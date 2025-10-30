==> si se necesita instalar todo l q tiene requirements
pip install -r requirements.txt

sino agrega todos los requerimento ejecutar nuevamente: 
pip freeze > requirements.txt


------------------
# Task Manager – Django + Angular

Aplicación web para gestión de tareas con autenticación JWT.

## Backend
- Django 5 + Django REST Framework
- Base de datos SQLite
- Endpoints:
  - POST /api/register/
  - POST /api/login/
  - GET /api/tasks/

## Frontend
- Angular 18
- Angular Material
- Login, CRUD y filtros

## Cómo ejecutar
1. cd backend && python manage.py runserver
2. cd frontend && ng serve
