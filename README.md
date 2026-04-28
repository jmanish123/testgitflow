# Todo Application

A full-stack todo application with Node.js backend and vanilla JavaScript frontend.

## Features

- Add new tasks
- Mark tasks as completed/undo completion
- Delete tasks
- RESTful API backend
- In-memory data storage

## Project Structure

- `server.js`: Express server with API routes
- `public/index.html`: Frontend application
- `package.json`: Project dependencies and scripts

## Installation

1. Ensure Node.js is installed on your system.
2. Clone or download the project.
3. Run `npm install` to install dependencies.

## Running the Application

1. Start the server: `npm start`
2. Open your browser and navigate to `http://localhost:3000`

## API Endpoints

- `GET /api/todos`: Retrieve all todos
- `POST /api/todos`: Create a new todo (body: `{ "text": "task description" }`)
- `PUT /api/todos/:id`: Update a todo (body: `{ "completed": true/false }`)
- `DELETE /api/todos/:id`: Delete a todo

## Technologies Used

- Backend: Node.js, Express.js
- Frontend: HTML, CSS, JavaScript (vanilla)
- Data Storage: In-memory (resets on server restart)

## Development

For development, you can modify the files and restart the server. The frontend is served statically from the `public` directory.
