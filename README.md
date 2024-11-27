# RBAC-Authentication-Project

## Description
This project is a Flask-based web application implementing **Role-Based Access Control (RBAC)** with **JWT (JSON Web Tokens)** for user authentication and authorization. It includes the ability for users to register, log in, and access protected resources based on their roles. The roles supported are **Admin**, **Moderator**, and **User**, each with specific permissions.

## Features
- **User Registration**: Allows users to register with a username, password, and role.
- **User Login**: Users can log in to receive a JWT for authentication.
- **Role-Based Access Control**: Only users with specific roles can access protected resources.
- **Logout**: JWTs can be blacklisted to effectively log out users.

## Installation Instructions

### 1. Clone the repository
```bash
git clone https://github.com/your-username/RBAC-Authentication-System.git

Code Structure
app.py: Main application file where the Flask app is initialized.
auth/: Contains the authentication modules for login, logout, registration, and RBAC.
auth/jwt_instance.py: Initializes the JWTManager.
auth/register.py: Handles user registration.
auth/login.py: Handles user login.
auth/logout.py: Manages user logout and token blacklisting.
auth/rbac.py: Implements Role-Based Access Control (RBAC) for resource access.

Install dependencies:

pip install -r requirements.txt
