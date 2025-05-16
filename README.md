# ALX Travel App 🌍

The **ALX Travel App** is a real-world Django-based backend for a travel listing platform. This project is designed as part of the ALX Software Engineering program to demonstrate scalable backend setup using industry-standard practices including REST APIs, Swagger documentation, MySQL configuration, and secure environment management.

## 🚀 Features

- Django REST API backend
- Swagger (drf-yasg) auto-generated API docs
- MySQL database integration
- Environment-based configuration using `django-environ`
- CORS configuration for frontend API consumption
- Ready for future task queue setup using Celery and RabbitMQ

---

## 📦 Tech Stack

- Python 3.x
- Django 4.x
- Django REST Framework
- MySQL
- drf-yasg (Swagger)
- django-environ
- django-cors-headers
- Celery (prepared for future use)
- RabbitMQ (prepared for future use)

---

## 🛠️ Setup Instructions

### 1. Clone the Repository

git clone https://github.com/your-username/alx_travel_app.git
cd alx_travel_app

# Create and Activate a Virtual Environmen
python3 -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

# Install Dependencies
pip install -r requirements.txt

# Set Up Environment Variables
Create a .env file in the root directory with the following format:

DEBUG=True
SECRET_KEY=your-secret-key
DB_NAME=your_db_name
DB_USER=your_db_user
DB_PASSWORD=your_db_password
DB_HOST=localhost
DB_PORT=3306

# Apply Migration
python manage.py migrate

# Run server
python manage.py runserver

# 📁 Project Structure

alx_travel_app/
├── alx_travel_app/
│   ├── settings.py
│   ├── urls.py
├── listings/
│   ├── models.py
│   ├── views.py
├── requirements.txt
├── .env
├── manage.py
└── README.md

# 🧪 API Documentation

Swagger UI is available at:

/swagger/
