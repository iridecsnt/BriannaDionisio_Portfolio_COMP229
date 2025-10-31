# BriannaDionisio_Portfolio_COMP229

Student: Brianna Dionisio
STUDENT ID: 301468985

OVERVIEW:

This project is a full stack MERN portfolio application.
It includes a backend using Node.js, Express, and MongoDB Atlas, and a frontend built with React (Vite).
The backend handles CRUD operations for four main collections — contacts, projects, qualifications, and users — and includes JWT authentication for login and protected routes.

SETUP:

Install dependencies:

npm install
cd client
npm install


Create a .env file in the project root:

MONGO_URI=your_atlas_connection_string
JWT_SECRET=your_secret_key


Run the backend:

node server.js


→ open http://localhost:5000/
 to confirm the server is running.

Run both frontend and backend together:

cd client
npm run dev


Frontend: http://localhost:5173/

Backend: http://localhost:5000/

API ENDPOINTS:

Contacts / Projects / Qualifications / Users

GET     /api/<resource>
GET     /api/<resource>/:id
POST    /api/<resource>
PUT     /api/<resource>/:id
DELETE  /api/<resource>/:id
DELETE  /api/<resource>


Authentication

POST  /api/auth/signin      → Login and receive JWT
GET   /api/auth/signout     → Logout
GET   /api/secure/profile   → Access protected route (requires Bearer token)

TOOLS & TECHNOLOGIES:

- Node.js + Express
- MongoDB Atlas + Mongoose
- React (Vite)
- JSON Web Token (JWT)
- Bcrypt (password hashing)
- Thunder Client (API testing)

