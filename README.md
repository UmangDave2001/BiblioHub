# Book Media Platform

A Django REST Framework application for managing books, audiobooks, podcasts, and social interactions.

## Features
- User Management
- Books and Audiobooks Library
- Podcast Management
- Reading/Listening Progress Tracking
- Social Features
- Discussion Forums

## Tech Stack
- Python 3.x
- Django 4.2+
- Django REST Framework
- PostgreSQL (configurable)
- Swagger/OpenAPI Documentation

## Local Development Setup
```bash
# Create and activate virtual environment
python -m venv .venv
source .venv/bin/activate  # Linux/Mac
# or
.\.venv\Scripts\Activate.ps1  # Windows PowerShell

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Create superuser
python manage.py createsuperuser

# Run development server
python manage.py runserver
```

## API Documentation
- Swagger UI: `/swagger/`
- ReDoc: `/redoc/`