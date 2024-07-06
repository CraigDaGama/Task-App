
# Task Management System in C

This program is a simple command-line task management system implemented in C. It allows users to add, view, delete, and mark tasks as completed, with tasks stored persistently in a text file (`tasks.txt`).

## Features

- Add new tasks with a description.
- View existing tasks.
- Mark tasks as completed or uncompleted.
- Delete tasks.
- Persist tasks in a text file (`tasks.txt`).

## Getting Started

### Prerequisites

- A C compiler (e.g., GCC).
- A terminal or command prompt.

### Installation

Clone the repository:

```bash
git clone https://github.com/CraigDaGama/Task-Manager.git
cd Task-Manager
```

### Compilation

To compile the program, use the following command:

```bash
gcc -o task_manager task_manager.c
```

### Running the Program

Run the compiled executable:

```bash
./task_manager
```

## Usage

Upon running the program, you will be presented with a menu:

- **Add Task**: Prompts you to enter a task description.
- **View Tasks**: Displays all tasks and allows you to mark tasks as completed/uncompleted.
- **Delete Task**: Allows you to delete a task by its number.
- **Quit**: Exits the program.


## Example Usage

1. **Adding a Task**:
    Enter task 

2. **Viewing Tasks**:
    Press 'enter' to mark task as completed
    Press 's' to save
    Press 'Esc' to go back to the main menu.
   

3. **Deleting a Task**:
    Select a task to delete
    Press 'Esc' to go back to the main menu.

## License

This project is licensed under the MIT License.
