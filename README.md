# Employee-Management-System


This project is a full-stack employee management application, allowing for CRUD (Create, Read, Update, Delete) operations on employee records. It includes a backend built with Express and MongoDB, and a frontend using React.

# Features
- Create, update, view, and delete employee records.
- Validation for required fields like email, department, and role.
- Error Handling for routes and invalid data inputs.
- User Interface with Tailwind CSS for a modern look and feel.

# Tech Stack
- Backend: Node.js, Express, TypeScript, MongoDB (Mongoose).
- Frontend: React, TypeScript, Vite, Tailwind CSS, React Router.
- Additional Libraries:
  - `react-query` for data handling in the frontend.
  - `dotenv` for environment configuration.
  - `mongoose` for MongoDB modeling and validation.

# Project Structure
```plaintext
arya_project/
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middlewares/
│   ├── models/
│   ├── routes/
│   └── server.ts
├── client/
│   ├── src/
│   │   ├── components/
│   │   ├── layouts/
│   │   ├── pages/
│   │   └── App.tsx
└── README.md


# Setup Instructions
Prerequisites
Node.js and npm installed.
MongoDB instance running locally or a MongoDB Atlas URI.


# Backend Setup
Navigate to the backend directory : cd backend
Install dependencies : npm install
Start the server : npm run start


# Frontend Setup
Navigate to the client directory : cd client
Install dependencies : npm install
Start the frontend : npm run dev


