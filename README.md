# SocketChat

A simple **real-time chat application** built using **Node.js**, **Socket.IO**, and **Vanilla JavaScript**. Users can join the chat, send messages, and see when other users connect or disconnect.

## Features

- Real-time chat between multiple users
- User join and leave notifications
- Simple, responsive UI
- Easy to set up and run locally
- No database required (all in-memory)

## Tech Stack

- **Backend:** Node.js, Socket.IO
- **Frontend:** HTML, CSS, Vanilla JavaScript
- **Communication:** WebSockets via Socket.IO

## Installation

1. Clone the repository:
```
git clone https://github.com/your-username/chat-app.git
cd chat-app
```
2. Install dependencies:
```
npm install socket.io
```
3. Start the server:
```
node index.js
```
By default, the server will run on **port 4000**.
4. Open `index.html` in your browser.

## Usage

1. Enter your name when prompted.
2. Send messages and chat with other users in real-time.
3. Notifications appear when users join or leave.

## File Structure

```
chat-app/
│
├── index.js          # Backend Node.js + Socket.IO server
├── index.html        # Frontend HTML file
├── script.js         # Frontend JavaScript for handling socket events
└── README.md         # Project documentation
```
