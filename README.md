# Task Management Application

This is a full-stack web application for managing tasks. It provides a user-friendly interface for creating, updating, and tracking tasks. The application is built using Node.js, Express.js, MongoDB.

## Features

- **User Authentication**: Users can register, log in, and securely access the application.
- **Task Management**: Users can create new tasks, set due dates, assign tasks to other users, and update task status.
- **Task Filtering and Sorting**: Tasks can be filtered based on status, assigned user, or due date. Tasks can also be sorted by various criteria.
## Technologies Used

- **Backend**: Node.js, Express.js
- **Database**: MongoDB, Mongoose
- **Authentication**: JSON Web Tokens (JWT)

## Getting Started

### Prerequisites

- Node.js (v14 or later)
- npm (Node Package Manager)
- MongoDB (local or remote instance)

### Installation

1. Clone the repository:

```
git clone https://github.com/NGangaMahesh/task-management-application.git
```

2. Navigate to the project directory:

```
cd task-management-app
```

3. Install the dependencies:

```
npm install
```

4. Create a `.env` file in the project root directory and provide the required environment variables:

```
MONGODB_URI=your-mongodb-uri
JWT_SECRET=your-jwt-secret
```

Replace `your-mongodb-uri` with the connection string for your MongoDB instance, and `your-jwt-secret` with a secure secret key for JWT authentication.

### Running the Application

```
npm start
```

This will start the backend server and the React development server concurrently.

### Running Tests

```
npm test
```

This will run the unit tests and integration tests for the backend.

### Building for Production

```
npm run build
```

This will create an optimized production build of the React frontend in the `build` directory.

## Acknowledgments

- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)
- [Render](https://render.com/)
