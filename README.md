# Task Manager

Task Manager is a simple, full-stack application built with **Node.js**, **Express.js**, and **MongoDB**. This project provides essential task management features, allowing users to add, edit, and delete tasks, as well as mark them as completed. When a task is marked as completed, it appears with a strikethrough for easy identification. The app is hosted on [Render](https://render.com), a free hosting platform where inactive sites may take up to 60 seconds to load.

## Project Overview

Task Manager was designed to help users efficiently manage tasks by providing basic CRUD (Create, Read, Update, Delete) operations with a clean, user-friendly interface. Each task can be toggled as completed, making it easy for users to track their progress at a glance.

## Features

- **Add New Tasks**: Users can create new tasks.
- **Edit Tasks**: Modify the details of any existing task.
- **Delete Tasks**: Remove tasks that are no longer needed.
- **Mark as Completed**: Mark tasks as completed, which adds a strikethrough effect for visual clarity.
- **Persistence**: All tasks are stored in a MongoDB database, allowing data to persist across sessions.
- **Hosting**: Deployed on Render, which may require extra time to load due to its free hosting plan.

## Technologies Used

- **Node.js**: Server-side JavaScript runtime.
- **Express.js**: Framework for building the REST API and handling server-side routing.
- **MongoDB**: NoSQL database for task storage and retrieval.
- **Mongoose**: MongoDB object modeling for seamless integration with Node.js.

## Getting Started

To set up and run this project locally:

1. Clone this repository:

```bash
git clone https://github.com/atulkkale/task-manager.git
cd task-manager
```

2. Install dependencies:

```bash
npm install
```

3. Set up environment variables in a .env file, including MONGO_DB_URI and PORT=3000.

4. Run the app:

```bash
npm start
```

5. Open http://localhost:3000 in your browser to view the application.

## Project Link

You can access the deployed app on Render [here](https://task-manager-ouc3.onrender.com).

*`Note: Due to Render’s free hosting plan, it may take up to 60 seconds to load the site after periods of inactivity.`*

## Future Improvements

- Add user authentication to allow individual task management per user.
- Implement due dates and prioritization for tasks.
- Create a filter to view only completed or pending tasks.

## Screenshots

<img width="1680" alt="Screenshot 2024-11-12 at 3 38 16 PM" src="https://github.com/user-attachments/assets/7d4320c8-8cf8-4af0-ba77-37751df35a95">

<img width="1680" alt="Screenshot 2024-11-12 at 3 38 27 PM" src="https://github.com/user-attachments/assets/44bf34a6-16de-4f13-be7c-0b10aada5351">
