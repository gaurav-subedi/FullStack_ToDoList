# 📝 To-Do List App (Full Stack)

A simple and elegant full-stack To-Do List web application built using **React** for the frontend, **Django REST Framework** for the backend, and **PostgreSQL** as the database.

---

## 🚀 Tech Stack

- **Frontend**: React, JavaScript, CSS
- **Backend**: Django, Django REST Framework
- **Database**: PostgreSQL
- **Tools**: pgAdmin, Git, VS Code

---

## 🎯 Features

- ✅ Add, view, and delete tasks
- 🎨 Clean, responsive UI
- 🔌 RESTful API with full CRUD support
- 🐘 PostgreSQL integration with Django ORM
- 🔐 Django admin panel for backend management

---

## 📁 Project Structure

```bash
task-backend/
├── backend/             # Django project root
│   ├── backend/         # Django settings, URLs
│   ├── todo/            # Task model, views, serializers
│   ├── manage.py
│   └── requirements.txt

task-frontend/
├── src/
│   ├── App.js
│   ├── index.js
│   ├── components/
│       ├── NavBar.js
│       ├── AddTask.js
│       └── MainPagee.js
├── public/
└── package.json
