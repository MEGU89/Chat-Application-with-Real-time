# Real-Time Chat Application

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)  
![License](https://img.shields.io/badge/license-MIT-blue)  
![Tech Stack](https://img.shields.io/badge/stack-React.js%20|%20Node.js%20|%20Socket.IO%20|%20MongoDB-orange)

A secure and efficient chat platform with **real-time messaging**, **user authentication**, and features such as **message encryption**, **read receipts**, and **online status indicators**.

---

## Features

- **Real-Time Messaging**: Powered by WebSockets (Socket.IO).  
- **One-on-One & Group Chats**: Switch seamlessly between private and group chats.  
- **User Authentication**: Secure login using JWT.  
- **Message Encryption**: Keeps conversations private.  
- **Read Receipts & Online Status**: Real-time activity tracking.

---

## Tech Stack

- **Frontend**: React.js  
- **Backend**: Node.js, Express  
- **Real-Time Communication**: Socket.IO  
- **Database**: MongoDB  

---

## Architecture Overview

```plaintext
Client (React.js)  <->  Socket.IO/WebSocket  <->  Server (Node.js/Express)
                                           |
                                           v
                                      MongoDB Database
```

---

## Screenshots

### Login Screen
![Login Screen](./screenshots/login.png)

### Chat Interface
![Chat Interface](./screenshots/chat-interface.png)

---

## Installation & Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/MEGU89/Chat-Application-with-Real-time.git
   cd Chat-Application-with-Real-time
   ```

2. **Install Dependencies**
   ```bash
   # Server
   cd server
   npm install

   # Client
   cd ../client
   npm install
   ```

3. **Set Environment Variables**
   ```
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```

4. **Run the Application**
   ```bash
   # Start backend
   cd server
   npm run dev

   # Start frontend
   cd client
   npm start
   ```

---

## Usage

- Register or log in  
- Start one-on-one or group conversations  
- View online users and read receipts in real-time  

---

## Future Enhancements

- File sharing (images, documents)  
- Push notifications  
- Voice & video calls  
- Dark/light theme  

---

## Contributing

1. Fork this repository  
2. Create a branch: `git checkout -b feature/your-feature-name`  
3. Commit your changes: `git commit -m "Add feature"`  
4. Push: `git push origin feature/your-feature-name`  
5. Open a pull request  

---

## License

This project is licensed under the **MIT License**.
