![Screenshot 2024-10-20 182446](https://github.com/user-attachments/assets/4e2b6433-f550-4c38-a2e1-f7b057132d37)


Barath Chat Application
A simple real-time chat application built using HTML, CSS, JavaScript, Node.js, and Socket.IO. This chat room allows multiple users to communicate in real-time with an interactive user interface.

Overview
This project demonstrates a basic implementation of a chat application using the following technologies:

HTML & CSS: For structuring and styling the user interface.
JavaScript (Client-side): For handling form submissions and interacting with the server through WebSockets.
Node.js: As the server-side platform to handle socket connections and serve the static files.
Socket.IO: For enabling real-time, bidirectional communication between the server and clients.
Features
Real-time messaging between multiple users.
User-friendly interface with a message display area.
Automatic updates for all connected clients when a new message is sent.
Getting Started
Follow these steps to set up and run the project locally:

Prerequisites
Ensure you have the following installed:

Node.js (v12 or higher)
npm (Node package manager, typically installed with Node.js)


Steps to create the application:

Step 1: Create a new directory for your project and navigate to it using the command line.

mkdir real-time-chat-app
Step 2: Navigate to the project directory.

cd real-time-chat-app
Step 3: Initialize a new Node.js project by Run the following command in the project directory to create a new package.json file:

npm init -y
Step 4: Install the required dependencies by Install Socket.IO packages by running the following command:

npm install socket.io
Step 5: Create the following files index.js, index.html, style.css

Running the Application
Start the Server:
bash
Copy code
node index.js
Access the Chat Application:
Open your browser and go to http://localhost:3000.

Usage
Enter your name and message in the input fields and click "Send Message."
Messages will be displayed in the chat area and visible to all connected users.
Project Structure
bash
Copy code
barath-chat-application/
│
├── index.html       # HTML file for the front-end interface
├── style.css        # CSS file for styling the chatroom
├── index.js         # Node.js server file handling socket communication
├── package.json     # Project configuration and dependencies
└── README.md        # Documentation of the project
