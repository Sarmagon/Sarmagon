# Станислав Смирнов

Станислав Смирнов · Москва · **Junior Python Backend Developer**.

Завершил программу Python-разработчика (615 академических часов), курсы Django, Python Advanced и архитектуры ПО. Создаю учебные backend-проекты с API, базами данных, фоновыми задачами и тестами. Ищу первую роль в Python backend; коммерческий опыт разработки не заявляю.

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?logo=django&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)

[Портфолио](https://github.com/Sarmagon/python-portfolio) · [Резюме](https://github.com/Sarmagon/python-portfolio/tree/main/resume) · [Сертификаты](https://github.com/Sarmagon/python-portfolio/tree/main/certificates)

## Основные проекты

### Megano — интернет-магазин на Django

Итоговый проект курса «Python-фреймворк Django», Skillbox. Каталог, корзина, оформление и история заказов, профиль и учебная оплата через очередь в БД с отдельным worker. Django 5.2, SQLite, Poetry; медиа в SeaweedFS, мониторинг Prometheus, Grafana и node-exporter. В итоговой версии в Ubuntu прошли 66 тестов. Sentry — подготовленная интеграция; frontend предоставлен в учебном задании.

[Исходный код на GitLab](https://gitlab.skillbox.ru/stanislav_smirnov_2/python_django_diploma/-/tree/master) · [Описание и ограничения](https://github.com/Sarmagon/python-portfolio#megano--интернет-магазин-на-django)


### Twitter Clone Backend

[Исходный код](https://github.com/Sarmagon/twitter-clone-backend) · [CI](https://github.com/Sarmagon/twitter-clone-backend/actions/workflows/ci.yml)

Итоговый проект Python Advanced: REST API микроблогов, API-ключи, твиты, лента, лайки, подписки и загрузка изображений. FastAPI, PostgreSQL, SQLAlchemy, Alembic, Docker Compose, Nginx. 40 тестов, покрытие 78%, Ruff. Предоставленный готовый frontend отделён от собственного backend; собственный код не скрыт из статистики языков.

### Habit Tracker — Telegram и FastAPI

[Исходный код](https://github.com/Sarmagon/habit-tracker-telegram-fastapi) · [CI](https://github.com/Sarmagon/habit-tracker-telegram-fastapi/actions/workflows/ci.yml)

Привычки, ежедневные отметки, история и напоминания с часовыми поясами IANA. Отдельные Telegram frontend и HTTP backend; JWT, Argon2id для service secret, шифрование токенов бота, идемпотентные отметки. PostgreSQL, SQLAlchemy, Alembic, Poetry, Docker Compose. Проверены 47 тестов и отдельный тест PostgreSQL, Ruff и миграции. Учебный проект; публичное production-развёртывание не заявляется.

### Django CRM

[Исходный код](https://github.com/Sarmagon/django-crm)

Услуги, рекламные кампании, лиды, договоры, активные клиенты и статистика. Авторизация и роли оператора, маркетолога и менеджера, перевод лида в клиента. Django ORM, PostgreSQL, Docker Compose. Проверены 3 теста, системная проверка Django и миграции. Выход выполняется POST с CSRF. Pylint имеет замечания; зелёный CI не заявляется. Локальное учебное приложение.

### SportTogether Architecture

[Архитектурные материалы](https://github.com/Sarmagon/sport-together-architecture)

Завершённый проект курса «Архитектор программного обеспечения»: требования, стейкхолдеры, ADR, NFR, архитектурные диаграммы, сценарии, риски, компромиссы, стоимость владения и презентация. Это проектирование системы; работающий backend SportTogether не заявляется.

## Технологии

| Область | Практика в проектах |
|---|---|
| Язык и web | Python, FastAPI, Django, Flask, REST API, OpenAPI |
| Данные | PostgreSQL, SQLite, Django ORM, SQLAlchemy и Async SQLAlchemy, Peewee, Alembic |
| Фоновые задачи | Celery, Redis, Celery Beat, Flower; отдельная очередь PaymentJob в Django |
| Интеграции и доступ | Telegram Bot API, HTTP API, SMTP; JWT, Django auth/groups, API-ключи |
| Проверки | pytest, unittest, Ruff; flake8, black, isort, mypy в Cookbook; GitHub Actions |
| Запуск | Docker, Docker Compose, Nginx, Poetry, pip, Linux, SSH, Git |
| Мониторинг и хранение медиа | Prometheus, Grafana, node-exporter, SeaweedFS; Sentry — подготовленная интеграция |
| Архитектура | ADR, NFR, анализ рисков, компромиссов и стоимости владения |

## Обучение

Программа Python-разработчика и курс Django завершены 12.10.2026; Python Advanced — 24.09.2026; архитектура ПО — 22.09.2026. Все семь сертификатов доступны в портфолио, включая основы Python и документ GeekBrains.

## Направление развития

Production-развёртывание, наблюдаемость приложений, надёжность фоновых задач. Практика архитектурных решений подтверждается завершённым проектом SportTogether.

## Дополнительная практика

[Django Deployment Lab](https://github.com/Sarmagon/skillbox-django-deploy), Cookbook, обработка изображений, Parking API, Telegram-бот и File Sync — [в каталоге портфолио](https://github.com/Sarmagon/python-portfolio#дополнительные-проекты).

## Контакты

[GitHub](https://github.com/Sarmagon) · [Telegram @Sarmagon](https://t.me/Sarmagon) · [stasus.sv@mail.ru](mailto:stasus.sv@mail.ru)
