# Job Portal (Django)

A job portal web application built with Django where employers can post jobs and candidates can search and apply, including resume upload.

## Features

- User registration and login
- Employers can post and manage job listings
- Candidates can browse jobs and apply
- Resume upload (PDF) while applying
- Clean, responsive pages built with HTML, CSS and JavaScript

## Tech Stack

- *Backend:* Python, Django
- *Frontend:* HTML, CSS, JavaScript
- *Database:* SQLite (default)

## Getting Started

### 1. Clone the repository

bash
git clone https://github.com/ankushkaushal0805-design/job-portal-jango.git
cd job-portal-jango


### 2. Create and activate a virtual environment

bash
python -m venv venv
venv\Scripts\activate


On macOS/Linux use source venv/bin/activate.

### 3. Install dependencies

bash
pip install django pillow


If a requirements.txt file is present, use pip install -r requirements.txt instead.

### 4. Set up the database

bash
python manage.py migrate
python manage.py createsuperuser


### 5. Run the server

bash
python manage.py runserver


Open http://127.0.0.1:8000/ in your browser.

## Notes

- The media/ folder (uploaded resumes) and db.sqlite3 are not included in this repository for privacy reasons. They are created automatically when you run the project.

## Author

*Ankush Kaushal*
B.Tech CSE Graduate | Aspiring Software Developer
GitHub: [ankushkaushal0805-design](https://github.com/ankushkaushal0805-design)
