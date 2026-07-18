# Zerodha Clone

This is a **Zerodha Clone** project built using the **MERN Stack**. It is a simple stock trading platform that has a landing website, a trading dashboard, and a backend server. This project helped me learn full-stack web development and how frontend and backend work together.

## Features

### Landing Website

* Home Page
* About Page
* Products Page
* Pricing Page
* Support Page
* Signup Page
* Responsive Navbar and Footer

### Trading Dashboard

* Watchlist
* Holdings
* Positions
* Orders
* Funds
* Portfolio Summary
* Buy Window
* Portfolio Charts

### Backend

* REST API using Express.js
* MongoDB Database
* CRUD operations for Holdings, Positions, and Orders
* CORS Support
* Environment Variables using Dotenv

## Tech Stack

### Frontend

* React.js
* React Router DOM
* Material UI
* Axios

### Dashboard

* React.js
* Chart.js
* React ChartJS 2
* Material UI

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* CORS
* Dotenv

## Folder Structure

```text
Zerodha-main/
│
├── frontend/
│   └── Landing Website
│
├── dashboard/
│   └── Trading Dashboard
│
└── backend/
    ├── Server
    ├── Models
    └── API Routes
```

## Installation

### 1. Clone the Repository

```bash
git clone <repository-link>
cd Zerodha-main
```

### 2. Setup Backend

```bash
cd backend
npm install
npm start
```

### 3. Setup Frontend

```bash
cd frontend
npm install
npm start
```

### 4. Setup Dashboard

```bash
cd dashboard
npm install
npm start
```

## Environment Variables

Create a `.env` file inside the `backend` folder and add:

```env
MONGO_URL=your_mongodb_connection_string
PORT=3002
```

## What I Learned

* Building a full-stack web application
* Connecting React with Express APIs
* Using MongoDB with Mongoose
* Working with REST APIs
* Managing project structure in MERN Stack
* Creating a responsive user interface

## Future Improvements

* User Login and Authentication
* Real-time Stock Price Updates
* Better Portfolio Analytics
* Mobile Responsive Dashboard
* Dark Mode

## Note

This project is created for learning and educational purposes only. It is not connected to the official Zerodha platform.

## Author

**Himanshu Upadhyay**

B.Tech CSE Student
