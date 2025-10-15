# Project: Code assist demo

## Project Overview
This project is a simple Flask web application that interacts with a PostgreSQL database to manage user data.

## Architecture
- **Backend:** Python Flask API
- **Database:** PostgreSQL
- **Frontend:** HTML, CSS, JavaScript (served by Flask)

## Key Files and Directories
- `main.py`: Main Flask application file.
- `models.py`: Defines SQLAlchemy models for database interaction.
- `templates/`: Contains Jinja2 templates for the frontend.
- `static/`: Contains static assets like CSS and JavaScript.

## Setup and Running
1. Create a virtual environment: `python -m venv venv`
2. Activate the virtual environment: `source venv/bin/activate`
3. Install dependencies: `pip install -r requirements.txt`
4. Run the application: `python app.py`

## Project-Specific Conventions
- All database interactions should be handled through SQLAlchemy ORM.
- Use f-strings for string formatting.
