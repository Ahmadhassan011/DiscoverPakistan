# Pakistan Tourism Management System (PKTM)

A comprehensive web application for managing and exploring tourist destinations, hotels, restaurants, bookings, and reviews across Pakistan. Built with Flask, SQLAlchemy, and MySQL.

## Features
- User and admin authentication
- Browse and search tourist destinations, hotels, and restaurants
- Book hotels and make restaurant reservations
- Leave reviews for destinations, hotels, and restaurants
- Admin dashboard for managing content
- User dashboard for managing bookings, favorites, and reservations

## Project Structure
- `app.py` / `main.py`: Application entry points
- `models.py`: SQLAlchemy ORM models
- `forms.py`: WTForms for user input
- `routes.py` / `views.py`: Application routes and views
- `populate_database.py`: Script to populate the database with sample data
- `attached_assets/ddl.sql`: MySQL DDL for schema setup
- `attached_assets/dml.sql`: Sample data for manual SQL import
- `templates/`: Jinja2 HTML templates
- `static/`: CSS and JS assets

## Requirements
- Python 3.13+
- MySQL Server
- Flask 3.1.1+
- Other dependencies (see `pyproject.toml`)

## Setup Instructions

1. **Clone the repository**

2. **Install Python dependencies**
```powershell
pip install .
```

4. **Configure environment variables**
- By default, the app connects to MySQL at `mysql+pymysql://root:password@localhost/DataBaseName`.
- To change, set the `DATABASE_URL` environment variable.

5. **Populate the database with sample data (Flask models)**
```powershell
python populate_database.py
```

6. **Run the application**
```powershell
python main.py
```
- The app will be available at http://127.0.0.1:5000/

## Demo Login Credentials
- **Admin:** ali.raza@tourism.pk / admin123
- **User:** ahmed.k@example.com / user123


© 2025 Pakistan Tourism Management System