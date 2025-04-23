ChatApp
ChatApp is a real-time messaging application designed to facilitate seamless communication between users. Built with the MERN stack (MongoDB, Express.js, React.js, Node.js) and powered by Socket.IO, it offers both global and private chat functionalities with real-time updates.

🌟 Features
User Authentication: Secure login and registration using JWT tokens.

Global Chat Room: Engage in conversations with all online users.

Private Messaging: One-on-one chats with other registered users.

Real-Time Communication: Instant message delivery and updates using Socket.IO.

Responsive Design: Optimized for both desktop and mobile devices.

🛠️ Technologies Used
Frontend: React.js, Material-UI

Backend: Node.js, Express.js

Database: MongoDB with Mongoose

Real-Time Communication: Socket.IO

Authentication: JSON Web Tokens (JWT)

🚀 Getting Started
Follow these steps to set up and run the application locally.

Prerequisites
Node.js and npm installed on your machine.

MongoDB installed and running locally.

Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/tshepang98/chatApp.git
cd chatApp
Install backend dependencies:

bash
Copy
Edit
npm install
Install frontend dependencies:

bash
Copy
Edit
npm run client-install
Configure Environment Variables:

Create a .env file in the root directory and add the following:

env
Copy
Edit
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
Replace your_mongodb_connection_string with your actual MongoDB connection string and your_jwt_secret with a secure secret key for JWT.

Start the application:

bash
Copy
Edit
npm run dev
This command will concurrently run both the backend server and the React frontend.

Access the application:

Open your browser and navigate to http://localhost:3000 to use the ChatApp.
