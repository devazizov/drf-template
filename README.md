# Django REST Framework Template

This is a basic template for a Django REST Framework (DRF) project. It provides a structured foundation for building RESTful APIs using Django.

## Features
- Django & Django REST Framework setup
- Modular project structure
- Ready-to-use API app
- Basic configuration and settings

## Project Structure
```
├── api
│   ├── admin.py           # Admin panel configurations
│   ├── apps.py            # Application configuration
│   ├── __init__.py        # Package initialization
│   ├── migrations         # Database migrations
│   │   └── __init__.py    # Migrations initialization
│   ├── models.py          # Database models
│   ├── serializers.py     # DRF serializers
│   ├── tests.py           # Unit tests
│   ├── urls.py            # API URLs
│   └── views.py           # API views
├── config
│   ├── asgi.py            # ASGI configuration
│   ├── __init__.py        # Package initialization
│   ├── settings.py        # Project settings
│   ├── urls.py            # Root URL configuration
│   └── wsgi.py            # WSGI configuration
├── manage.py              # Django management script
├── README.md              # Project documentation
└── requirements.txt       # Project dependencies
```

## Installation

### Prerequisites
- Python 3.8+
- pip
- Virtual environment (recommended)

### Setup
1. **Clone the repository**
   ```sh
   git clone https://github.com/devazizov/drf-template.git
   cd your-repo
   ```

2. **Create and activate a virtual environment**
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install dependencies**
   ```sh
   pip install -r requirements.txt
   ```

4. **Run migrations**
   ```sh
   python manage.py migrate
   ```

5. **Start the development server**
   ```sh
   python manage.py runserver
   ```

## API Endpoints
You can define API endpoints in `api/urls.py` and implement them in `api/views.py`.

## Running Tests
To run the tests, use:
```sh
python manage.py test
```

---

This template is a great starting point for developing Django-based RESTful APIs. Customize it according to your needs!
