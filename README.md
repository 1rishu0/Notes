# Notes App

A full-stack Notes application built with **Python**, **Django**, and **React.js**. It allows users to securely manage their notes with authentication and a responsive user interface.

## Features

* User Authentication (JWT)
* Create, Read, Update, and Delete (CRUD) Notes
* REST API using Django REST Framework
* React.js Frontend
* Responsive UI
* Secure access to user-specific notes

## Tech Stack

* Python
* Django
* Django REST Framework
* React.js
* JavaScript
* HTML
* CSS
* SQLite

## Project Structure

```
Notes/
├── backend/
│   ├── api/
│   ├── backend/
│   ├── manage.py
│   └── requirements.txt
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── vite.config.js
│
└── README.md
```

## Installation

### Clone the Repository

```bash
git clone <repository-url>
cd Notes
```

### Frontend Setup

```bash
cd frontend

npm install

npm run dev
```

### Backend Setup

```bash
cd backend

uv add pyproject.toml

uv run django-admin makemigrations 

uv run django-admin migrate

uv run manage.py runserver
```

## Environment Variables

Create a `.env` file inside the frontend directory.

```env
VITE_API_URL=http://127.0.0.1:8000
```

## API Endpoints

* `/api/token/` - Login
* `/api/token/refresh/` - Refresh JWT Token
* `/api/user/register/` - Register User
* `/api/notes/` - Manage Notes

## Screenshots

<img width="952" height="794" alt="Notes-1" src="https://github.com/user-attachments/assets/abe48221-4092-405a-a461-e63485882ab1" />


## Future Improvements

* Search Notes
* Categories/Tags
* Dark Mode
* Rich Text Editor
* Note Sharing
* File Attachments

## License

This project is licensed under the MIT License.
