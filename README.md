# To-Do List Application

![toDoList](https://github.com/user-attachments/assets/cb716955-58dc-4476-8a89-839360765b10)


This project is a To-Do List application built with React using a styled-component approach and atomic design principles. The application features CRUD operations with a backend server to store and manage tasks. 

## Features

- Add, update, and delete tasks
- Display tasks based on their status: To Do, In Progress, and Done
- Styled components for consistent UI
- Atomic design architecture for reusable components
- HTTP requests for CRUD operations

## Technologies Used

- React
- Styled Components
- Atomic Design
- Fetch API for HTTP requests
- CSS Modules for component-level styling

## Installation

1. Clone the repository
2. Change to the project directory:

    ```bash
    cd to-do-list-app
    ```
3. Install the dependencies:

    ```bash
    npm install
    ```
4. Install the json-server:

    ```bash
    npm install -g json-server
    ```
5. Go to database file:

    ```bash
    cd src
    cd database
    ```

6. Start the json-server:

    ```bash
    npx json-server db.json
    ```

7. Run the application:

    ```bash
    npm run dev
    ```

## Project Structure

The project follows an atomic design methodology, dividing components into Atoms, Molecules, and Organisms.

src
├── components
│ ├── atoms
│ │ ├── button
│ │ │ ├── Button.jsx
│ │ │ └── Button.module.css
│ │ ├── input
│ │ │ ├── Input.jsx
│ │ │ └── Input.module.css
│ ├── molecules
│ │ ├── formGroup
│ │ │ ├── FormGroup.jsx
│ ├── organisms
│ │ ├── toDoCard
│ │ │ ├── ToDoCard.jsx
│ │ │ └── ToDoCard.module.css
│ │ ├── toDoForm
│ │ │ ├── ToDoForm.jsx
│ │ │ └── ToDoForm.module.css
├── database
│ ├── db.json
├── service
│ ├── Api.js
├── App.jsx
├── App.module.css
└── main.jsx
