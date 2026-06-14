Chatty
Chatty is a real-time chat application built with a modern tech stack, designed for smooth and instant communication. It allows users to sign up, log in, and start chatting with others instantly. The app supports real-time messaging, typing indicators, and user presence status to make conversations feel more interactive and alive.

Features
🔹 Real-time Messaging – Messages are delivered instantly without page refresh.

🔹 User Authentication – Secure sign-up and login with password encryption.

🔹 Typing Indicators – See when someone is typing a message.

🔹 Online/Offline Status – Know which users are active.

🔹 Responsive UI – Works seamlessly on desktop and mobile.

Tech Stack
Frontend: React.js, Tailwind CSS 
Backend: Node.js, Express.js
Real-time Engine: Socket.io
Database: MongoDB (Mongoose)

Installation
Clone the repository

bash
Copy code
git clone https://github.com/yourusername/chatty.git
Navigate to the project directory

bash
Copy code
cd chatty/chaty
Install dependencies for backend

bash
Copy code
cd backend
npm install
Install dependencies for frontend

bash
Copy code
cd ../frontend
npm install
Run the backend server

bash
Copy code
npm start
Run the frontend app

bash
Copy code
npm run dev
How It Works
The frontend connects to the backend using Socket.io for real-time communication.

When a user sends a message, it’s instantly broadcasted to the recipient(s).

The backend stores chat history in MongoDB for persistence.

Future Improvements
Group chats

Message reactions

File sharing (images, docs, etc.)
