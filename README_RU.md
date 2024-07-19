# 🎰 Mines Game Bot

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![Telegram](https://img.shields.io/badge/Telegram-Bot-blue.svg)
![Flask](https://img.shields.io/badge/Flask-3.x-red.svg)
![python-telegram-bot](https://img.shields.io/badge/python--telegram--bot-20.x-green.svg)
![Stars](https://img.shields.io/github/stars/stavrmoris/Mines_game-Bot)

Mines Game Bot - это Telegram-бот, который предоставляет пользователям игру в сапера и сигналы.

[Read in English](README.md)

## 📚 Содержание

- [Описание](#-описание)
- [Установка](#-установка)
- [Использование](#-использование)
- [Лицензия](#-лицензия)

## 📜 Описание

Этот код реализует Telegram-бота, который позволяет пользователям играть в игру сапер и получать сигналы. Бот предоставляет интерактивный интерфейс с кнопками для доступа к инструкциям и веб-приложению. Он использует библиотеку `python-telegram-bot` для взаимодействия с Telegram API.

## 🔧 Установка

1. **Клонируйте репозиторий:**
    ```bash
    git clone https://github.com/stavrmoris/Mines_game-Bot.git
    cd Mines_game-Bot
    ```

2. **Создайте виртуальное окружение и активируйте его:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # для Windows используйте `venv\Scripts\activate`
    ```

3. **Установите необходимые зависимости:**
    ```bash
    pip install -r requirements.txt
    ```

4. **Откройте главный файл `main.py` и добавьте свои данные:**
    ```
    TOKEN=your_telegram_bot_token
    CHANNEL_URL='your_channel_url'
    WEB_APP_URL='your_web_app_url'
    ```

## 🚀 Использование

1. **Запустите бота:**
    ```bash
    python bot.py
    ```

2. **Взаимодействуйте с ботом:**
   - Откройте Telegram и найдите своего бота по имени.
   - Отправьте команду `/start`, чтобы начать использование бота.
   - Следуйте инструкциям и играйте в игру сапер или получайте сигналы.

## 📄 Лицензия

Этот проект лицензируется по лицензии MIT. Подробнее см. в файле [LICENSE](LICENSE).
