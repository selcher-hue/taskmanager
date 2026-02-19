
# Task Manager

## What is this project?
Task Manager is a command-line Python application written in Python.
It allows users to manage study or homework tasks using a simple menu interface.
Tasks are stored in a JSON file (tasks.json) so they remain saved after the program exits.

The program supports:
- Adding new tasks
- Viewing all tasks
- Marking tasks as completed
- Saving tasks before exiting

## How to run the project
1. Make sure Python 3.6 or higher is installed.
2. Open a terminal (Command Prompt / PowerShell).
3. Navigate to the folder that contains tasks.py.
4. Run the following command:

   python tasks.py

## Example usage

When the program starts, you will see:

1. Add Task
2. View Tasks
3. Mark Task as Done
4. Exit

Example:

Choose an option: 1
Enter task: Study Math
Task added.

Choose an option: 2
1. [ ] Study Math

Choose an option: 3
Enter task number to mark as done: 1
Task marked as done.

Choose an option: 2
1. [Done] Study Math

Choose an option: 4
(Program exits)

## Files included
- tasks.py : Main Python application file
- tasks.json : Stores tasks data in JSON format
- README.md : Project documentation

## Requirements
- Python 3.6 or higher
"""
with open("README.md", "w") as file:
    file.write(readme_text)

print("README.md created successfully.")
