## Описание 
Социальная сеть для загрузки и просмотра изображений котиков. При выкладывании котика, ему можно выбрать имя, цвет, дату рождения и достижения.

## Стек технологий:
- Python
- Django
- Django REST Framework
- PostgreSQL
- JavaScript
- Ngnix
- Docker
- Gunicorn
- GitHub Actions

## Запуск приложения в Docker

1. Клонируйте репозиторий:
2. В корне проекта переименуйте файл `.env.example`, в `.env`.
3. Запустите Docker контейнеры:
   ```bash
   docker-compose up -d
   ```
4. Выполните миграции и создайте суперпользователя:
   ```bash
   docker-compose exec backend python manage.py migrate
   docker-compose exec backend python manage.py createsuperuser
   docker-compose exec backend python manage.py collectstatic --no-input
   ```
