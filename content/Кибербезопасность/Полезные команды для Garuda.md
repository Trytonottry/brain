### Полезные команды 

1)  Диагностика диска
```bash
 sudo smartctl -a /dev/nvme0n1
```

 2) Глубокий анализ системы
 ```bash
 sudo lynis audit system 
 ```

3) Запуск контейнеров docker
```bash
docker-compose up --build 
docker-compose up -d --build 
```

4)  Команда для записи образа диска
```bash
sudo dd if=ubuntu-22.04.iso of=/dev/sdb bs=4M status=progress oflag=sync
```

5) Команда передачи файлов между устройствами линукс
```bash
rsync -avz -e ssh /home/semyon/Documents/GCode/smart_home_hybrid_lubuntu kali@10.147.19.210:/home/kali/
```

### Починка Nextcloud

1)  Очистка системы
```bash
sudo ./purge_nextcloud_snap.sh
```

2) Чистовая установка
```bash
sudo ./nextcloud_clean_install.sh
sudo ./next.sh
```

### Github Token

push token: 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

### Wake-On-Lan

1)  HP Proliant dl380p gen 8
```bash
sudo ethtool -s eno1 wol g
ip a
```

2)  Orange Pi 3 Zero
```bash
sudo apt update
sudo apt install wakeonlan
wakeonlan ac:16:2d:6f:7d:c5
```

Loading, wait 10 mins, then connect.

### ZeroTier
```bash
curl -s https://install.zerotier.com | sudo bash
```

Проверяем сервис:
```bash
sudo systemctl enable zerotier-one
sudo systemctl start zerotier-one
sudo systemctl status zerotier-one
```

Присоединяем:
```bash
sudo zerotier-cli join 17d709436c2ad76c
```