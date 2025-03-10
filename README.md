
# TodoAPI & Todo-React

## Project Overview

### TodoAPI
The backend of the Todo application, built using [Backend Technology]. It handles the creation of the SQL database, API endpoints, and interactions with the database.

### todo-react
The frontend of the Todo application, built using React and TypeScript. It provides a user-friendly interface where users can manage tasks. The page is divided into two sections:
- **Left Sidebar**: Displays the name of the application and a form to add new tasks, with a button to submit them.
- **Right Section**: Displays the tasks with color-coded statuses:
  - **Red**: Not completed
  - **Orange**: In progress
  - **Green**: Completed

At the top of the page, three circles show the count of tasks in each status category (completed, in progress, not completed).

---

## Getting Started

### Prerequisites

- Node.js
- npm or yarn
- [Database Server and Setup Instructions]

### Installation

#### Backend (TodoAPI)
1. Clone the repository:
   ```bash
   git clone [repo-link]
   cd TodoAPI
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up the database by running the necessary SQL commands.
4. Start the backend:
   ```bash
   npm start
   ```

#### Frontend (todo-react)
1. Clone the repository:
   ```bash
   git clone [repo-link]
   cd todo-react
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the frontend:
   ```bash
   npm start
   ```

---

## Features

- **Add a task**: Use the form in the left sidebar to add a new task.
- **Task statuses**: Tasks are color-coded for easy tracking:
  - Red for "Not Completed"
  - Orange for "In Progress"
  - Green for "Completed"
- **Task count**: The top of the screen shows three circles representing the count of tasks in each category (completed, in progress, not completed).

---

## API Endpoints (TodoAPI)

- **GET /tasks**: Retrieves all tasks from the database.
- **POST /tasks**: Creates a new task.
- **PUT /tasks/:id**: Updates an existing task.
- **DELETE /tasks/:id**: Deletes a task.

---

## License

This project is licensed under the **Private Use Only** license.
