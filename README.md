Django To-Do Web Application

Overview
This is a simple To-Do web application built using Python and the Django framework. It allows users to create, read, update, and delete tasks. The application follows the tutorial from GeeksforGeeks.

Features
  Add new tasks with a title and description.
  View a list of all tasks.
  Udate existing tasks.
  Delete tasks.
  Simple and intuitive user interface.

Prerequisites
To run this project, you need to have the following installed:
  Python 3.6 or higher
  Django 3.2 or higher
  pip (Python package manager)

Installation

Clone the repository:
  https://github.com/Mirsulton1/To-Do-App.git
  cd django-todo-webapp

Create a virtual environment (optional but recommended):
  python -m venv venv
  source venv/bin/activate  # On Windows: venv\Scripts\activate

Install dependencies:

  pip install django

Apply migrations:

  python manage.py makemigrations
  python manage.py migrate
  Run the development server:
  python manage.py runserver

Access the application: Open your browser and navigate to http://127.0.0.1:8000/.

Project Structure

django-todo-webapp/
│
├── todo/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── views.py
│   └── wsgi.py
├── todoapp/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── migrations/
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   ├── views.py
│   └── templates/
│       └── todoapp/
│           ├── home.html
│           ├── update_task.html
│           └── ...
├── manage.py
├── requirements.txt
└── README.md

Usage
  Home Page: View all tasks and add new ones.
  Add Task: Enter a task title and description, then submit to add it to the list.
  Update Task: Click the "Edit" button next to a task to modify its details.
  Delete Task: Click the "Delete" button to remove a task.

Contributing

Contributions are welcome! Please follow these steps:

Fork the repository.
  Create a new branch (git checkout -b feature-branch).
  Make your changes and commit them (git commit -m 'Add some feature').
  Push to the branch (git push origin feature-branch).
  Create a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
  This project is based on the GeeksforGeeks Django To-Do Web App Tutorial.
  Thanks to the Django community for their excellent documentation and resources.
