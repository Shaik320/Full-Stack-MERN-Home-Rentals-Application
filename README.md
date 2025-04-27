# Full Stack Home Rentals Application

## 📌 Project Overview

This project is a **Full Stack Home Rentals Application** built with the **MERN** stack (MongoDB, Express.js, React.js, Node.js), demonstrating the ability to build a scalable, production-ready web application. It provides a platform for property owners to list their properties, and for users to browse, filter, and inquire about rentals.

### 🚀 **Deployment Status**  
The **frontend** is **live on Vercel**, and **backend deployment** is in progress. The project is ready for production, with a seamless user experience and optimized performance.

---

## 🛠️ **Technologies Used**

- **Frontend:**  
  - React.js (for building user interfaces)
  - Redux Toolkit (for state management)
  - SCSS (for modular and maintainable styling)
  - Material UI (for pre-built components and UI consistency)

- **Backend:**  
  - Node.js (for server-side logic)
  - Express.js (for building RESTful API)
  - JWT (for secure user authentication)
  - bcryptjs (for hashing passwords)

- **Database:**  
  - MongoDB (for a scalable, NoSQL database)
  - Mongoose (for object data modeling)

- **Cloud & Deployment:**  
  - Vercel (for hosting the frontend)
  - MongoDB Atlas (for database hosting)
  - Render/Heroku (for backend deployment)
  - AWS

---

## 🏁 **Getting Started**

### Prerequisites

To get this project up and running locally on your machine, you will need the following:

- **Node.js** and **npm** installed
- **MongoDB Atlas** account or local MongoDB setup

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/home-rentals-app.git
   cd home-rentals-app

   ```bash
   cd client
   npm install
   npm start

   ```bash
   cd server
   npm install
   npm start

## Environment Variables:

Create a .env file in both the server and client folders to configure the necessary environment variables.
Sample:

### Backend:

JWT_SECRET=your_jwt_secret

MONGO_URI=your_mongodb_connection_string

### Frontend:

REACT_APP_API_URL=http://localhost:5000 (or the deployed API URL)

## 🎯 Features
User Registration & Login: Secure authentication with JWT and bcryptjs for password hashing.

Property Listings: Users can browse and filter properties.

Property Management: Admins can add, edit, or delete property listings.

Image Upload: Property images are handled with Multer, allowing users to upload property images.

Responsive Design: Built using Material UI and SCSS for a mobile-friendly user experience.

## 💡 Future Improvements
Add user reviews and ratings for properties.

Implement real-time messaging for users to contact property owners.

Integrate payment gateway for booking rentals.

## 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
