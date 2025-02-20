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
  - [Milestone 6: Secure User Registration](#milestone-6-secure-user-registration)  
  - [Milestone 7: User Login & Authentication](#milestone-7-user-login--authentication)  
  - [Milestone 8: Product Card Component & Homepage Layout](#milestone-8-product-card-component--homepage-layout)  
  - [Milestone 9: Product Input Form](#milestone-9-product-input-form)  
  - [Milestone 10: Product Schema & Endpoint Creation](#milestone-10-product-schema--endpoint-creation)
  - [Milestone 11: Dynamic Homepage with Product Data](#milestone-11-dynamic-homepage-with-product-data)
  - [Milestone 12: My Products Page - Filtering by User Email](#milestone-12-my-products-page---filtering-by-user-email)
- [How to Run the Project](#-how-to-run-the-project) ---

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

### 🏆 Milestone 7: Secure Login with Password Verification

- Developed a _backend endpoint_ for user login.
- Implemented _user authentication_ by validating credentials.
- Used _bcrypt_ to compare hashed passwords securely.
- Ensured compliance with _security standards_ like GDPR and PCI-DSS.
- Returned appropriate error messages for _invalid credentials_.
- Updated the _README.md_ file with progress details.
- Committed and pushed changes to the _GitHub repository_.

---

### 🏆 Milestone 8: Product Card Component and Homepage Design

- Designed a _reusable Product Card Component_ to display product details.
- Implemented _props_ to pass product information dynamically (e.g., name, price, image).
- Used _array mapping_ to display multiple products efficiently.
- Designed a _structured homepage layout_ with a clean and visually appealing UI.
- Ensured _responsiveness_ using CSS Grid or Flexbox.
- Updated the _README.md_ file with progress details.
- Committed and pushed changes to the _GitHub repository_.

---

### 🏆 Milestone 9: Product Form Creation

✅ Goals:

- Product Form: Developed a product form for adding products with multiple images.
- Admin Access (Optional): Experimenting with adding admin-specific upload functionality.
- User Profiles (Optional): Considering adding shop-specific user roles for uploading products.
- Next Steps: Implement role-based access, improve validation, and optimize image upload.

---

### Milestone 10: Product Schema and API Endpoint Creation

✅ Goals:

## Product Schema:

- Created a Mongoose schema for product data, including fields like product name, description, price, and image URL.
- Implemented validation to ensure the fields are correctly formatted and required.
- Ensured data integrity with proper field types and validation rules.
- API Endpoint Creation:
  _ Developed a POST endpoint to accept product data from the client-side.
  _ Validated incoming product details and saved them to the MongoDB database. \* Integrated error handling to ensure smooth validation and saving of product data.
- Validation:

      * Used Mongoose's built-in validation methods to enforce constraints on product data.
      * Prevented invalid or incomplete data from being stored in the database.

---

### Milestone 11: Dynamic Homepage with Product Data

✅ Goals:

1. Backend - Fetch All Products
   Created an API endpoint to retrieve all product data stored in MongoDB.
   Used Express.js and Mongoose to fetch and send product details as JSON.

2. Frontend - Fetch & Display Data Dynamically
   Created a function to fetch product data from the backend.
   Passed the received data to the existing Product Card Component.
   Used .map() to dynamically render each product on the homepage.

3. Why This Matters?
   Enables dynamic content loading from the database instead of hardcoded values.
   Improves scalability and flexibility as new products are added.

4. Submission Steps
   ✅ Pushed the updated code to the GitHub repository.
   ✅ Updated the README.md file with Milestone 11 details.
   ✅ Shared the repository link for submission.

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
