
# blago-guide-gpt

Ассистент для смарт-контракта BLAGO и блокчейна ZHCASH. Бот на базе GPT с интеграцией Telegram, поддержкой RAG и автоматизацией Make.

## Возможности
- Подключение к Telegram-боту
- Поддержка fine-tuned модели GPT-3.5 или GPT-4
- Использование RAG (retrieval-augmented generation) для ответов
- Подключение к платформе Make (ex. Integromat) для автоматизации

## Структура проекта
- `bot/` — Telegram-бот
- `api/` — взаимодействие с OpenAI
- `model/` — настройки модели и system prompt
- `docs/` — документация и инструкции
- `.env.example` — переменные окружения
- `requirements.txt` — зависимости Python

## Установка

1. Клонируйте репозиторий:
```bash
git clone https://github.com/ZHCASH-Development/blago-guide-gpt.git
cd blago-guide-gpt
```

2. Установите зависимости:
```bash
pip install -r requirements.txt
```

3. Создайте файл `.env` по примеру `.env.example`

4. Запустите бота:
```bash
python bot/main.py
```

---

### 🛡 Авторские права

© Все права защищены. Проект BlagoGUIDE создан и принадлежит автору и разработчику — **Мастер Марго**.

Запрещается любое использование, копирование, распространение, а также доработка, запуск или внедрение данного проекта без предварительного письменного согласования с автором.

📬 Контакт для согласования: [@Margo_voin_sveta](https://t.me/Margo_voin_sveta)
