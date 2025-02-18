# 📌 Project Name: E_Commerce_Follow_Along

## 🚀 Overview

This project is an e-commerce website developed through a series of milestones, progressively adding features to build a complete and functional application.

## 📚 Table of Contents

- [Overview](#-overview)
- [Tech Stack](#-tech-stack)
- [Milestones](#-milestones)
  - [Milestone 1: Project Setup](#milestone-1-project-setup)
  - [Milestone 2: Frontend & Backend Initialization](#milestone-2-frontend--backend-initialization)
  - [Milestone 3: Backend Structure & Server Setup](#milestone-3-backend-structure--server-setup)
  - [Milestone 4: Creating User Model and Controller](#milestone-4-creating-user-model-and-controller)
  - [Milestone 5: Sign-Up Page & Form Validation](#milestone-5-sign-up-page--form-validation)
- [How to Run the Project](#-how-to-run-the-project)
- [Next Steps](#-next-steps)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🛠 Tech Stack

- Frontend: React.js, Tailwind CSS
- Backend: Node.js, Express.js
- Database: MongoDB
- File Uploads: Multer
- Version Control: Git, GitHub

---

## 📌 Milestones

### Milestone 1: Project Setup

_✅ Goals:_

- Created and updated README.md file.
- Initialized GitHub repository for version control.

---

### Milestone 2: Frontend & Backend Initialization

_✅ Goals:_

1. _Project Folder Structure:_ Organized files into separate frontend and backend directories.
2. _React Frontend Setup:_ Initialized a React application for building the user interface.
3. _Node.js Backend Setup:_ Set up a simple Node.js server for API integration in future milestones.
4. _Tailwind CSS Configuration:_ Integrated and configured Tailwind CSS for modern, responsive styling.
5. _Login Page Development:_ Created a login page with functionality and styling.

---

### Milestone 3: Backend Structure & Server Setup

_✅ Goals:_

1. _Backend Folder Structure:_ Created a structured hierarchy for organizing routes, controllers, models, and middleware.
2. _Server Setup:_
   - Used Node.js and Express.js to create a backend server.
   - Configured the server to listen on a designated port.
3. _Database Connection:_
   - Integrated MongoDB for efficient data storage.
   - Confirmed the connection between the server and MongoDB.
4. _Error Handling:_
   - Provided clear error messages for better debugging and user feedback.

---

### Milestone 4: Creating User Model and Controller

_✅ Goals:_

1. _User Model:_ Defined the structure of user data with attributes like name, email, password, and profile picture.
2. _User Controller:_ Handled user-related actions such as registration and data retrieval.
3. _Multer Integration:_ Enabled file uploads for storing user profile pictures.
4. _API Routes:_ Created endpoints for user creation and fetching user details.
5. _README Update:_ Documented progress and updated repository.

---

### Milestone 5: Sign-Up Page & Form Validation

_✅ Goals:_

1. _Sign-Up Page UI:_ Designed a clean and user-friendly sign-up form with fields for name, email, and password.
2. _Form Validation:_
   - Ensured the email follows the correct format.
   - Implemented password security criteria (minimum length, special characters, etc.).
3. _User Registration Flow:_ Integrated frontend form submission with the backend API.
4. _Error Handling:_ Displayed validation errors to users in real-time.
5. _README Update:_ Documented progress and updated repository.

---

### Milestone 6: Secure User Registration

_✅ Goals:_

1. _Password Encryption:_
   - Used bcrypt to hash passwords before storing them in the database.
   - Ensured no plaintext passwords are stored.
2. _Secure Data Storage:_
   - Stored the user's encrypted password along with other necessary details in MongoDB.
3. _Updated API Endpoints:_
   - Modified the user registration endpoint to handle password hashing securely.
4. _Security Compliance:_
   - Followed best practices for protecting user credentials.
   - Complied with security standards like GDPR and PCI-DSS.
5. _README Update:_
   - Documented progress for Milestone 6 and updated the repository.

---

## ▶ How to Run the Project

1. Clone the repository:
   bash
   git clone https://github.com/your-username/E_Commerce_Follow_Along.git
   cd E_Commerce_Follow_Along
2. Install dependencies for both frontend and backend:
   bash
   cd frontend && npm install
   cd ../backend && npm install
3. Run the backend server:
   bash
   npm start
4. Run the frontend application:
   bash
   cd frontend
   npm start
5. Open http://localhost:3000/ in your browser.

---
