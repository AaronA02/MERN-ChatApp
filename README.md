# MERN Stack Project: Build and Deploy a Real Time Chat App | JWT, Socket.io

 A real-time chat application using the MERN stack, which includes MongoDB for the database, Express.js for the server framework, React.js for the front-end, and Node.js for the server runtime environment.

Some Features:

 * User Authentication:

 - Implemented secure user signup and login functionalities using bcrypt for password hashing and JWT for authentication.
 - Included features like user profile creation with profile pictures based on gender.

 * Real-time Messaging:

 - Enabled real-time messaging between users using WebSockets via the socket.io library.
 - Developed components for message input, message display, and conversation management.
 * User Interface:

 - Designed a responsive user interface with React.js, including components for the sidebar, message container, and user authentication pages (login and signup).
 - Utilized Tailwind CSS for efficient styling and layout management.
 * State Management:

 - Managed application state using React hooks and Zustand for lightweight state management.
 - Implemented custom hooks for authentication, messaging, and conversation management.
 * Backend API:

 - Created RESTful API endpoints for user authentication, message handling, and user management.
 - Structured the backend with Express.js, handling routes for authentication, messaging, and user data.
 * Database Integration:

 - Used MongoDB to store user data, messages, and conversation information.
 - Applied Mongoose for schema definitions and database operations.
 * Security:

 - Ensured secure communication and data handling with JSON Web Tokens (JWT) for authentication and secure password storage with bcrypt.
 - Implemented cookie-based sessions for maintaining user login state.
 * Deployment:

 - Configured the application for deployment, including environment variable management and static file serving.

### Setup .env file

```js
PORT=...
MONGO_DB_URI=...
JWT_SECRET=...
NODE_ENV=...
```

### Build the app

```shell
npm run build
```

### Start the app

```shell
npm start
```
