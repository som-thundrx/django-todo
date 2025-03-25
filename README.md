# Python ToDo WebApp using Django

This project is a simple ToDo web application built with Django. It demonstrates the basics of Django by allowing users to create, view, and delete todo items, similar to popular note apps like Google Keep or Evernote.

Based on the [GeeksforGeeks tutorial](https://www.geeksforgeeks.org/python-todo-webapp-using-django/).

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Features

- **Add ToDo Items:** Create new notes/todo items with a title, details, and a timestamp.
- **View List:** Display all todo items in reverse chronological order.
- **Delete Items:** Remove a todo item by clicking the delete button.
- **Responsive UI:** Uses Bootstrap for a responsive and clean design.
- **Django Admin:** Manage todo items via the Django admin interface.

## Tech Stack

- **Backend:** Python, Django
- **Frontend:** HTML5, CSS3, Bootstrap, jQuery
- **Database:** SQLite (default, configurable)
- **Forms:** django-crispy-forms

## Prerequisites

- Python 3.x
- pip (Python package installer)
- Virtual environment tool (optional but recommended)

## Installation

Follow these steps to set up the project locally:

1. **Clone the Repository**

   ```sh
   git clone https://github.com/your-username/python-todo-webapp.git
   cd python-todo-webapp
Set Up Virtual Environment

Create and activate a virtual environment:

sh
Copy
Edit
python -m venv venv
# On Windows:
venv\Scripts\activate
# On Mac/Linux:
source venv/bin/activate
Install Required Packages

Install Django and other dependencies:

sh
Copy
Edit
pip install django
pip install django-crispy-forms
Start a New Django Project

If you haven’t already, create a new project:

sh
Copy
Edit
django-admin startproject todo_site
cd todo_site
Create the ToDo App

Create a Django app named todo:

sh
Copy
Edit
python manage.py startapp todo
Configure Settings

Add 'todo' and 'crispy_forms' to the INSTALLED_APPS in todo_site/settings.py.

Configure the database (default is SQLite):

python
Copy
Edit
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.sqlite3',
        'NAME': BASE_DIR / "db.sqlite3",
    }
}
Apply Migrations

sh
Copy
Edit
python manage.py makemigrations
python manage.py migrate
Run the Development Server

sh
Copy
Edit
python manage.py runserver
Open your web browser and navigate to http://127.0.0.1:8000/.
