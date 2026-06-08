# 🎂 Birthday Calculator

Веб-приложение на Django для хранения и управления днями рождения.  
Пользователи могут регистрироваться, добавлять, редактировать и удалять записи через удобный веб-интерфейс.

## 🛠 Технологии

- Python
- Django
- SQLite
- HTML
- Git

## ⚙️ Установка и запуск

**1. Клонируй репозиторий**
```bash
git clone https://github.com/God-Rav/birthday-calculator.git
cd birthday-calculator
```

**2. Создай и активируй виртуальное окружение**
```bash
python -m venv venv

# Windows
venv\Scripts\activate

# Linux / macOS
source venv/bin/activate
```

**3. Установи зависимости**
```bash
pip install -r requirements.txt
```

**4. Создай файл `.env`** в корне проекта и добавь секретный ключ:
```
SECRET_KEY=твой_секретный_ключ
DEBUG=True
```

Сгенерировать ключ можно командой:
```bash
python -c "from django.core.management.utils import get_random_secret_key; print(get_random_secret_key())"
```

**5. Примени миграции**
```bash
python manage.py migrate
```

**6. Запусти сервер**
```bash
python manage.py runserver
```

**7. Открой в браузере**
```
http://127.0.0.1:8000
```

## 📋 Возможности

- Регистрация и авторизация пользователей
- Добавление дней рождения
- Редактирование и удаление записей
- Публикация записей через веб-интерфейс

## 👤 Автор

**Равиль** — [github.com/God-Rav](https://github.com/God-Rav)
