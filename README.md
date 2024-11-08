# Real-Time Chat Application

This is a real-time chat application built using **Node.js** (backend), **Socket.io** (for WebSocket connections), and **React.js** (frontend). The application allows users to join a chat room, send messages, and receive messages in real time.

---

## Features

- **Real-Time Messaging**: Users can send and receive messages instantly using WebSocket technology.
- **Multiple Rooms**: Create or join different chat rooms for topic-based discussions.
- **Responsive Design**: Fully responsive UI for mobile and desktop users.
- **Message History**: Displays message history for each chat room.

## Tech Stack

- **Frontend**: React.js, Tailwind CSS 
- **Backend**: Node.js, Express
- **WebSocket**: Socket.io
- **Database**: MongoDB

## Setup Instructions

### Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/real-time-chat-app.git
   cd real-time-chat-app
   ```

2. **Install Backend Dependencies**
   ```bash
   cd server
   npm install
   ```

3. **Install Frontend Dependencies**
   ```bash
   cd ../client
   npm install
   ```

### Running the Application

1. **Start the Backend Server**
   ```bash
   cd server
   npm run dev
   ```
   The backend server should now be running on `http://localhost:8747`.

2. **Start the Frontend**
   ```bash
   cd ../client
   npm run dev
   ```
   The frontend should now be running on `http://localhost:5173`.

## Usage

1. Open `http://localhost:5173` in a web browser.
2. Enter a username and choose a room to join.
3. Start chatting in real time with others in the same room.


## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a feature branch.
3. Make your changes.
4. Submit a pull request.

---

Feel free to contribute, suggest features, or open issues. Happy chatting!

---
