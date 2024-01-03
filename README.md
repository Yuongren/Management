# Management
This project will be a simple task management system where users can create tasks, assign them to projects, and mark them as completed.

## Project Outline:

### 1.CLI Application:

Create a CLI application using Python.
Use a library like click for building the command-line interface.
Include commands for adding tasks, listing tasks, marking tasks as completed, and managing projects.

### 2.Database and SQLAlchemy ORM:

Set up a SQLite database using SQLAlchemy ORM.
Define three related tables: Task, Project, and User.
Tasks should have foreign key relationships with both Project and User.

### 3.Package Structure:

Maintain a well-organized package structure for your application.
For example:

project/
├── app/
│   ├── __init__.py
│   ├── models/
│   │   ├── __init__.py
│   │   ├── task.py
│   │   ├── project.py
│   │   └── user.py
│   ├── commands/
│   │   ├── __init__.py
│   │   ├── add.py
│   │   ├── list.py
│   │   ├── complete.py
│   │   └── manage.py
│   ├── utils.py
│   └── main.py
├── Pipfile
├── .gitignore
└── README.md

### 4.Virtual Environment:

Use Pipenv for managing the virtual environment.
Maintain a Pipfile with the required dependencies.
Ensure that the virtual environment is well-isolated and only includes the necessary packages.

### 5.Data Structures and Algorithms:

Implement a sorting algorithm (e.g., quicksort or mergesort) to sort tasks by priority or due date.
Use this algorithm to display a sorted list of tasks when listing them in the CLI.

### 6.Lists, Dicts, and Tuples:

Utilize lists to store collections of tasks and projects.
Use dicts for representing task attributes like title, description, and status.
Tuples can be used for fixed-size data, perhaps to represent the priority and due date of a task.

### 7.Object-Oriented Programming:

Implement classes for Task, Project, and User.
Leverage the principles of object-oriented programming, including encapsulation and abstraction.

### 8.Object Inheritance:

Consider using inheritance if there are common attributes or methods shared between different types of tasks or projects.

### 9.Configuring Applications:

Use a configuration file or environment variables to store configurations like database connection details.

### 10.SQL Fundamentals and Table Relations:

Ensure proper use of SQL fundamentals in SQLAlchemy queries.
Establish relationships between tables based on foreign keys.

### 11.Object-Relational Mapping with SQLAlchemy:

Leverage SQLAlchemy for interacting with the database.
Create, read, update, and delete records using SQLAlchemy ORM.

### 12.Building CLIs:

Implement a command-line interface that allows users to interact with the application easily.
Provide clear and helpful messages to guide users through different commands.
Remember to handle errors gracefully, validate user input, and provide clear and helpful error messages. Following best practices for coding standards, documentation, and testing will contribute to a well-rounded and maintainable project.
