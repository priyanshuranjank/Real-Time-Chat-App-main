# Real-Time Chat App

## Overview
The Real-Time Chat App is a web-based application that enables users to communicate in real-time through instant messaging. This application leverages WebSockets for real-time communication and is built using modern web development technologies.

## Features
- **Real-Time Messaging:** Instant message exchange without the need to refresh the page.
- **User Authentication:** Secure user registration and login.
- **Chat Rooms:** Users can create and join different chat rooms.
- **User Presence:** See online status of users.
- **Responsive Design:** Works seamlessly on both desktop and mobile devices.

## Technologies Used
- **Frontend:**
  - HTML, CSS, JavaScript
  - React.js
- **Backend:**
  - Node.js
  - Express.js
  - WebSocket (Socket.IO)
- **Database:**
  - MongoDB
- **Authentication:**
  - JWT (JSON Web Tokens)
- **Other:**
  - Docker for containerization

## Getting Started

### Prerequisites
- Node.js (v14 or later)
- MongoDB
- Docker (optional, for containerization)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Girjesh-Dhodaria/real-time-chat-app.git
   cd real-time-chat-app
   ```

2. **Install backend dependencies:**
   ```bash
   cd server
   npm install
   ```

3. **Install frontend dependencies:**
   ```bash
   cd ../client
   npm install
   ```

### Running the Application

1. **Start MongoDB:**
   Make sure MongoDB is running on your local machine. If using Docker, you can run:
   ```bash
   docker run -d -p 27017:27017 --name mongodb mongo
   ```

2. **Configure Environment Variables:**
   Create a `.env` file in the `server` directory and add the following:
   ```env
   PORT=5000
   MONGODB_URI=mongodb://localhost:27017/chatapp
   JWT_SECRET=your_secret_key
   ```

3. **Start the Backend Server:**
   ```bash
   cd server
   npm start
   ```

4. **Start the Frontend Development Server:**
   ```bash
   cd ../client
   npm start
   ```

5. **Access the Application:**
   Open your web browser and navigate to `http://localhost:3000`.

## Project Structure
```plaintext
real-time-chat-app/
├── client/          # Frontend React application
├── server/          # Backend Node.js application
├── README.md        # Project documentation
└── .gitignore       # Git ignore file
```

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- [Socket.IO](https://socket.io/)
- [React](https://reactjs.org/)
- [Express](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)

---

Feel free to reach out if you have any questions or need further assistance. Enjoy building and happy coding!
