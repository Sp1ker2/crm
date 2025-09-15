# crm
CREATE USER crm_user WITH PASSWORD '1234';
CREATE DATABASE crm_db OWNER crm_user;
GRANT ALL PRIVILEGES ON DATABASE crm_db TO crm_user;



psql -U crm_user -d crm_db -h localhost -p 5432
