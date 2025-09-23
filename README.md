# crm
CREATE USER crm_user WITH PASSWORD '1234';
CREATE DATABASE crm_db OWNER crm_user;
GRANT ALL PRIVILEGES ON DATABASE crm_db TO crm_user;



psql -U crm_user -d crm_db -h localhost -p 5432



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

## 📂 Структура проекта

