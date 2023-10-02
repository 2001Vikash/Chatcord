# Real-Time Chat Application with Multiple Rooms

This GitHub repository contains the source code and documentation for a real-time chat application with multiple rooms. This application allows users to join different chat rooms and communicate with each other in real-time. It is built using cutting-edge web technologies and is designed to be easy to set up and use.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Features

- Real-time chat functionality.
- Multiple chat rooms with the ability to create new rooms.
- Notification system for new messages.

## Technologies Used

- **Node.js**: Server-side JavaScript runtime.
- **Express.js**: Web application framework for Node.js.
- **Socket.io**: Real-time communication library.
- **HTML,CSS,Js**: For the Designing.

## Getting Started

Follow these instructions to set up and run the chat application locally.

### Prerequisites

- Node.js and npm installed on your machine.

### Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/real-time-chat-app.git
   cd real-time-chat-app
   ```

2. Install server dependencies:

   ```bash
   cd server
   npm install
   ```

3. Create a `.env` file in the `server` directory and configure the following variables:

   ```
   PORT= 3000
   ```

4. Install client dependencies:

   ```bash
   cd ../client
   npm install
   ```

5. Start the server and client development environments:

   ```bash
   # In the 'server' directory
   npm start

   # In the 'client' directory
   npm run dev
   ```

6. Visit `http://localhost:3000` in your browser to access the chat application.

## Usage

- Register and log in to the chat application.
- Join existing chat rooms or create new ones.
- Start chatting with other users in real-time.

## Contributing

Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on how to contribute to this project.
