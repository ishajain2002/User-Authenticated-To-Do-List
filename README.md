# User Authenticated To-do List

## Overview

This project implements a User Authenticated To-do List using Django's built-in authentication system. It prioritizes data privacy and personalized task management features, allowing users to securely manage their tasks with authentication capabilities.

## Features

- User Authentication: Utilizes Django's built-in authentication system to allow users to sign up, log in, and securely manage their tasks.
- Task Management: Enables users to create, update, delete, and mark tasks as completed.
- Personalization: Provides personalized task management features tailored to individual user accounts.
- Data Privacy: Ensures data privacy and security through authentication mechanisms and access control.

## How to Use

### Prerequisites

Make sure you have Python and Django installed on your machine.

### Clone the Repository

```bash
git clone <repository-url>
cd user-authenticated-todo-list
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Start the Development Server 

```bash
python manage.py runserver
```
This will start the development server on http://localhost:8000.

## Access the application 
Open your web browser and navigate to http://localhost:8000 to access the application.

## How it Works 
1.User Authentication: Utilizes Django's authentication system to handle user registration, login, and logout functionalities. <br>
2.Task Management: Implements CRUD (Create, Read, Update, Delete) operations for managing tasks associated with authenticated users. <br>
3.Personalization: Provides personalized task lists and views based on user accounts, ensuring each user has their own set of tasks. <br>
4.Data Privacy: Ensures data privacy and security by restricting access to tasks based on user authentication and authorization. <br>

### License
This project is licensed under the MIT License - see the LICENSE file for details.
