# 📝 My First Django Blog

This is a simple blog project built with Django. It allows users to create and manage blog posts via the Django admin panel.

## 🚀 Features

- Create, edit, and delete blog posts
- Admin dashboard with login
- Fields: title, content, author

## 🛠️ How to Run

```bash
# Create virtual environment
python -m venv venv
venv\Scripts\activate  # For Windows

# Install dependencies
pip install django

# Run migrations
python manage.py migrate

# Create superuser
python manage.py createsuperuser

# Start server
python manage.py runserver
