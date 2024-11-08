
---

# JobVerse - A Job Portal Website

**Description:**  
JobVerse is a full-featured job portal app that connects job seekers with the latest opportunities, allowing them to browse, apply, and track job applications effortlessly. Employers can post job listings, review candidates, and manage the hiring process through a streamlined dashboard. With real-time notifications and a user-friendly interface, finding the perfect match has never been easier.

---

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Running the Project](#running-the-project)
- [License](#license)

---

## Features

### Backend
- User authentication with JWT
- Secure password storage using bcrypt
- Image handling with Cloudinary
- Data handling with MongoDB

### Frontend
- Responsive UI built with React
- State management using Redux
- Dynamic routing with React Router
- Styled with Tailwind CSS

---

## Technologies Used

- **Backend:**
  - Node.js
  - Express
  - MongoDB (Mongoose)
  - Cloudinary
  - JWT
  - dotenv

- **Frontend:**
  - React
  - Vite
  - Redux
  - Axios
  - Tailwind CSS

---

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ishansavaliya/JobVerse-a-Job-Portal-Website.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd Job-Portal-Website
   ```

3. **Set up the backend:**
   - Navigate to the backend directory:
     ```bash
     cd backend
     ```
   - Install backend dependencies:
     ```bash
     npm install
     ```
   - Set up environment variables:  
     Create a `.env` file in the `backend` directory with the following:
     ```env
     MONGO_URI=<Your MongoDB URI>
     SECRET_KEY=<Your Secret Key>
     CLOUD_NAME=<Your Cloudinary Cloud Name>
     API_KEY=<Your Cloudinary API Key>
     API_SECRET=<Your Cloudinary API Secret>
     ```

4. **Set up the frontend:**
   - Navigate to the frontend directory:
     ```bash
     cd ../frontend
     ```
   - Install frontend dependencies:
     ```bash
     npm install
     ```

---

## Running the Project

### Backend

- **Development Mode:**  
  Start the backend server with Nodemon:
  ```bash
  cd backend
  npm run dev
  ```

### Frontend

- **Development Mode:**  
  Start the frontend server with Vite:
  ```bash
  cd frontend
  npm run dev
  ```

---

## License
This project is licensed under the ISC License.

--- 

