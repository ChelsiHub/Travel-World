🌍 Tours and Travels – MERN Web Application

A complete travel booking and trip-planning platform built using the MERN Stack.




📝 Overview

Tours and Travels is a full-stack web application designed to simplify booking, planning, and managing travel experiences.
Users can browse tour packages, customize travel plans, book trips securely, and manage their itineraries — all in one place.

This project demonstrates end-to-end MERN development, including authentication, APIs, UI design, and database integration.




🚀 Live Demo

(Add your deployment link when ready)
👉 Live URL: https://your-live-site-link.com

📸 Screenshots

(Add images later — example placeholder)

![Homepage](./screenshots/homepage.png)
![Booking Page](./screenshots/booking.png)
![User Dashboard](./screenshots/dashboard.png)




✨ Key Features
🔐 User Features

User Registration & Login (JWT Authentication)
Browse travel packages
View package details
Search and filter for tours
Custom travel plan creation
Book tours securely
Manage bookings
User profile management

🛠 Admin Features
Admin login
Add, update, delete tour packages
Manage user bookings
View all users
Dashboard for analytics (optional if implemented)

🧭 General Features
Fully responsive UI
Clean user experience
REST API backend
Protected routes
MongoDB for data storage




🛠 Tech Stack

Frontend
React.js
React Router
Axios
CSS / Material UI / Tailwind (based on your project)

Backend
Node.js
Express.js
MongoDB + Mongoose
JWT Authentication
Bcrypt for password hashing

Other Tools
Postman (API testing)
Git & GitHub
VS Code




📦 Project Structure
Tours-and-Travels-MERN/
 ├── client/           # Frontend (React)
 │   ├── public/
 │   ├── src/
 │   ├── package.json
 ├── server/           # Backend (Node + Express)
 │   ├── controllers/
 │   ├── models/
 │   ├── routes/
 │   ├── config/
 │   ├── server.js
 │   ├── package.json
 ├── README.md
 └── .env




⚙️ Installation & Setup
1. Clone the Repository
git clone https://github.com/YourUsername/Tours-and-Travels-MERN.git

2. Move into the project
cd Tours-and-Travels-MERN

Backend Setup
cd server
npm install


Create a .env file:

MONGO_URI=your-mongodb-connection-string
JWT_SECRET=your-secret
PORT=5000


Start backend:

npm start

Frontend Setup
cd client
npm install
npm start


Frontend will run on:
👉 http://localhost:3000

Backend will run on:
👉 http://localhost:5000




🧪 API Testing

All APIs can be tested using Postman or any REST client.
You can create a folder containing:

Auth APIs
Booking APIs
Tour Package APIs




🔐 Authentication

Uses JWT for generating secure tokens
Protected routes for user & admin
Password encryption using bcrypt




🎯 What This Project Demonstrates

✔ Full MERN stack development
✔ REST API design
✔ State management and React hooks
✔ Authentication & authorization
✔ Database schema design
✔ Clean frontend UI
✔ CRUD operations
✔ Error handling and validation




🙋‍♀️ Author

Chelsi Patoliya
🌐 GitHub: https://github.com/ChelsiHub