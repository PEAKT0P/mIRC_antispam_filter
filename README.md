# mIRC Antispam Filter

[English](#english) | [Русский](#russian)

## English

### Overview
A powerful antispam protection script for mIRC clients that provides automated moderation capabilities. The script uses advanced pattern matching to detect and prevent various types of spam messages in IRC channels.

### Features
- Real-time spam detection and prevention
- Customizable channel and server lists
- GUI-based configuration interface
- Multiple spam detection patterns:
  - ASCII art spam
  - URL spam
  - Repeated characters
  - Excessive capitalization
  - Mass mentions
  - Numerical spam
  - Emoji spam
  - Advertisement keywords
  - Phishing attempts

### Installation
1. Create the following directory structure in your mIRC folder:
```
mIRC/
└── texts/
    ├── antispam_chan.txt
    └── antispam_server.txt
```
2. Place the script in your mIRC scripts folder
3. Load the script via mIRC Scripts Editor
4. Configure protected channels and allowed servers through the context menu

### Usage
- Right-click on any channel to access the Antispam menu
- Use `/antispam on` or `/antispam off` to control the script
- Add channels and servers through the settings interface
- The script automatically bans users posting spam (except channel operators)

### Requirements
- mIRC 7.x or higher
- Write permissions in the mIRC directory

### Development History
This script was developed as a collaboration between:
- **PEAKTOP** - Initial concept and base functionality
- **Claude (Anthropic)** - Code optimization and enhanced spam detection
- Development focused on creating a robust, user-friendly anti-spam solution for IRC channels

### License
MIT License

---

## Russian

### Обзор
Мощный скрипт защиты от спама для mIRC, обеспечивающий автоматическую модерацию. Скрипт использует продвинутую систему сопоставления паттернов для обнаружения и предотвращения различных типов спам-сообщений в IRC каналах.

### Возможности
- Обнаружение и предотвращение спама в реальном времени
- Настраиваемые списки каналов и серверов
- Графический интерфейс настройки
- Множество паттернов обнаружения спама:
  - ASCII арт спам
  - Спам ссылками
  - Повторяющиеся символы
  - Чрезмерное использование заглавных букв
  - Массовые упоминания
  - Числовой спам
  - Спам эмодзи
  - Рекламные ключевые слова
  - Попытки фишинга

### Установка
1. Создайте следующую структуру директорий в папке mIRC:
```
mIRC/
└── texts/
    ├── antispam_chan.txt
    └── antispam_server.txt
```
2. Поместите скрипт в папку скриптов mIRC
3. Загрузите скрипт через редактор скриптов mIRC
4. Настройте защищаемые каналы и разрешенные серверы через контекстное меню

### Использование
- Нажмите правой кнопкой мыши на любом канале для доступа к меню Антиспам
- Используйте команды `/antispam on` или `/antispam off` для управления скриптом
- Добавляйте каналы и серверы через интерфейс настроек
- Скрипт автоматически банит пользователей, отправляющих спам (кроме операторов канала)

### Требования
- mIRC 7.x или выше
- Права на запись в директории mIRC

### История разработки
Этот скрипт был разработан в сотрудничестве между:
- **PEAKTOP** - Изначальная концепция и базовый функционал
- **Claude (Anthropic)** - Оптимизация кода и улучшенное обнаружение спама
- Разработка была сосредоточена на создании надежного и удобного решения для защиты IRC каналов от спама

### Лицензия
MIT License
