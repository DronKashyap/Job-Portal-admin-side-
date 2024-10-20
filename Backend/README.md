# Job Posting Backend

## Overview

This project is a job posting backend application built using **Node.js**, **Express.js**, and **TypeScript**. The backend provides a RESTful API that allows users to manage job postings, candidates, and user accounts efficiently. It integrates various technologies for robust functionality, including **Bcrypt** for password hashing, **Zod** for input validation and **JWT** for user authentication.

## Tech Stack

- **Node.js**: A JavaScript runtime built on Chrome's V8 engine, enabling the creation of scalable server-side applications.

- **Express.js**: A fast, unopinionated, minimalist web framework for Node.js that provides robust routing and middleware support.

- **TypeScript**: A superset of JavaScript that adds static typing, enhancing code quality and maintainability.

- **Bcrypt**: A library for hashing passwords, ensuring secure user authentication.

- **Zod**: A TypeScript-first schema declaration and validation library, allowing for strong input validation and error handling.

- **Jsonwebtoken**: A library for generating tokens, which are verified at the time of authentication.


## Features

- **User Management**: Create, retrieve, update, and delete user accounts with secure password storage using Bcrypt.
- **Job Postings**: Manage job postings including creating, retrieving, updating, and deleting job listings.
- **Candidate Management**: Allow candidates to apply for jobs and manage candidate data.
- **Input Validation**: Ensure all incoming data is validated against predefined schemas using Zod.


## Getting Started

### Prerequisites

- Node.js (version >= 14)
- MongoDB (for database management)
- A package manager (npm or yarn)

### Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
Navigate to the project directory:


cd <project-directory>
Install the required dependencies:


npm install
Set up your environment variables:

Create a .env file in the root directory and add the following variables:

PORT=3000
DB_URL=<your_mongodb_connection_string>

Run the application:

npm run dev
The backend will start running on the specified port (default is 3000).
# API Endpoints

## Users
- **POST /api/user/signup**: Create a new user  
- **POST /api/user/signin**: signin a user  
- **GET /api/user/users/:id**: Get a user by ID  
- **PUT /api/user/users/:id**: Update user information  
- **DELETE /api/user/users/:id**: Delete a user  
- **GET /api/user/users**: Retrieve all users  

## Job Postings
- **POST /api/jobpostings/jobpostings**: Create a new job posting  
- **GET /api/jobpostings/jobpostings/:id**: Get a job posting by ID  
- **PUT /api/jobpostings/jobpostings/:id**: Update job posting information  
- **DELETE /api/jobpostings//jobpostings/:id**: Delete a job posting  
- **GET /api/jobpostings/jobpostings**: Retrieve all job postings  

## Candidates
- **POST /api/candidates/candidates**: Create a new candidate  
- **GET /api/candidates/candidates/:id**: Get a candidate by ID  
- **GET /api/candidates/candidates**: Retrieve all candidates  

# Contributing
Contributions are welcome! Please follow these steps to contribute to the project:

1. Fork the repository.
2. Create a new branch (e.g., `git checkout -b feature/YourFeature`).
3. Commit your changes (e.g., `git commit -m 'Add some feature'`).
4. Push to the branch (e.g., `git push origin feature/YourFeature`).
5. Open a pull request.

# Acknowledgments
- Node.js - JavaScript runtime  
- Express.js - Web framework for Node.js  
- TypeScript - Typed superset of JavaScript  
- Bcrypt - Password hashing library  
- Zod - TypeScript-first schema validation
- JWT- For user authentication  

For any questions or support, feel free to reach out!
