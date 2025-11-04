Week 4: MERN Stack Blog Application

Overview
This is a full-stack blog application built with the MERN stack (MongoDB, Express.js, React.js, Node.js).
It demonstrates CRUD operations, RESTful API communication, and front-end state management with React and hooks.

Project Structure
week4-mern-assignment/
│
├── client/
│ ├── src/
│ ├── .env.example
│ ├── package.json
│ └── vite.config.js
│
├── server/
│ ├── models/
│ ├── routes/
│ ├── middleware/
│ ├── uploads/
│ ├── server.js
│ ├── package.json
│ └── .env.example
│
├── README.md
└── .gitignore

Setup Instructions

Requirements

Node.js v18 or higher

MongoDB (local or MongoDB Atlas)

npm or yarn

Step 1: Clone Repository
git clone <your-github-classroom-repo-url>
cd week4-mern-assignment

Step 2: Backend Setup
cd server
npm install
cp .env.example .env

Example .env file
PORT=5000
MONGODB_URI=mongodb://localhost:27017/mern_blog
JWT_SECRET=your_jwt_secret

Run backend
npm run dev

Step 3: Frontend Setup
cd ../client
npm install
cp .env.example .env

Example .env file
VITE_API_URL=http://localhost:5000/api

Run frontend
npm run dev

Application will run at http://localhost:5173

API Endpoints

Posts
GET /api/posts – Get all posts
GET /api/posts/:id – Get post by ID
POST /api/posts – Create post
PUT /api/posts/:id – Update post
DELETE /api/posts/:id – Delete post

Categories
GET /api/categories – Get all categories
POST /api/categories – Create new category

Authentication (optional)
POST /api/auth/register – Register new user
POST /api/auth/login – Login user and get token

Features

CRUD for posts and categories

MongoDB + Mongoose integration

RESTful API using Express

React + Vite + Tailwind CSS frontend

Axios for API communication

State management with hooks

Error handling and validation

Responsive UI

Advanced (optional)

JWT authentication

Image uploads using Multer

Pagination and search

Comments per post

Testing
Use Postman to test APIs.
Base URL: http://localhost:5000/api

Example: GET http://localhost:5000/api/posts

Screenshots
Add screenshots of your running app here.

Deployment

Backend (Render, Railway, or Heroku)

Initialize git

Commit code

Push to GitHub and connect repo to hosting service

Frontend (Vercel or Netlify)

Run npm run build

Deploy the dist folder

Update environment variables for production before deployment.

Author
Benard Mutuguti
Week 4 MERN Assignment – Full-Stack Blog Application
