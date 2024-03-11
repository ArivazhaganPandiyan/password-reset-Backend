# Password Reset Task App Backend

This document provides an overview of the backend implementation for a password reset task application using Node.js and MongoDB.

## Overview

The password reset task app backend serves as the server-side component responsible for managing user accounts, password reset functionality, and database interactions. It exposes APIs to handle user authentication, account management, and password reset requests.

## Technologies Used

- **Node.js**: A JavaScript runtime environment that executes JavaScript code outside of a web browser.
- **Express.js**: A web application framework for Node.js that simplifies building web applications and APIs.
- **MongoDB**: A NoSQL document-oriented database used for storing user account information.
- **Mongoose**: An Object Data Modeling (ODM) library for MongoDB and Node.js, providing a higher-level abstraction for interacting with MongoDB.

## Features

1. **User Authentication**: Allows users to create accounts, log in, and log out securely.
2. **Password Reset Functionality**: Enables users to request a password reset via email and securely reset their passwords.
3. **User Account Management**: Provides endpoints to update user profiles, change passwords, and delete accounts.
4. **Token-based Authentication**: Implements token-based authentication using JSON Web Tokens (JWT) for secure API access.
5. **Middleware for Request Validation**: Utilizes middleware for input validation to ensure data integrity and security.
6. **Error Handling**: Implements error handling middleware to gracefully handle errors and provide meaningful responses to clients.
7. **Logging**: Integrates logging functionality to record application events and monitor server activity.
8. **Security Measures**: Implements security best practices such as password hashing, rate limiting, and HTTPS for enhanced security.
9. **Deployment Ready**: Configured for deployment on platforms like Heroku, AWS, or similar hosting services.

## Setup Instructions

1. Clone the repository.
2. Install dependencies using `npm install`.
3. Configure environment variables such as database connection URI, JWT secret, and email service credentials.
4. Run the server using `npm start`.
5. Access the API endpoints using tools like Postman or integrate them into the frontend application.

## API Endpoints

### Authentication

- `POST /api/auth/register`: Register a new user.
- `POST /api/auth/login`: Log in an existing user.
- `POST /api/auth/logout`: Log out the current user.



## Database Schema

The MongoDB database contains a `users` collection with the following schema:

## Frontend Code Repository

The frontend code for the password reset task application can be found in the following repository:

[Frontend Code Repository](https://github.com/ArivazhaganPandiyan/reset-password-client)



