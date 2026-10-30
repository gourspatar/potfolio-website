# Personal Portfolio Website

A personal portfolio website built with **Python and Django** as my first project while learning Django web development.

The website introduces me, showcases my projects, and provides a way for visitors to contact me.

## Features

- Home page
- About page
- Projects page
- Contact page
- Shared navigation bar and footer
- Reusable templates using Django template inheritance
- Custom CSS styling
- Static file management with Django's static files system

## Technologies Used

- Python
- Django
- HTML5
- CSS3

## Project Structure

```text
Portfolio_Website/
│
├── config/
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── portfolio/
│   ├── migrations/
│   ├── static/
│   │   └── portfolio/
│   │       ├── css/
│   │       │   └── style.css
│   │       └── images/
│   ├── templates/
│   │   └── portfolio/
│   │       ├── base.html
│   │       ├── home.html
│   │       ├── about.html
│   │       ├── projects.html
│   │       └── contact.html
│   ├── views.py
│   ├── urls.py
│   └── models.py
│
├── manage.py
├── .gitignore
└── README.md
```

## Getting Started

Follow these steps to run the project locally.

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Navigate into the project

```bash
cd Portfolio_Website
```

### 3. Create a virtual environment

```bash
python -m venv .venv
```

### 4. Activate the virtual environment

For Windows PowerShell:

```powershell
.venv\Scripts\Activate.ps1
```

### 5. Install Django

```bash
python -m pip install django
```

### 6. Apply database migrations

```bash
python manage.py migrate
```

### 7. Start the development server

```bash
python manage.py runserver
```

### 8. Open the website

Visit:

http://127.0.0.1:8000/

## What I Learned

Through this project, I practised:

- Setting up a Django project and application.
- Understanding the difference between a project and an app.
- Creating URL routes and views.
- Rendering HTML templates.
- Using Django template inheritance.
- Managing static files such as CSS and images.
- Building multiple pages with a shared layout.

## Project Status

Project 1 — Personal Portfolio Website.

Built as part of my Django project-based learning journey.

---

**More projects coming as I continue learning Django!**