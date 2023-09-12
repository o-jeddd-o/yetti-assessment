# Yetti Technologies Backend Assessment

This repository contains the Django project developed as part of the Backend Developer Intern Assessment for Yetti Technologies.

## Prerequisites

- Python (3.7 or higher recommended)
- `pip` for package management
- `virtualenv` (optional, but recommended)

## Setup

1. **Clone the Repository**:
```bash
git clone https://github.com/o-jeddd-o/yetti-assessment.git
cd yetti-assessment
```
### Setup a virtual environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```
### Install required packages
```bash
pip install -r requirements.txt
```
### Run Migrations
```bash
python manage.py migrate
```
## Running the project
To run the project:
```bash
python manage.py runserver
```
Visit http://127.0.0.1:8000/ in your browser.

## Running Tests
To run any tests,
```bash
python manage.py test users
```
## Features
* User registration using email and password.
* User login/logout functionality.
* Authenticated access to a "Hello World" page.
* Comprehensive unit tests to ensure functionality and security.

## Notes And Further Explanations
* This project uses Django's built-in user authentication system.
* CSRF protection is enabled by default in Django, ensuring the application's forms are secure against CSRF attacks.
* Session fixation protection is also a built-in feature of Django, automatically renewing session IDs during login.

For any further information or clarifications, feel free to reach out. 
