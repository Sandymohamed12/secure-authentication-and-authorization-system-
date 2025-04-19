# secure-authentication-and-authorization-system-
# Secure Authentication and Authorization System

This project is a secure authentication and authorization system built using **Express.js**, **JWT (JSON Web Tokens)**, and **Role-Based Access Control (RBAC)**. The system allows users to register, log in, and access protected routes based on their roles (`user`, `moderator`, `admin`). It also features password hashing using **bcrypt**.

## Features Implemented
- **User Registration and Login**: Users can register with a username, email, password, and role, and log in with their credentials to receive a JWT token.
- **JWT-based Authentication**: JSON Web Tokens (JWT) are used to authenticate and authorize users for accessing protected routes.
- **Role-Based Access Control (RBAC)**: Three user roles are supported: `user`, `moderator`, and `admin`. Different routes are restricted based on the user's role.
- **Protected Routes**: The system includes protected routes that are only accessible by authenticated users.
- **Profile Management**: Users can view and update their profile details (email and password).
- **Rate Limiting**: Basic rate limiting is implemented for login and registration endpoints to prevent abuse.
- **Security Enhancements**: Passwords are hashed using **bcrypt**, and JWT tokens are validated to ensure security.

## Requirements
- **Node.js** and **npm** installed on your machine.

## Setup Instructions

1. **Clone the Repository**:
   Clone this repository to your local machine:
   ```bash
   git clone https://github.com/Sandymohamed12/secure-authentication-and-authorization-system-.git
