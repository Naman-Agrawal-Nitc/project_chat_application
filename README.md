# Real-Time Chat Application

A full-stack real-time messaging application built with React and Node.js, using Socket.IO for bidirectional communication between clients and the server.

## Tech Stack

- **Frontend:** React.js
- **Backend:** Node.js, Express.js
- **Real-Time Communication:** Socket.IO

## Overview

The application demonstrates real-time communication using WebSockets through Socket.IO. The client provides the user interface for sending and receiving messages, while the server handles communication between connected clients.

## Getting Started

### Prerequisites

- Node.js
- npm

### Installation

Clone the repository:

```bash
git clone https://github.com/Naman-Agrawal-Nitc/project_chat_application.git
cd project_chat_application
```

### Run the Application

Start the backend server in one terminal:

```bash
cd server
npm install
npm start
```

Start the frontend in another terminal:

```bash
cd client
npm install
npm start
```

If the frontend or backend uses a different startup command in its `package.json`, use the configured script instead.

## Key Concepts

- Real-time, bidirectional communication
- Socket.IO event-based messaging
- Client-server communication
- React frontend integration with a Node.js backend

## License

Refer to the repository for licensing information.
