# Simple Task Manager using Flask

This is a basic task manager web application built using Flask, a Python web framework. It allows users to add, edit, mark tasks as done, and delete tasks from a list.

## Prerequisites
- Python 3.x
- Flask (pip install flask)
  
## Installation and Setup
1. Clone the repository or download the source code.
2. Navigate to the project directory.
3. Install Flask if you haven't already:
`pip install flask`

## Run the Flask application:
Access the application in your browser at http://localhost:5000.

## Usage
- Add a Task: Visit /add and submit a task using the provided form.
- Edit a Task: Click on the task you want to edit and modify its content on the edit page.
- Mark Task as Done: Click on the checkbox beside each task to mark it as done.
- Delete a Task: Click on the delete button to remove a task from the list.

## Code Structure
- app.py: Contains the Flask application code.
- templates/: Folder containing HTML templates for the application.

## Routes
- /: Displays the list of tasks.
- /add: Adds a new task to the list.
- /edit/<int:index>: Edits an existing task by its index in the list.
- /check/<int:index>: Marks a task as done or undone.
- /delete/<int:index>: Deletes a task from the list.

## Notes
- Tasks are stored in memory and will be reset upon restarting the application.

## Screenshots
<img width="821" alt="Screenshot 2024-01-03 173513" src="https://github.com/Aravin-S/Task-Manager/assets/73080952/733f3d2e-618f-4e16-920b-526f79ffe30e">

