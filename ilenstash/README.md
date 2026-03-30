# Ilenstash Appointment Scheduling System
This is a Django project for an appointment scheduling system.

## Project Structure 
- **ilenstash/**
  - **appointments/**
    - **migrations/** 
    - **templates/** 
    - **static/** 
    - **views.py**  
    - **models.py**  
    - **serializers.py**
    - **urls.py**
    - **admin.py**
  - **ilenstash/**
    - **settings.py**
    - **urls.py**
    - **wsgi.py**
  - **manage.py**

## Requirements
- Django
- djangorestframework

## Setup Instructions
1. Create a virtual environment: `python -m venv venv`
2. Activate the virtual environment: `venv\Scripts\activate`
3. Install required packages: `pip install django djangorestframework`
4. Run migrations: `python manage.py migrate`
5. Start the server: `python manage.py runserver`
