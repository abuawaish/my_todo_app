# Todo App

A simple and intuitive Todo application built using **Flask** and **SQLite**, styled with **Bootstrap**, and featuring basic CRUD functionality.

## Features

- **Create**: Add new tasks to your Todo list.
- **Read**: View all tasks in a clean and organized layout.
- **Update**: Edit existing tasks with ease.
- **Delete**: Remove completed or unnecessary tasks.
- Flash messages provide feedback for actions like adding, updating, or deleting tasks.

## Project Structure

```plaintext
Todo_App/ 
├── app.py             # Main Flask application
├── requirements.txt   # Project dependencies
├── templates/         # HTML templates for the application
│   ├── layouts/
│   │   └── app.html   # Base layout for the app
│   └── index.html     # Main page for the Todo list
├── .gitignore         # Files and folders to ignore in version control
├── LICENSE            # License for the project
└── README.md          # Documentation for the app
```

## Templates Overview
- **layouts/app.html**: The base HTML layout containing reusable header, footer, and Bootstrap CDN.
- **index.html**: The main page extending the layout and displaying the Todo list.

## Installation
### 1.Clone the Repository
```bash
git clone https://github.com/abuawaish/my_todo_app.git
cd todo-app
```

### 2.Set Up a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate # On Windows, use venv\Scripts\activate
```

### 3.Install Dependencies
```bash
pip install -r requirements.txt
```

### 4.Run the Application
```bash
python app.py
```

## Dependencies

### The following Python libraries are required:
- **flask**: A lightweight WSGI web application framework.
- **Flask-SQLAlchemy**: An ORM for handling the SQLite database.

Dependencies are listed in the requirements.txt file. Install them with
```bash
pip install -r requirements.txt
```

## Usage
- Open the app in your browser.
- Add new tasks using the input field.
- View all tasks in a list format.
- Edit or delete tasks using the provided buttons.