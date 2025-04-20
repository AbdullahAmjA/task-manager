Task Management Application
A Django-based web application for managing tasks with user authentication and category-based organization.
Features

User Authentication: Register, login, and logout functionality.
Task Management: Create, read, update, and delete (CRUD) tasks.
Categories: Organize tasks into user-specific categories (e.g., Work, Personal).
Responsive UI: Styled with Tailwind CSS for a clean, modern interface.
Form Styling: Enhanced form fields using django-widget-tweaks for better usability.
SQLite Database: Lightweight database for task and user data.

Technologies

Backend: Django 4.2, Python 3.11
Frontend: Tailwind CSS, JavaScript
Database: SQLite
Dependencies: django-widget-tweaks

Setup Instructions

Clone the Repository:
git clone https://github.com/AbdullahAmjA/task-manager.git
cd task-manager


Create Virtual Environment:
python -m venv venv


Activate Virtual Environment:

Windows:
venv\Scripts\activate


macOS/Linux:
source venv/bin/activate




Install Dependencies:
pip install -r requirements.txt


Apply Migrations:
python manage.py migrate


Run the Server:
python manage.py runserver


Access the App:

Open http://127.0.0.1:8000/ in a browser.



Live Demo
Link to deployed app, e.g., on Render (Update after deployment)
Project Structure

tasks/: App containing models, views, templates, and static files.
task_manager/: Project settings, URLs, and WSGI configuration.
templates/tasks/: HTML templates for login, register, task list, and forms.
static/js/: JavaScript for client-side functionality.

Screenshots
(Optional: Add screenshots of the app, e.g., task list, form)
Future Enhancements

Add task search and filter functionality.
Implement form validation error messages.
Support task due dates and reminders.

License
MIT License
