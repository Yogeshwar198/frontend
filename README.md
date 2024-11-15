# Task Management

This is a full-stack task management application built using React for the frontend and Node.js with Express for the backend. It allows users to manage tasks across multiple categories such as To Do, In Progress, Done, and Timeout. The application interacts with a backend API to perform CRUD operations on tasks and includes features such as form validation, error handling, and timeout management. Tasks that exceed a certain time limit are automatically moved to the "Timeout" category.

---

## Frontend

### Technologies Used:
- **React**: A JavaScript library for building user interfaces.
- **TailwindCSS**: A utility-first CSS framework for rapidly building custom designs.
- **Axios**: A promise-based HTTP client for the browser and Node.js.
- **React Icons**: A library that provides a set of customizable icons as React components. It allows you to easily integrate popular icon sets like FontAwesome, Material Design, and more.


### Installation (Frontend)

To run this application locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   ```

2. **Navigate to the project directory:**
```bash
cd <filename>
```

3. **Install the dependencies:**
```bash
npm install
```
4. **Run the application:**
```bash
npm start
```
5. **Open your browser and visit:**
```bash
http://localhost:3000
```

## Features

- **Task List**: Displays tasks with relevant information.
- **Task Item**: Individual task details displayed in a structured format.
- **Task Form**: Allows adding and editing tasks with proper form validation and error handling.
- **State Management**: Uses React hooks or the Context API for managing the state across the application.
- **API Integration**: Uses async/await to make API calls to the backend.
- **Timeout Handling**: Automatically moves tasks to the "Timeout" category if their duration exceeds a specific limit.
- **Error Handling & UX**: Includes loading indicators, error messages, and good UX practices.

## Backend

### Technologies Used:

- **Express**: A fast, unopinionated web framework for Node.js.
- **Mongoose**: An ODM (Object Data Modeling) library for MongoDB and Node.js.
- **Cors**: A package for enabling Cross-Origin Resource Sharing.
- **Dotenv**: A module for loading environment variables from a .env file.
- **Nodemon**: A tool for automatically restarting the server during development.


### Installation (Backend)

To run this application locally, follow these steps:


1. **Navigate to the project directory:**
```bash
 cd backend
```

2. **Install the dependencies:**
```bash
npm install
```
3. **Run the application:**
```bash
npm run server
```
4. **Open your browser and visit:**
```bash
http://localhost:4000
```

## Features
- **Node.js with Express**: Backend API framework built on Node.js with Express and TypeScript.
- **Endpoints**:
- GET /tasks: Fetch all tasks.
- GET /tasks/:id: Fetch a single task by ID.
- POST /tasks: Create a new task.
- PUT /tasks/:id: Update a task by ID.
- DELETE /tasks/:id: Delete a task by ID.

- **Async Handling**: Implements advanced async handling with a streaming API to integrate external data with task details.
- **Database**: Uses an in-memory database for simplicity or lightweight databases like SQLite or MongoDB.
- **Timeout Feature**: Tasks will be moved to the "Timeout" category if their duration exceeds a certain threshold.
- **Error Handling**: Robust error handling and validation for all endpoints.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
Yogeshwar Singh - yogeshwaredu198@gmail.com
