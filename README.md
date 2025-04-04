
# ChatPort - Real-Time Chat Application

ChatPort is a real-time chat application built with modern web technologies. The project was developed as a self-learning endeavor to explore real-time communication, user authentication, and database management.

## Project Overview

- **Objective**: To create a chat application with an integrated socket.io module to enable seamless real-time communication.
- **Timeframe**: June 2023 - July 2023
- **Deployment**: The project is live at [ChatPort on Render](https://chatportapp.onrender.com)

## Features

- **User Authentication**: Implemented functionalities for user login, logout, and registration.
- **Real-Time Communication**: Integrated socket.io to facilitate real-time messaging between users.
- **Emoji Support**: Added a comprehensive emoji feature to enhance the chat experience.
- **Data Management**: Utilized MongoDB to store chat messages, user information, and profile pictures efficiently.
- **Intuitive UI**: Designed an engaging and user-friendly interface using HTML, styled components, and React JS.

## Project Structure

\`\`\`
.
│   index.js                    # Entry point of the application
│   package-lock.json           # Auto-generated file for npm dependencies
│   package.json                # Lists project dependencies and scripts
│   
├───build                       # Contains the production build of the front-end
│   │   asset-manifest.json
│   │   index.html              # Main HTML file for the front-end
│   │   logo.png
│   │
│   └───static                  # Static assets used by the front-end
│       ├───css
│       │       main.6af9cb51.css
│       │       main.6af9cb51.css.map
│       │
│       ├───js
│       │       main.07ba3a04.js
│       │       main.07ba3a04.js.LICENSE.txt
│       │       main.07ba3a04.js.map
│       │
│       └───media               # Media assets (images, gifs) used in the app
│               loader.d0c1692cd7dd38f5e503.gif
│               logo.6fc3cbbd02ca7a9e1bef.png
│               robot.065284e779819c075e3c.gif
│               setAvatarbg.8a4770c70f1f39282aae.jpg
│               techbg.391c640d3f92fe1f1204.jpg
│
├───controllers                 # Handles the logic for user and message management
│       messageController.js
│       userController.js
│
├───models                      # Defines the data models for MongoDB
│       messageModel.js
│       userModel.js
│
└───routes                      # Defines the API routes for authentication and messaging
        auth.js
        messages.js
\`\`\`

## Installation and Setup

To run this project locally:

1. Clone the repository:
   \`\`\`bash
   git clone https://github.com/your-username/chatport.git
   cd chatport
   \`\`\`

2. Install dependencies:
   \`\`\`bash
   npm install
   \`\`\`

3. Create a \`.env\` file in the root directory and add your MongoDB URI and other necessary environment variables:
   \`\`\`
   MONGODB_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
   \`\`\`

4. Start the application:
   \`\`\`bash
   npm start
   \`\`\`

5. Open your browser and navigate to \`http://localhost:3000\`.

## Usage

- Register a new account or log in with an existing account.
- Start a chat by selecting a user from the list.
- Use the emoji picker to add emojis to your messages.
- View and update your profile, including changing your profile picture.

## Technologies Used

- **Front-End**: React JS, HTML, CSS (styled components)
- **Back-End**: Node.js, Express.js
- **Database**: MongoDB
- **Real-Time Communication**: Socket.io
- **Deployment**: Render


