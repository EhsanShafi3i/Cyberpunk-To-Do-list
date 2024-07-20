# Cyberpunck To do list

A simple "Todo List" project built with Django. This project includes features such as user registration, login, logout, viewing, creating, editing, and deleting tasks.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation and Setup](#installation-and-setup)
- [Usage](#usage)
- [Development Notes](#development-notes)
- [License](#license)

## Introduction
This project is a simple "Todo List" application built with Django. Users can sign up, log in, create new tasks, view existing tasks, edit them, and delete them. It is suitable for learning the basics of Django and working with authentication systems and CRUD (Create, Read, Update, Delete) operations.

## Features

- **Registration and Login**: Users can create a new account and log in.
- **Task Management**: Users can add new tasks, view existing tasks, edit them, and delete them.
- **Search**: Users can search tasks by title.
- **UI/UX**: Simple and attractive user interface with CSS and JavaScript for enhanced user experience.

## Installation and Setup

### Prerequisites

- Python 3.x
- Django 5.x

### Installation Steps

1.**Clone the Repository**

```bash
git clone (https://github.com/EhsanShafi3i/Cyberpunk-To-Do-list.git)
cd Cyberpunk-To-Do-list/
```

2.**Create and Activate Virtual Environment**

```bash
python -m venv venv
source venv/bin/activate   # For Windows: venv\\Scripts\\activate
```

3.**Apply Migrations(Optional)**

 ```bash
python manage.py migrate
```

4.**Create Admin User (Optional)**

```bash
python manage.py createsuperuser
```

5.**Run the Local Server**
```bash
python manage.py runserver
```

6.**Access the Application**

Visit `http://127.0.0.1:8000/` to access the application.

## Usage

- **Home Page**: After logging in, the home page displays the list of tasks. Users can add new tasks and view existing tasks.
- **Task Create Page**: To add a new task.
- **Task Update Page**: To edit an existing task.
- **Task Delete Page**: To delete a task.
- **Login Page**: To log into your account.
- **Register Page**: To create a new user account.

## Development Notes

- **Settings**: The Django settings are in `settings.py`, where you can configure environment variables and database settings.
- **Templates**: HTML templates are located in the `templates` directory and can be modified as needed.
- **Models**: Models are defined in `models.py` and you can add new models or modify existing ones.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

---

For more information or issues, please refer to the [Issues](https://github.com/EhsanShafi3i/Cyberpunk-To-Do-list/issues).
