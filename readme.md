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
ecommerce-app/
|-- backend/
| |-- controllers/
| | |-- authController.js
| | |-- productController.js
| | |-- cartController.js
| |
| |-- models/
| | |-- User.js
| | |-- Product.js
| | |-- Cart.js
| |
| |-- routes/
| | |-- authRoutes.js
| | |-- productRoutes.js
| | |-- cartRoutes.js
| |
| |-- middleware/
| | |-- authMiddleware.js
| |
| |-- app.js
| |-- server.js
|
|-- frontend/
| |-- public/
| |-- src/
| | |-- components/
| | | |-- AuthForm.js
| | | |-- ProductList.js
| | | |-- ProductDetail.js
| | | |-- Cart.js
| | |
| | |-- redux/
| | | |-- store.js
| | | |-- constants.js
| | | |-- actions/
| | | | |-- authActions.js
| | | | |-- productActions.js
| | | | |-- cartActions.js
| | | |
| | | |-- reducers/
| | | |-- authReducer.js
| | | |-- productReducer.js
| | | |-- cartReducer.js
| | | |-- rootReducer.js
| | | |--index.js
| | |
| | |-- App.js
| | |-- index.js
| |
| |-- package.json
|
|-- package.json
|-- README.md

### Backend Setup

1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/ecommerce-mern.git
   cd ecommerce-mern/backend
   2.Install dependencies
   npm install
   ```
2. Create a .env file in the backend folder and add the following environment variables:
   env
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   PORT=8000
   3.Start the backend server
   npm run server

###Frontend Setup

1.Navigate to the frontend folder:
cd ../frontend

2.Install dependencies:
npm install
3.Start the frontend development server:
npm start

4.Usage:
Open your browser and navigate to http://localhost:3000
Register a new user or log in with an existing account
Browse products, view product details, and add products to your cart
