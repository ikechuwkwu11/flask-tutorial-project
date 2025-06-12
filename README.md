# 🧑‍💻 Flask User Session Manager
Flask User Session Manager is a simple yet effective web application built with Flask, demonstrating essential user authentication features including login, session management, email updates, and user listing, all backed by SQLite for persistent data storage.

## ✅ Features
- User Registration & Login using just a username
- Update Email Address for the logged-in user
- Session Management with automatic expiration
- View All Registered Users
- Persistent Storage using SQLite
- Flash Messaging for user-friendly feedback

## 🛠 Tech Stack
- Layer	Technology
- Backend	Python 3.x, Flask
- ORM	Flask-SQLAlchemy
- Frontend	HTML, Jinja2 Templates
- Database	SQLite (default)
- UX Feedback	Flask Flash Messaging

## 🔍 Usage Guide
- Visit / — Home page
- Register a new user or log in using a username
- Update your email address once logged in
- View all users at /users (optional admin/public feature)
- Logout to end the session

Session data is stored securely and will expire after a set time (if configured).

## ✅ To-Do / Possible Enhancements
- Add password support with hashing
- Improve UI with Bootstrap or custom CSS
- Add email validation or unique email constraint
- Implement user roles (admin/user)
