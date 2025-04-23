ChatApp
=======

ChatApp is a real-time messaging application designed to facilitate seamless communication between users. Built with the MERN stack (MongoDB, Express.js, React.js, Node.js) and powered by Socket.IO, it offers both global and private chat functionalities with real-time updates.

Features
--------

- User Authentication: Secure login and registration using JWT tokens.
- Global Chat Room: Engage in conversations with all online users.
- Private Messaging: One-on-one chats with other registered users.
- Real-Time Communication: Instant message delivery and updates using Socket.IO.
- Responsive Design: Optimized for both desktop and mobile devices.

Technologies Used
-----------------

- Frontend: React.js, Material-UI
- Backend: Node.js, Express.js
- Database: MongoDB with Mongoose
- Real-Time Communication: Socket.IO
- Authentication: JSON Web Tokens (JWT)

Getting Started
---------------

Follow these steps to set up and run the application locally.

Prerequisites
-------------

- Node.js and npm installed on your machine.
- MongoDB installed and running locally.

Installation
------------

1. Clone the repository:

   git clone https://github.com/tshepang98/chatApp.git
   cd chatApp

2. Install backend dependencies:

   npm install

3. Install frontend dependencies:

   cd client
   npm install
   cd ..

4. Configure Environment Variables:

   Create a `.env` file in the root directory and add the following:

   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret

   Replace `your_mongodb_connection_string` with your actual MongoDB connection string and `your_jwt_secret` with a secure secret key for JWT.

5. Build the React frontend:

   npm run build-client

6. Start the application:

   node server.js

   This command will start the backend server and serve the React frontend.

7. Access the application:

   Open your browser and navigate to `http://localhost:5000` to use the ChatApp.


Contributing
------------

Contributions are welcome!

1. Fork the repository
2. Create a new branch:

   git checkout -b feature/your-feature

3. Make your changes and commit:

   git commit -m "Add your message"

4. Push to your branch:

   git push origin feature/your-feature

5. Submit a pull request

Contact
-------

Created by [@tshepang98](https://github.com/tshepang98) – feel free to reach out for questions, ideas, or collaboration!
