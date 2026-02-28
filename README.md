✨ Full-Stack Interview Platform

A modern real-time coding interview platform that replicates a real technical interview environment with live coding, video communication, and automated evaluation.

🚀 Features

🧑‍💻 VSCode-like online code editor

🔐 Authentication with Clerk

🎥 1-on-1 video interview rooms

💬 Real-time chat messaging

🖥️ Screen sharing & recording

🔊 Mic & camera toggle

⚙️ Secure code execution environment

🎯 Automatic test-case evaluation

🎉 Success confetti & failure notifications

🧩 Practice problems (solo mode)

🔒 Room locking (max 2 participants)

🧠 Background jobs with Inngest

🧭 Dashboard with live stats

🏗️ Tech Stack
Frontend

React (Vite)

TanStack Query

Clerk Authentication

Stream Video SDK

Backend

Node.js

Express

MongoDB

Inngest

Dev Tools

Git & GitHub workflow

CodeRabbit PR analysis

Deployment on Sevalla

📂 Project Structure
.
├── backend
│   ├── src
│   └── package.json
├── frontend
│   ├── src
│   └── package.json
└── README.md
⚙️ Environment Variables
Backend (/backend/.env)
PORT=3000
NODE_ENV=development

DB_URL=your_mongodb_connection_url

INNGEST_EVENT_KEY=your_inngest_event_key
INNGEST_SIGNING_KEY=your_inngest_signing_key

STREAM_API_KEY=your_stream_api_key
STREAM_API_SECRET=your_stream_api_secret

CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

CLIENT_URL=http://localhost:5173
Frontend (/frontend/.env)
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
VITE_API_URL=http://localhost:3000/api
VITE_STREAM_API_KEY=your_stream_api_key
🧪 Running Locally
1️⃣ Clone the repository
git clone https://github.com/amann0007/TALENT-IQ
cd interview-platform
2️⃣ Run Backend
cd backend
npm install
npm run dev
3️⃣ Run Frontend
cd frontend
npm install
npm run dev
🧑‍💻 How It Works

Sign up or log in

Create or join an interview room

Collaborate via video & chat

Write and run code

Get instant feedback

📈 Future Improvements

AI interview feedback

Multi-participant rooms

Question bank CMS

Interview analytics dashboard

Code playback timeline

🤝 Contributing

Fork the repository

Create a feature branch

Commit your changes

Open a Pull Request

⭐ Support

If you like this project, please give it a ⭐ on GitHub!

📜 License

MIT License © 2026
