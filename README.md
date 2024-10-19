
<h1 align="center">Wave - Realtime Chat Application</h1>

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1ayaymd6awaESyaQ9WhC0aR--TN4UcYuC" alt="Wave - Realtime Chat Application" width="500"/>
</p>

Wave is a real-time chat application built using **Websockets**, **Express.js**, **Bootstrap**, and **HTML**. It provides features for 1-1 and group chat, allowing users to communicate in real-time with seamless interaction.

## Features
- **1-1 Chat**: Engage in private conversations with individual users.
- **Group Chat**: Create or join group chats to communicate with multiple users simultaneously.
- **Realtime Messaging**: Messages are delivered instantly using Websockets.
- **Responsive Design**: Built with Bootstrap for a responsive user interface across devices.

## Demo

- **[Watch the Working Video](https://drive.google.com/file/d/1vYo3FP3tjaFM3GWDrjxkYD_-2v5PjQPn/view?usp=sharing)**

## Built With
- [![Express.js](https://img.shields.io/badge/Express.js-4.x-orange.svg?style=rounded-square)](https://expressjs.com/en/starter/installing.html)
- [![Websockets](https://img.shields.io/badge/Websockets-Realtime-blue.svg?style=rounded-square)](https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API)
- [![Bootstrap](https://img.shields.io/badge/Bootstrap-5.x-purple.svg?style=rounded-square)](https://getbootstrap.com/)

## Requirements
1. [Node.js](https://nodejs.org/en/download/)
2. [Express.js](https://expressjs.com/en/starter/installing.html)
3. Web Browser (Chrome, Firefox, etc.)

## How to Run the App?
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/wave-realtime-chat.git
   ```
2. Install the necessary dependencies:
   ```bash
   npm install
   ```
3. Start the application:
   ```bash
   npm start
   ```
4. Open your browser and navigate to `localhost:3000` to start chatting in real-time!

## Usage
- **For 1-1 Chat**: Choose a user and start a private conversation.
- **For Group Chat**: Select a group or create a new one to begin chatting with multiple participants.
  
## Technologies Used
- **Node.js**: Server-side JavaScript runtime environment.
- **Express.js**: Web framework for Node.js to build the server-side logic.
- **Websockets**: Used for real-time communication between clients and the server.
- **Bootstrap**: For responsive, mobile-first web design.
- **HTML/CSS/JavaScript**: For building the user interface.

## Project Workflow
1. **Websockets** are used to establish a real-time connection between clients and the server.
2. Users can join rooms for **group chats** or start **1-1 chats**.
3. Messages are broadcasted in real-time across connected clients without refreshing the page.

## Future Improvements
- Adding file-sharing functionality.
- Implementing user notifications for new messages.
- Adding message encryption for enhanced security.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
