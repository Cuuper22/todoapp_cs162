# Hierarchical KanBan Board

## Introduction
The Hierarchical KanBan Board is a web application developed using Flask, which allows users to manage tasks in a hierarchical manner. It provides features for user registration, login, and task management. Users can create, update, and delete tasks, and organize them into different status categories. Tasks can also have parent-child relationships, creating a hierarchy for better organization.

## Installation
1. Clone the repository to your local machine:
   
   ```git clone https://github.com/Cuuper22/todoapp_cs162```
   
3. Change into the project directory:
   
   ```cd Hierarchical Kanban Board```
   
5. Create a virtual environment:
   
   ```python -m venv venv```
   
7. Activate the virtual environment:
   
   ```source venv/bin/activate```
   
9. Install the required packages:
    
   ```pip install -r requirements.txt```
   
11. Run the app:
    
    ```python3 main.py```

## Usage
- **Registration:** Users can create an account by providing a username and password.
- **Login:** Registered users can log in using their credentials.
- **Task Management:** Once logged in, users can:
  - Create new tasks, specifying a title and status (e.g., "todo," "doing," "done").
  - Organize tasks into a hierarchy by associating a task as a child of another task.
  - Update the title, status, and parent task of existing tasks.
  - Delete tasks and their children recursively.

## Features
- User registration and authentication.
- Create, update, and delete tasks.
- Organize tasks into a hierarchy with parent-child relationships.
- Task statuses (e.g., "todo," "doing," "done").

## Contributing
If you'd like to contribute to this project, please follow these steps:
1. Fork the project on GitHub.
2. Create a new branch with a descriptive name for your feature or bug fix.
3. Make your changes and commit them.
4. Push your branch to your fork.
5. Create a pull request from your fork to the original repository.

Thank you for your contributions!

Feel free to contact the project maintainer for any questions or issues.

**Maintainer:** [Fady Hanna](https://github.com/fadyFH194)

**Project Repository:** [Repo](https://github.com/fadyFH19/Hierarchical-Kanban-Board)
