# Simple Task Manager (CLI)

## Overview

This project is a simple task manager implemented in Golang, designed to run on the command line interface (CLI). It allows users to manage their tasks efficiently through simple and intuitive commands.

## Features

- Add tasks with a description and due date.
- List all tasks.
- Mark tasks as completed.
- Remove tasks.
- View tasks based on their status (completed or pending).
- Command-line interface for easy interaction.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/simple-task-manager.git
  ```

``` $ task
task is a CLI for managing your TODOs.

Usage:
  task [command]

Available Commands:
  add         Add a new task to your TODO list
  do          Mark a task on your TODO list as complete
  list        List all of your incomplete tasks

Use "task [command] --help" for more information about a command.

$ task add review talk proposal
Added "review talk proposal" to your task list.

$ task add clean dishes
Added "clean dishes" to your task list.

$ task list
You have the following tasks:
1. review talk proposal
2. some task description

$ task do 1
You have completed the "review talk proposal" task.

$ task list
You have the following tasks:
1. some task description ```