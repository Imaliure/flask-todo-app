
# Flask Todo App

This is a simple **Todo Application** built with **Flask**. The app allows users to add, update, and delete tasks. Data is stored in an SQLite database.

## Features

- Add new tasks
- Update existing tasks
- Delete tasks
- Tasks are stored in a database

## How to Use the App

You can access the live web app [here](https://flask-todo-app-3v07.onrender.com). The app is currently live, and you can perform the following actions:

1. **Add a new task**: Use the form on the main page to add new tasks.
2. **Update tasks**: Click on any task to be redirected to a page where you can edit the task.
3. **Delete tasks**: Click on the delete button next to any task to remove it from the list.

## Application Details

### Database

This app uses **SQLite** as its database, with data stored in the `test.db` file. The app connects to the database using **SQLAlchemy**.

### Pages

- **Home Page (`/`)**: Lists all tasks and allows you to add new tasks.
- **Task Update Page (`/update/<id>`)**: Allows you to update an existing task.
- **Task Deletion**: Each task has a delete button for removal.

## Installation

Follow these steps to run the Flask Todo app on your local machine:

### 1. Clone the Repository
```bash
git clone https://github.com/Imaliure/flask-todo-app.git
```

### 2. Create a Virtual Environment
```bash
cd flask-todo-app
python -m venv env
```

### 3. Activate the Virtual Environment
For Windows:
```bash
.\env\Scripts\activate
```
For MacOS/Linux:
```bash
source env/bin/activate
```

### 4. Install Required Libraries
```bash
pip install -r requirements.txt
```

### 5. Create the Database
```bash
python app.py
```
This command will create the `test.db` database file and start the application.

### 6. Run the Application
```bash
python app.py
```
You can access the app by navigating to **http://127.0.0.1:5000/** in your web browser.

## Technologies Used

- **Flask**: A lightweight web framework for Python.
- **SQLite**: Used as the database.
- **SQLAlchemy**: Object Relational Mapping (ORM) for Flask.
- **Gunicorn**: Used to run the application in a production environment (required for deployment on Render).

## Deployment

The app is deployed on **Render**. You can use the app [live here](https://flask-todo-app-3v07.onrender.com).

## Contributing

Feel free to fork the repository and create a **pull request** if you'd like to contribute to the project.

