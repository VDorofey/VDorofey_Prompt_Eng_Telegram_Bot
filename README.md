# VDorofey_Prompt_Eng_Telegram_Bot
Python Telegram AI Bot
Telegram-бот - помощник при обучении школьников 8-11 классов технологиям анализа данных и МО. 
Он использует языковую модель YandexGPT, доступ к ней осуществляется по API. Бот написан на Python и использует библиотеку python-telegram-bot для работы с Telegram API.

Инструкции по установке
1. Скачайте и распакуйте файлы проекта, откройте папку в VsCode.

git clone https://github.com/labintsev/python-telegram-ai-bot.git](https://github.com/VDorofey/VDorofey_Prompt_Eng_Telegram_Bot.git
cd VDorofey_Prompt_Eng_Telegram_Bot

2. Создайте виртуальное окружение
Виртуальное окружение помогает изолировать зависимости проекта.

3. Установите зависимости
Можно сразу установить галочку на файле requirements.txt при создании виртуального окружения в VsCode.

4. Настройка переменных окружения
Создайте файл .env в корневой папке проекта и добавьте туда ваши ключи:

TELEGRAM_BOT_TOKEN=ваш_токен_бота
YA_API_KEY=ваш_яндекс_api_key
YA_FOLDER_ID=ваш_каталог_яндекс_консоли  
TELEGRAM_BOT_TOKEN — получите в @BotFather в Telegram.
YA_API_KEY — получите на сервисе, который используется для ИИ (например, YandexGPT).
YA_FOLDER_ID - скопируйте из яндекс консоли.
5. Запуск бота
Запустите бота командой:
python bot.py
Если всё настроено верно, бот начнет работать и принимать сообщения в Telegram.
