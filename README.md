# Привет! Я Станислав Смирнов 👋

### Python Backend Developer

Развиваюсь в backend-разработке на Python и проектировании программных систем.

Работаю с REST API, базами данных, ORM, асинхронным Python, фоновыми задачами, тестированием и CI.

---

## 🛠️ Технологии

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?logo=django&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-red)
![SQLite](https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?logo=pytest&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)

---

## 🚀 Основные проекты

### 🐍 Python Backend Portfolio

Мои проекты по Python-разработке:

- FastAPI
- Flask
- Django
- PostgreSQL
- Docker / Docker Compose
- SQLAlchemy
- Async SQLAlchemy
- Celery + Redis
- Telegram Bot API
- pytest
- GitHub Actions

👉 [Открыть Python Portfolio](https://github.com/Sarmagon/python-portfolio)

---

### 🤖 Habit Tracker — Telegram + FastAPI

🔗 [habit-tracker-telegram-fastapi](https://github.com/Sarmagon/habit-tracker-telegram-fastapi)

Трекер привычек с отдельным Telegram frontend и HTTP backend: создание и редактирование привычек, ежедневные отметки, история и напоминания с часовыми поясами IANA.

- JWT, проверка внутреннего service secret по Argon2id-хешу и зашифрованное хранилище токенов бота.
- PostgreSQL, SQLAlchemy, миграции Alembic, идемпотентные отметки и блокировки строк.
- Poetry, Docker Compose, pytest и GitHub Actions: Ruff, тесты, миграции и отдельные проверки PostgreSQL.

**Статус:** учебный проект для локального запуска; публичный production deployment не заявляется.
**Стек:** Python 3.12, FastAPI, pyTelegramBotAPI, PostgreSQL, SQLAlchemy, Alembic, SQLite, Poetry, Docker Compose, pytest, Ruff.

---

### 🐦 Twitter Clone Backend

Учебный backend корпоративного сервиса микроблогов — итоговый проект Python Advanced.

В проекте реализованы:

- REST API на FastAPI и авторизация по API-ключу
- твиты, лайки, подписки и лента
- загрузка изображений с проверкой содержимого и прав доступа
- PostgreSQL, SQLAlchemy и миграции Alembic
- запуск через Docker Compose с Nginx и готовым интерфейсом Vue
- тесты API на pytest и проверки Ruff

👉 [Открыть Twitter Clone Backend](https://github.com/Sarmagon/twitter-clone-backend)

---

### 📊 Django CRM

Веб-приложение для учёта услуг, рекламных кампаний, клиентов и контрактов.

В проекте реализованы:

- авторизация и роли оператора, маркетолога и менеджера
- работа с услугами, кампаниями, лидами, контрактами и активными клиентами
- перевод лида в активного клиента
- статистика рекламных кампаний
- PostgreSQL и запуск через Docker Compose

👉 [Открыть Django CRM](https://github.com/Sarmagon/django-crm)

---

### 🏗️ SportTogether Architecture

Архитектурный проект глобального спортивного приложения.

В проекте представлены:

- бизнес- и функциональные требования
- ADR
- NFR
- архитектурные диаграммы
- сценарии использования
- анализ рисков
- стоимость владения
- архитектурная презентация

👉 [Открыть SportTogether Architecture](https://github.com/Sarmagon/sport-together-architecture)

---

### 🚢 Django Deployment Lab

🔗 [skillbox-django-deploy](https://github.com/Sarmagon/skillbox-django-deploy)

Учебная упаковка Django-приложения для запуска в Docker Compose и переноса на Linux VM через SSH. Зависимости фиксируются Poetry; миграции и сбор статики выполняются при запуске.

**Стек:** Python 3.11, Django 4.2, Django REST Framework, SQLite, Poetry, Docker Compose.
**Ограничения:** `runserver`, `DEBUG=1`, отсутствие TLS и постоянного тома SQLite. Это deployment practice; production deployment и доступность публичного сервера не заявляются.

---

## Django diploma — на ревью

Интернет-магазин Megano: каталог, отзывы, профиль, корзина, оформление заказов, доставка, история и учебная оплата через очередь в БД. Python, Django 5.2, SQLite, Poetry, Pillow; предоставленный учебный frontend адаптирован к backend.

**Статус на 11.10.2026:** финальный этап отправлен на ревью, принятие диплома не подтверждено. Публичный репозиторий будет добавлен после завершения ревью и проверки возможности распространения учебных материалов. Это не интеграция с настоящим платёжным провайдером; Celery/Redis в очереди не используются.

---

## 📚 Практика и дальнейшее обучение

- Django: углубляю практику
- архитектурные компромиссы, ADR и NFR на основе завершённого проекта SportTogether
- надёжность фоновых задач и production-развёртывание; микросервисный подход как направление дальнейшего изучения

---

## 🎓 Обучение и сертификаты

- **Skillbox — Основы Python. Часть 1**  
  [Сертификат № SKB0469958](https://github.com/Sarmagon/python-portfolio/blob/main/certificates/skillbox-python-part-1.png) · 10.02.2026

- **Skillbox — Основы Python. Часть 2**  
  [Сертификат № SKB0487169](https://github.com/Sarmagon/python-portfolio/blob/main/certificates/skillbox-python-part-2.png) · 02.05.2026

- **GeekBrains / Skillbox Holding — Python-разработчик**  
  [Сертификат № 2835512](https://github.com/Sarmagon/python-portfolio/blob/main/certificates/geekbrains-python-developer.pdf) · 17.06.2026

- **Skillbox — Архитектор программного обеспечения**  
  [Сертификат № SKB0505176](https://github.com/Sarmagon/python-portfolio/blob/main/certificates/skillbox-software-architect.png) · 22.09.2026

- **Skillbox — Python Advanced**\
  [Сертификат № SKB0506025](https://github.com/Sarmagon/python-portfolio/blob/main/certificates/skillbox-python-advanced.png) · 24.09.2026

---

## 🎯 Направление развития

Моя цель — развиваться как **Python Backend Developer** и работать над реальными backend-системами.

Интересуют задачи, связанные с:

- REST API
- backend-сервисами
- базами данных
- автоматизацией
- интеграциями
- тестированием
- архитектурой приложений

---

## 📫 Контакты

- GitHub: [@Sarmagon](https://github.com/Sarmagon)
- Telegram: [@Sarmagon](https://t.me/Sarmagon)
- Email: [stasus.sv@mail.ru](mailto:stasus.sv@mail.ru)
