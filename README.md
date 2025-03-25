# TaskNest

## Overview
TaskNest is a simple and efficient to-do web application built using Django. It allows users to create, update, and delete tasks, helping them stay organized and manage their daily activities effectively.

## Features
- Add, update, and delete tasks effortlessly
- Mark tasks as completed
- User-friendly interface with a minimalistic design
- Persistent storage using SQLite
- Built using Django for a robust backend

## Tech Stack
- **Backend:** Django (Python)
- **Frontend:** HTML, CSS (No Bootstrap)
- **Database:** SQLite

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/tasknest.git
   cd tasknest
   ```
2. Set up a virtual environment:
   ```sh
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Apply migrations:
   ```sh
   python manage.py makemigrations
   python manage.py migrate
   ```
5. Run the server:
   ```sh
   python manage.py runserver
   ```
6. Open the application in your browser:
   ```
   http://127.0.0.1:8000/
   ```

## Usage
- Navigate to the web interface and add new tasks.
- Edit or delete tasks as needed.
- Mark tasks as completed when done.

## Contribution
Feel free to fork the repository and submit pull requests for improvements and bug fixes.

## License
This project is licensed under the MIT License.


