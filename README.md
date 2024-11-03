**JobVerse a Job-Portal Website**

**Description**
This project consists of a frontend and backend component. Our Job Portal App connects job seekers with the latest opportunities, enabling them to browse, apply, and track applications effortlessly. Employers can post jobs, review candidates, and manage hiring efficiently through a streamlined dashboard. With real-time notifications and a user-friendly interface, finding the perfect match has never been easier.

**Table of Contents**
- Features
- Technologies Used
- Installation
- Running the Project
- License

**Features:-**
**Backend**
- User authentication with JWT
- Secure password storage using bcrypt
- Image handling with Cloudinary
- Data handling with MongoDB

**Frontend**
- Responsive UI built with React
- State management using Redux
- Dynamic routing with React Router
- Styled with Tailwind CSS

**Technologies Used**
- **Backend:**
  - Node.js
  - Express
  - MongoDB (using Mongoose)
  - Cloudinary
  - JWT
  - dotenv

- **Frontend:**
  - React
  - Vite
  - Redux
  - Axios
  - Tailwind CSS

**Installation**

1. **Clone the repository:**
   git clone https://github.com/ishansavaliya/JobVerse-a-Job-Portal-Website.git
   

2. **Navigate to the project directory:**
   cd Job-Portal-Website
  

3. **Set up the backend:**
   - Navigate to the backend directory:
     cd backend
     
   - Install backend dependencies:
     npm install
     

   - Set up environment variables:  
     Create a `.env` file in the `backend` directory and add the following:
     
     MONGO_URI=<Your File>
     SECRET_KEY=<Your File>
     CLOUD_NAME=<Your File>
     API_KEY=<Your File>
     API_SECRET=<Your File>
     

4. **Set up the frontend:**
   - Navigate to the frontend directory:
     cd ../frontend
     
   - Install frontend dependencies:
     npm install
     

**Running the Project**

**Backend**
- **Development Mode:**  
  Start the backend server in development mode using Nodemon:
  cd backend
  npm run dev
  

**Frontend**
- **Development Mode:**  
  Start the frontend server using Vite:
  cd frontend
  npm run dev
  
License
This project is licensed under the ISC License.

