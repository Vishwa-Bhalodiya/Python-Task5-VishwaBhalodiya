# Django Quiz App 📝

A dynamic quiz application built with Django.  
The app allows creating questions with multiple options and evaluates user submissions, showing the number of correct and wrong answers.

---

## Features

- Dynamic number of options per question.
- Admin interface for adding questions and options.
- Inline option creation in Django admin.
- Calculates correct and wrong answers automatically.
- Simple and user-friendly interface.

---

## Requirements

- Python 3.x
- Django 4.x (or compatible)
- SQLite (default) or any other database configured in `settings.py`

## Setup & How to Run
1.Clone the repository
``` bash
    git clone https://github.com/Vishwa-Bhalodiya/Python-Task5-VishwaBhalodiya.git
    cd quiz_project
```
2.Install Dependencies
```bash
    pip install django
```
3.Apply migrations
```bash
  python manage.py makemigrations
  python manage.py migrate
```
4.Create a superuser (admin)
```bash
python manage.py createsuperuser
```
- Follow the prompts to create the admin user (username, email, password).

5.Run the development server
```bash
python manage.py runserver
```

## Access the application

- Open your browser at http://127.0.0.1:8000/ to take the quiz.
- Access the admin panel at http://127.0.0.1:8000/admin/ to add questions and options.
