Task Manager

A simple Task Management application built using Django.

--> Features
Add tasks
Edit tasks
Delete tasks
Restore deleted tasks
Set task priority
Set due dates
Manage task status

--> Technologies Used
Python
Django
SQLite

--> Project Structure
task_manager/
│
├── task_manager/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── task/
│   ├── models.py
│   ├── views.py
│   ├── forms.py
│   ├── urls.py
│   └── admin.py
│
├── templates/
│   ├── dashboard.html
│   ├── task_form.html
│   └── trash.html
│
├── db.sqlite3
├── manage.py
├── requirements.txt
└── README.md

--> Run the Project

Install dependencies:
pip install -r requirements.txt

Run migrations:
python manage.py migrate

Start the server:
python manage.py runserver

