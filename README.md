# All_cats

All_cats — это веб-приложение для обмена и управления информацией о кошках. Проект состоит из фронтенда, созданного на React, и бэкенда на основе Django и Django REST Framework.

## Структура проекта

- `frontend/`: Содержит фронтенд-приложение на React.
- `backend/`: Содержит бэкенд-приложение на Django.

## Возможности

- Аутентификация и авторизация пользователей.
- Создание, редактирование и удаление профилей кошек.
- Просмотр профилей кошек с пагинацией.

## Стек технологий

- Python
- Django
- Django REST Framework
- PostgreSQL
- JavaScript
- React
- Nginx
- Docker
- Gunicorn
- GitHub Actions

## Установка

### Фронтенд

Клонируйте репозиторий и перейдите в директорию с фронтендом:

```bash
git clone git@github.com:aeee78/all_cats.git
```

Установите зависимости:

```bash
npm install
```

Запустите фронтенд-приложение:

```bash
npm run start
```

### Бэкенд

Перейдите в директорию с бэкендом:


Создайте и активируйте виртуальное окружение:

```bash
python -m venv venv
```

```bash
source venv/bin/activate  # В Windows используйте `venv\Scripts\activate
```

Установите зависимости:

```bash
pip install -r requirements.txt
```

Выполните миграции базы данных:

```bash
python manage.py migrate
```

Создайте суперпользователя:

```bash
python manage.py createsuperuser
```

Запустите сервер бэкенда:

```bash
python manage.py runserver
```

## Использование

### Фронтенд

После запуска фронтенд-сервера вы сможете получить доступ к приложению по адресу `http://localhost:3000`.

### Бэкенд

Сервер бэкенда будет доступен по адресу `http://localhost:8000`. Вы также можете использовать интерфейс администрирования Django по адресу `http://localhost:8000/admin`.

## Вклад

1. Сделайте форк репозитория.
2. Создайте новую ветку: `git checkout -b my-feature-branch`.
3. Внесите свои изменения и зафиксируйте их: `git commit -m 'Add new feature'`.
4. Отправьте изменения в свою ветку: `git push origin my-feature-branch`.
5. Создайте pull request.



# All_cats

All_cats is a web application for sharing and managing information about cats. The project consists of a frontend built with React and a backend powered by Django and Django REST framework.

## Project Structure

- `frontend/`: Contains the React frontend application.
- `backend/`: Contains the Django backend application.

## Features

- User authentication and authorization.
- Create, edit, and delete cat profiles.
- View cat profiles with pagination.

## Technology Stack

- Python
- Django
- Django REST Framework
- PostgreSQL
- JavaScript
- React
- Nginx
- Docker
- Gunicorn
- GitHub Actions

## Installation

### Frontend

Clone the repository and navigate to the frontend directory:

```bash
git clone git@github.com:aeee78/all_cats.git
```


Install the dependencies:

```bash
npm install
```

Start the frontend application:

```bash
npm run start
```

### Backend

Navigate to the backend directory:

Create and activate a virtual environment:

```bash
python -m venv venv
```

```
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

Install the dependencies:

```bash
pip install -r requirements.txt
```

Run the database migrations:

```bash
python manage.py migrate
```

Create a superuser:

```bash
python manage.py createsuperuser
```

Start the backend server:

```bash
python manage.py runserver
```

## Usage

### Frontend

Once the frontend server is running, you can access the application at `http://localhost:3000`.

### Backend

The backend server will be available at `http://localhost:8000`. You can use the Django admin interface at `http://localhost:8000/admin`.

## Contributing


1. Fork the repository.
2. Create a new branch: `git checkout -b my-feature-branch`.
3. Make your changes and commit them: `git commit -m 'Add new feature'`.
4. Push to the branch: `git push origin my-feature-branch`.
5. Create a pull request.

