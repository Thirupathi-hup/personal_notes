# Task Tracker

A simple React application to manage daily tasks with basic CRUD functionality. This app allows you to add, edit, delete, and view tasks with the ability to persist tasks using **localStorage**. The app is responsive and optimized for both small and large screen sizes.

## Features
- **Add Task**: A form to add a task with Title, Description, Due Date, and Status (Pending, In Progress, Completed).
- **View Tasks**: Displays a list of tasks in a table.
- **Edit Task**: Allows inline editing of tasks.
- **Delete Task**: Deletes tasks with a confirmation prompt.
- **Data Persistence**: All tasks are saved to and loaded from the browser's `localStorage`, so tasks persist even after the page refreshes.
- **Responsive UI**: The app adjusts to different screen sizes using Bootstrap classes.

## Technologies Used
- **React**: The app is built using React, a popular JavaScript library for building user interfaces.
- **Bootstrap**: Used for styling and making the app responsive.
- **localStorage**: For storing tasks persistently in the browser.

## Installation
1. Clone the repository:  
   `git clone https://github.com/Thirupathi-hup/Task_tracker.git`
2. Navigate to the project directory:  
   `cd task-tracker`
3. Install the dependencies:  
   `npm install`
4. Run the development server:  
   `npm start`  
   This will open the app in your default web browser at `http://localhost:3000`.

## Usage
1. **Add a task**: Click the "Add Task" button and fill out the form with the task title, description, due date, and status.
2. **View tasks**: The tasks you add will be displayed in a table.
3. **Edit a task**: Click the "Edit" button next to a task to modify its details.
4. **Delete a task**: Click the "Delete" button to remove a task.

## Folder Structure
ask-tracker/ ├── src/ │ ├── components/ │ │ ├── TaskForm.js # Form to add/edit tasks │ │ └── TaskList.js # List of tasks │ ├── App.js # Main application component │ ├── index.js # Entry point for React app │ └── index.css # Global CSS styles ├── public/ │ ├── index.html # HTML template ├── package.json # Project dependencies and scripts └── README.md # Project documentation


## Contribution
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Create a new pull request.
