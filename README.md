# Backend for User Management System

This is the backend application for a user management system, built with Node.js, Express.js, MongoDB, and JWT for authentication.

## Features

- **User Authentication**: Secure registration and login using JWT.
- **Role-Based Access Control**: Different access levels for users and admins.
- **User Management**:
  - Admin can add, update, or delete users.
  - Fetch all users from the database.
- **Protected Endpoints**: Endpoints secured with JWT-based authentication.
- **MongoDB Integration**: All user data is stored in MongoDB.

---

## Technologies Used

- **Node.js**: Backend runtime.
- **Express.js**: Framework for building the API.
- **MongoDB**: Database for storing user information.
- **Mongoose**: Object Data Modeling (ODM) for MongoDB.
- **bcrypt**: For hashing passwords.
- **jsonwebtoken**: For creating and verifying JWT tokens.
- **dotenv**: For environment variable management.
- **cors**: To enable Cross-Origin Resource Sharing.

---

## Prerequisites

- **Node.js**: [Download and install Node.js](https://nodejs.org/).
- **MongoDB**: Make sure you have MongoDB installed and running, or use a cloud database like [MongoDB Atlas](https://www.mongodb.com/cloud/atlas).
- **Environment Variables**: Create a `.env` file in the root directory of your project with the following variables:

```plaintext
DB_URI=mongodb://localhost:27017/RBACbased
SECRET_KEY=e7f8f35c8493b3be457be41cbf84894401319b8d85a84e9dbfb8b1891f4f24c9
PORT=<Port to run the backend> # Optional (default is 3001)
