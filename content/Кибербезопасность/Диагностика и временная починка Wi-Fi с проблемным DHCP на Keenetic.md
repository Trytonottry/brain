## 1. Наружная диагностика Wi-Fi и DHCP

### 1.1 Проверка видимости Wi-Fi

```bash
# Linux
nmcli dev wifi list
# или
iwlist wlan0 scan | grep ESSID
```

- Если SSID **не виден** → проблема на уровне радио.
    
- Если SSID **виден** → продолжаем диагностику DHCP.

### 1.2 Проверка получения IP через DHCP
```bash
sudo dhclient wlan0
ip a show wlan0
```

- IP `0.0.0.0` → DHCP не отвечает.
    
- IP присвоен → проверяем доступ к интернету.

### 1.3 Сниффинг DHCP пакетов
```bash
sudo tcpdump -i wlan0 port 67 or port 68 -n
```

- DHCP DISCOVER → отправка клиентом.
    
- DHCP OFFER → ответ роутера.
    
- OFFER не приходит → DHCP на Wi-Fi не работает.

### 1.4 Проверка IP-конфликтов
```bash
nmap -sn 192.168.1.0/24
arp -n
```

Ищем дублирующиеся IP, особенно у IP-телефонии.

### 1.5 Временное решение: статический IP
```bash
sudo ip addr add 192.168.1.250/24 dev wlan0
sudo ip route add default via 192.168.1.1
ping 192.168.1.1
ping 8.8.8.8
```

### 1.6 Дополнительно
```bash
arp -n
nmap -p 22,23,80,443 192.168.1.1
```

## 2. Диагностика через консольный провод
Подходит, если веб-доступ заблокирован, сброс запрещён, а у тебя есть RJ50 → USB кабель.
### 2.1 Подключение к консоли
```bash
# Определяем устройство
ls /dev/ttyUSB*  # или /dev/ttyACM*

# Подключаемся через minicom
sudo apt install minicom
sudo minicom -D /dev/ttyUSB0 -b 115200

# Альтернатива через screen
sudo screen /dev/ttyUSB0 115200
```

- Параметры: 115200, 8N1.
    
- После Enter должно появиться приглашение `login:`.

### 2.2 Проверка состояния Wi-Fi
```bash
# Список интерфейсов
ifconfig -a
iwconfig
```

- Ищем интерфейсы `wl0` / `wlan0`.
    
- Проверяем статус радио (включено/выключено, SSID, частота).

### 2.3 Логи Wi-Fi
