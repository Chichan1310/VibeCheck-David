# VibeCheck-David

VibeCheck-David is a app that interacts with a Node.js backend to deliver fortunes, jokes, mood vibes, and a “SMASH” counter. It’s designed for learning frontend-backend communication using APIs.

Features

🔮 Fortune – Get a random developer-friendly fortune.

😂 Joke – Receive a random programming joke.

😄🥱😵‍💫 Mood Vibes – Choose a mood to get a motivational message.

💥 SMASH! – Increment a counter to track “smashes.”

🕵️ Secret – Unlock a hidden message using a secret code.    

Folder Structure
.
├── backend/
│   ├── index.js         # Node.js backend API
│   ├── package.json     # Backend dependencies
│   └── package-lock.json
├── frontend/
│   ├── index.html       # Frontend page
│   └── app.js           # Frontend JS for button handling
├── .gitignore
└── README.md

Getting Started

Prerequisites
Node.js 
npm 

Setup
1. Backend

cd backend
npm install
node index.js

The backend server will run at http://localhost:3000

2. Frontend

Open frontend/index.html in your browser. The page will call the backend API to fetch data.

API Endpoints
Method	Endpoint	Description
GET	/api/fortune	Returns a random fortune
GET	/api/joke	Returns a random joke
GET	/api/vibe?mood=...	Returns a mood-based message
POST	/api/smash	Increments SMASH counter
GET	/api/smashes	Returns current SMASH count
GET	/api/secret?code=...	Returns a secret message if code is correct
Usage

Start the backend server.

Open frontend/index.html in your browser.

Click buttons to see API responses in the output area.