# Real-Time Cursor Tracker

Real-Time Cursor Tracker is a Node.js application that demonstrates the power of WebSockets for live communication between a server and clients. Using Express.js for the backend and native WebSockets on the front end, this project captures mouse cursor movements from users and broadcasts them to all connected clients, allowing for the real-time tracking of multiple cursors across different browsers.

## Features

- Real-time broadcasting of cursor positions to multiple clients
- Lightweight Express.js server setup
- Easy to understand client-side JavaScript for capturing and displaying cursor movements

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (https://nodejs.org/)

### Installing

Clone the repository to your local machine:

```bash
git clone https://github.com/incrosnatubogdan/yonder-web-cluster-websockets.git
cd real-time-cursor-tracker
```

Install the necessary dependencies:

```bash
npm i
cd api
npm i
```

Start the server:

```bash
npm start
```

The server should now be running on [http://localhost:8081](http://localhost:8081). Open this address in multiple browsers or tabs to test the real-time cursor tracking.

## Usage

Move your mouse around the browser window. Your cursor's position is broadcasted to all other connected clients in real-time, allowing you to see all cursors moving in the window.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Online testing environment

# ws://web-cluster-websockets.adaptable.app/