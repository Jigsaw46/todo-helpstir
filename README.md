# Todo List Application

## Overview

This project is a frontend Todo List application built using React. The application allows users to create, update, mark tasks as done, search for tasks, and view tasks in an expandable list format.

## System Design

The system is designed with the following components:

1. **TaskForm**: A component to add new tasks.
2. **TaskList**: A component to display the list of tasks.
3. **TaskItem**: A component to display individual tasks with options to edit, toggle completion, and expand for more details.

The data is managed using a dummy JSON file as a data repository, which is loaded into the application state on initialization.

## Implementation

### Core Features

1. **Create Task**: Users can add new tasks using the TaskForm component.
2. **Update Task**: Users can edit existing tasks by clicking the edit button on each task item.
3. **Mark as Done**: Users can mark tasks as completed by checking the checkbox next to each task.
4. **Search Tasks**: Users can search for tasks using the search input at the top of the application.
5. **Expandable List**: Tasks can be expanded to show a description and the timestamp of the last update.

### Data Storage

The tasks are stored in a `data.json` file and loaded into the application state. Any changes to tasks (add, update, complete) are reflected in the application's state.

## Setup and Run

### Prerequisites

- Node.js
- npm (Node Package Manager)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/todo-list.git
   cd todo-list
