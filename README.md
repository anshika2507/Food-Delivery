# Food-Delivery

---

## Project Overview.
This project is a MERN Stack web application for food delivery built using the MERN stack (MongoDB, Express.js, React.js, Node.js). It allows users to browse restaurants, view menus, place orders, and manage their accounts.

## Authors
   *Training project :- Food Delivery Website*
   Course:B.C.A. Semester:4
- *Awadhesh Kumar*
- *Ansh Gupta*
- *Anshika Shukla*
- *Anshika Dwivedi*

## Features

- User authentication 
- Google authentication via Firebase
- Create, read, update, and delete property listings
- Responsive and user-friendly UI
- State management with Redux Toolkit

## Technology Stack

- *Frontend:*
  - React-VITE
  - HTML
  - CSS 
  -JavaScript
  

- *Backend:*
  - Node.js
  - bcrypt
  - cors
  - dotenv
  -body-parser
  - multer

- *Database:*
  - MongoDB Atlas

- *Authentication:*
  - Custom User Authentication (JWT)
  - validator
## Getting Started

### Prerequisites

Ensure you have the following installed:

- Node.js
- npm or yarn
- MongoDB
- Firebase account

### Installation
1. Install the dependencies for both the client and server:
   bash
   cd client
   npm install
   cd ../server
   npm install
   

2. Set up environment variables:

   Create a .env file in the server directory and add your MongoDB URI and JWT secret:

   plaintext
   MONGODB_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
   

   Create a .env file in the client directory and add your Firebase configuration:

  pl aintext
   REACT_APP_FIREBASE_API_KEY=your_api_key
   REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain
   REACT_APP_FIREBASE_PROJECT_ID=your_project_id
   REACT_APP_FIREBASE_STORAGE_BUCKET=your_storage_bucket
   REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
   REACT_APP_FIREBASE_APP_ID=y
   

### Running the Application

1. Start the backend server:
   bash
   cd server
   npm start
   

2. Start the frontend development server:
   bash
   cd client
   npm start
   

3. Open your browser and navigate to http://localhost:4000 to see the application in action.

## Contributing

We welcome contributions to HomeHeaven! Please follow these steps:

1. Fork the repository
2. Create a new branch (git checkout -b feature-branch)
3. Commit your changes (git commit -am 'Add new feature')
4. Push to the branch (git push origin feature-branch)
5. Create a new Pull Request



---
