# Telegram Finance Bot

Бот для учета доходов и расходов с простыми командами и SQLite-базой данных.

## 📌 Возможности
- Добавление доходов (`/add_salary`)
- Добавление расходов (`/add_expense`)
- Просмотр месячного отчета (`/month_report`)
- Просмотр общего отчета (`/total_report`)

## 🚀 Установка

1. Клонируйте репозиторий:
   ```bash
   git clone (https://github.com/jorjlionov/Moderator-Helper-Telegram-Bot.git)
   cd 
Установите зависимости:

bash
pip install -r requirements.txt
Создайте файл .env и добавьте токен бота:

text
TELEGRAM_BOT_TOKEN=ваш_токен_здесь
Запустите бота:

bash
python main.py
⚙️ Команды бота
/start — показать приветственное сообщение

/add_salary 

[сумма] [категория] — добавить доход

/add_expense 

[сумма] [категория] — добавить расход

/month_report — показать отчет за текущий месяц

/total_report — показать общий отчет

База данных finance.db создается автоматически при первом запуске

📝 Примеры использования
text
/add_salary 50000 зарплата
/add_expense 1500 продукты
/month_report
💡 Совет: Получите токен бота у @BotFather в Telegram.
