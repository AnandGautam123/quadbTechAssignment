# E-Commerce MERN Stack Application

This is a full-stack E-Commerce application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). The application allows users to register, log in, browse products, view product details, and add products to their cart.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Screenshots](#screenshots)
- [License](#license)

## Features

- User Authentication (Register/Login)
- Product Listing
- Product Details
- Add to Cart functionality

## Technologies Used

- **Frontend**: React.js, Redux, Redux Thunk, React Router DOM, Axios
- **Backend**: Node.js, Express.js, MongoDB, Mongoose
- **Others**: JWT for authentication, bcrypt for password hashing

## Installation

### Prerequisites

- Node.js and npm installed on your machine
- MongoDB Atlas or a local MongoDB server

###Structure
<img width="326" alt="Screenshot 2024-07-03 at 12 15 21 PM" src="https://github.com/AnandGautam123/quadbTechAssignment/assets/103447008/e4db135c-2b75-4c4d-a8f4-d6d74eddb2c2">

### Backend Setup

1. Clone the repository
   ```bash
   git clone https://github.com/AnandGautam123/quadbTechAssignment.git
   cd ecommerce-mern/backend
   ```
2.Install dependencies
 ```bash
   npm install
 ```
4. Create a .env file in the backend folder and add the following environment variables:
   env
    ```bash
      MONGO_URI=your_mongodb_connection_string
      JWT_SECRET=your_jwt_secret
      PORT=8000
     ```
5.Start the backend server
 ```bash
   npm run server
 ```

###Frontend Setup

1.Navigate to the frontend folder:
 ```bash
   cd ../frontend
 ```
2.Install dependencies:
 ```bash
   npm install
 ```
3.Start the frontend development server:
 ```bash
   npm start
 ```

4.Usage:
Open your browser and navigate to http://localhost:3000
Register a new user or log in with an existing account
Browse products, view product details, and add products to your cart
