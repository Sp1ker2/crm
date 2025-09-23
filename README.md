# 📌 CRM Application

Лёгкая CRM-система на **FastAPI** с авторизацией, клиентами и пользователями.  
Использует **PostgreSQL** в качестве базы данных, **Alembic** для миграций и запускается через **Docker Compose**.

---

## ⚙️ Технологии

- ⚡ [FastAPI](https://fastapi.tiangolo.com/) — веб-фреймворк  
- 🐘 [PostgreSQL](https://www.postgresql.org/) — база данных  
- 🛠 [SQLAlchemy](https://www.sqlalchemy.org/) — ORM  
- 🔄 [Alembic](https://alembic.sqlalchemy.org/) — миграции БД  
- 📦 [Poetry](https://python-poetry.org/) — менеджер зависимостей  
- 🐳 [Docker Compose](https://docs.docker.com/compose/) — контейнеризация  

---

## 🚀 Запуск
### 🔹 Локально (через Poetry)
```bash
poetry install
poetry run uvicorn crm_app.main:app --reload
