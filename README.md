# MERN-FullStack-Social-Media-App
A COMPLETE Fullstack Responsive MERN App with Auth, Likes, Dark Mode | React, MongoDB, MUI

## Overview
This is a fullstack web application built using the MERN stack (MongoDB, Express.js, React, and Node.js). The application features user authentication, likes functionality, and a dark mode toggle. The frontend is built with React and Material-UI (MUI) for a modern and responsive user interface.

## Features
- **User Authentication:** Users can sign up, log in, and log out securely.
- **Likes Functionality:** Users can like and unlike posts.
- **Dark Mode:** Users can toggle between light and dark modes.
- **Responsive Design:** The application is fully responsive and works on all device sizes.

## Technologies Used
- **Frontend:**
  - React
  - Material-UI (MUI)
  - Axios
  - React Router
  - Context API for state management
- **Backend:**
  - Node.js
  - Express.js
  - MongoDB
  - Mongoose
  - JSON Web Tokens (JWT) for authentication
  - Bcrypt for password hashing

## Installation
### Prerequisites
- Node.js
- MongoDB

### Backend Setup
1. Clone the repository:
    ```bash
    git clone https://github.com/sasi5935/mern-app.git
    ```
2. Navigate to the backend directory:
    ```bash
    cd mern-app/backend
    ```
3. Install backend dependencies:
    ```bash
    npm install
    ```
4. Create a `.env` file in the backend directory and add the following environment variables:
    ```env
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    ```
5. Start the backend server:
    ```bash
    npm start
    ```

### Frontend Setup
1. Open a new terminal window and navigate to the frontend directory:
    ```bash
    cd mern-app/frontend
    ```
2. Install frontend dependencies:
    ```bash
    npm install
    ```
3. Start the frontend development server:
    ```bash
    npm start
    ```

## Usage
1. Open your browser and go to `http://localhost:3000`.
2. Sign up for a new account or log in if you already have one.
3. Create, like, and unlike posts.
4. Toggle between light and dark modes using the switch in the header.

## API Endpoints
### Auth
- `POST /api/auth/register`: Register a new user.
- `POST /api/auth/login`: Log in an existing user.

### Posts
- `GET /api/posts`: Get all posts.
- `POST /api/posts`: Create a new post.
- `PUT /api/posts/:id/like`: Like or unlike a post.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes. Ensure your code adheres to the project's coding standards and includes appropriate documentation.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
