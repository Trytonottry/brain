**Taskwarrior** — локальный инструмент для управления задачами в терминале, настроенный для хранения данных в `/mnt/kali-home/home/kali/taskwarrior` для доступа из Garuda, Kali и Parrot. Поддерживает теги, проекты, дедлайны и интеграцию с Obsidian. Эта шпаргалка содержит основные команды и настройки для ежедневного использования, включая `taskwarrior-tui` и интеграцию с Obsidian.

---

## Установка и настройка

### Установка

- Установить Taskwarrior:
  ```bash
  sudo pacman -S task
  ```

- Установить TUI (терминальный интерфейс):
  ```bash
  yay -S taskwarrior-tui
  ```

### Настройка хранения

-  Настроить общий раздел:
  ```bash
mkdir -p /mnt/kali-home/home/kali/taskwarrior
ln -s /mnt/kali-home/home/kali/taskwarrior ~/.task
```

-  Проверить права (для пользователя semyon, UID=1000):
  ```bash
sudo chown -R semyon:semyon /mnt/kali-home/home/kali/taskwarrior
```

### Конфигурация

- Редактировать ~/.taskrc:
  ```bash
  nano ~/.taskrc
```

Добавить:
```text
data.location=/mnt/kali-home/home/kali/taskwarrior
report.list.columns=id,description,due,project,tags
```

- Проверить конфиг:
  ```bash
  task diag
```

### Алиасы
Добавить в ~/.zshrc для удобства:
  ```bash
alias t='task'
alias tt='taskwarrior-tui'
alias tadd='task add'
alias tlist='task list'
```
Перезагрузить: source ~/.zshrc.

## Основные команды Taskwarrior
### Добавление задач
- Простая задача:
  ```bash
  t add "Закончить скрипт Python"
```

- С дедлайном, проектом, приоритетом:
  ```bash
  t add "Прочитать документацию" due:tomorrow project:Programming priority:H
```

- С тегами:
  ```bash
  t add "Проверить отчёт" due:2025-10-15 +analytics +urgent
```

- Рекуррентная задача (ежедневно):
  ```bash
  t add "Проверить почту" due:tomorrow recur:daily
```

### Просмотр задач
- Все активные задачи:
  ```bash
  t list
```

- По проекту:
  ```bash
  t project:Programming list
```

- По тегу:
  ```bash
  t +analytics list
```

- Все задачи (включая завершённые):
  ```bash
  t all
```

- Краткий список:
  ```bash
  t next
```

