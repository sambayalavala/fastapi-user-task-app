# FastAPI User Task Management API

A RESTful API built with FastAPI for managing users and tasks.

## Features

- User Management (CRUD operations)
  - Create new users
  - Get all users
  - Get user by ID
  - Update user details
  - Delete users
- Task Management (CRUD operations)
  - Create new tasks
  - Get all tasks
  - Get task by ID
  - Update task details
  - Delete tasks

## API Endpoints

### User Endpoints
- `POST /users/` - Create a new user
- `GET /users/` - Get all users
- `GET /users/{user_id}` - Get a specific user
- `PUT /users/{user_id}` - Update a user
- `DELETE /users/{user_id}` - Delete a user

### Task Endpoints
- `POST /tasks/` - Create a new task
- `GET /tasks/` - Get all tasks
- `GET /tasks/{task_id}` - Get a specific task
- `PUT /tasks/{task_id}` - Update a task
- `DELETE /tasks/{task_id}` - Delete a task

## Setup and Installation

1. Clone the repository:
```bash
git clone https://github.com/sambayalavala/FastAPI-User-Task-App.git
cd FastAPI-User-Task-App
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the application:
```bash
uvicorn main:app --reload
```

The API will be available at `http://localhost:8000`

## API Documentation

Once the server is running, you can access:
- Swagger UI documentation at `http://localhost:8000/docs`
- ReDoc documentation at `http://localhost:8000/redoc`
