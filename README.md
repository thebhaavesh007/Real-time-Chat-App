# Real-time-Chat-App
Basic real time chat application with;
* Node.js 
* socket.io
* ExpressJS

This is a real-time chat application built with Node.js, Express.js, and Socket.io. It allows users to join chat rooms and communicate with each other in real-time.

## Features

- **Real-time Communication**: Messages are sent and received instantly, providing a seamless chatting experience.
- **Multiple Chat Rooms**: Users can join existing chat rooms or create their own, allowing for flexible communication channels.
- **User Authentication**: Optionally, you can implement user authentication to ensure secure access to the chat rooms.
- **Simple Interface**: The interface is designed to be intuitive and easy to use, making it accessible for users of all levels.

## Installation

1. **Clone this repository** to your local machine:

   git clone https://github.com/your-username/real-time-chat-app.git
Navigate to the project directory:

cd real-time-chat-app
Install dependencies:

npm install
Start the server:

npm start
Access the application in your web browser at http://localhost:3000.

## Usage
Upon accessing the application, users can choose to create a new chat room or join an existing one.
Once inside a chat room, users can send messages which will be instantly displayed to all other users in the same chat room.
Users can leave the chat room or close the browser window to exit the application.
## Configuration
Port: By default, the server runs on port 3000. You can change this port by modifying the PORT variable in the .env file.
## Dependencies
Express.js: Minimal and flexible Node.js web application framework.
Socket.io: Enables real-time, bidirectional and event-based communication between web clients and servers.
dotenv: Loads environment variables from a .env file into process.env.
## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests to contribute to this project.

## License
This project is licensed under the Apache License 2.0.
