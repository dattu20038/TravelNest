# TravelNest

TravelNest is a full-stack web application built using the MERN stack (MongoDB, Express, React, Node.js). This project allows users to book and manage accommodations seamlessly. It provides a user-friendly interface for searching, booking, and reviewing hotels, as well as a secure admin panel for managing the bookings and properties.

## Features

* **User Authentication**: Users can register, log in, and manage their accounts.
* **Search & Filter**: Users can search for available hotels based on location, price, and other filters.
* **Booking System**: Secure booking functionality with date selection and confirmation.
* **Hotel Details**: Each hotel has detailed information including descriptions, amenities, and reviews.
* **Responsive Design**: Optimized for use on both desktop and mobile devices.

## Tech Stack

### Frontend:
* React.js
* React Router for navigation
* Axios for API requests
* CSS and styled-components for styling

### Backend:
* Node.js with Express.js
* MongoDB (NoSQL database)
* JWT for user authentication

## Setup Instructions

To run TravelNest locally, follow these steps:

### 1. Clone the Repository
```bash
git clone https://github.com/dattu20038/TravelNest.git
cd travelnest
```

### 2. Install Dependencies

For Frontend:
```bash
cd client
npm install
```

For Backend:
```bash
cd server
npm install
```

### 3. Set Up Environment Variables

Create a `.env` file in the server directory with the following variables:
```makefile
MONGO_URI=your_mongo_db_connection_string
JWT_SECRET=your_jwt_secret_key
```

### 4. Start the Application

To run the backend:
```bash
cd server
npm start
```

To run the frontend:
```bash
cd client
npm start
```

Now, navigate to http://localhost:3000 in your web browser to access the application.
