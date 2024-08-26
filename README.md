# Personal Tasks Management System

This project is a task management system that allows users to create, update, delete, and view tasks. The system is built with Django for the backend and Angular for the frontend.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Setup Backend (Django)](#setup-backend-django)
- [Setup Frontend (Angular)](#setup-frontend-angular)
- [Running the Application](#running-the-application)
- [Interacting Between Backend and Frontend](#interacting-between-backend-and-frontend)

# Prerequisites

Before you begin, ensure you have the following installed on your system:

Python 3.x: You can download it from python.org.
Git: You can download it from git-scm.com.
pip: This comes with Python, but you can update it by running python -m ensurepip --upgrade.
Setup Instructions
Follow these steps to set up and run the project on your local machine.

## 1. Clone the Repository

First, clone the repository from GitHub. Open your terminal or command prompt and run:

git clone https://github.com/Alemba-Vivian/Personal-Task-backend.git  
     or
git clone git@github.com:Alemba-Vivian/Personal-Task-backend.git


## 2. Navigate to the Project Directory

Move into the project directory using

cd Personal-Task-backend

## 3. Create a Virtual Environment
A virtual environment helps to keep your project dependencies isolated. Create a virtual environment by running:
python -m venv venv

## 4. Activate the Virtual Environment
Activate the virtual environment:

Windows:
venv\Scripts\activate

macOS/Linux:
source venv/bin/activate

You'll notice that your terminal prompt changes to indicate that you're now working within the virtual environment.

## 5. Install the Required Packages
Install all the required Python packages by running:
pip install -r requirements.txt


## 6. Set Up the Database
Apply the database migrations to set up the SQLite database:
python manage.py migrate


## 7. Run the Development Server
Start the development server to see your app in action:
python manage.py runserver

After running this command, you should see output similar to this:
Starting development server at http://127.0.0.1:8000/
Open your web browser and go to http://127.0.0.1:8000/ to view the application.

## 8. Accessing the Admin Panel
Django has a built-in admin panel where you can manage your tasks. To access it:
Create a superuser (admin) by running:

python manage.py createsuperuser
Follow the prompts to create your admin account.

Once created, visit http://127.0.0.1:8000/admin and log in with the credentials you just created.
You will be able to see the tasks added by the user.
