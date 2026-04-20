# FastAPI Task Manager

## Project Overview
This is a simple Task Manager application built using FastAPI.  
Users can register, login, and manage their tasks.

## Features
- User Registration
- User Login (JWT Authentication)
- Create Task
- View Tasks
- Update Task
- Delete Task

## Tech Stack
- Python
- FastAPI
- SQLAlchemy
- SQLite
- JWT Authentication

## How to Run

1. Install dependencies:
pip install -r requirements.txt

2. Run the server:
uvicorn main:app --reload

3. Open in browser:
http://127.0.0.1:8000/docs

## API Endpoints

### Authentication
- POST /register
- POST /login

### Tasks
- POST /tasks
- GET /tasks
- GET /tasks/{id}
- PUT /tasks/{id}
- DELETE /tasks/{id}

## Notes
- Do not upload .env file
- Do not upload tasks.db

## Author
Jannani Varadharaj