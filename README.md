🎮 Game Hub – AI & Multiplayer Games Platform
📌 Project Overview

Game Hub is a full-stack web application that brings together AI-based reinforcement learning games and multiplayer games under one unified platform.

The project demonstrates:

Reinforcement Learning concepts (Q-Learning, Policy Gradient)

Backend game logic using Flask

Modern frontend using React + TypeScript (Vite)

Clean frontend–backend separation

Real-time interaction and game state management

🧠 AI Games Included
Game	Description
CartPole	Policy Gradient (REINFORCE) agent trained on CartPole-v1
FrozenLake	Q-Learning agent with success-rate evaluation
GridWorld	Custom grid environment with Q-Learning (terminal logic + stats)

Each AI game runs on the backend and returns training results (episodes, rewards, success rate) to the frontend.

🎮 Multiplayer Games Included
Game	Modes
Chess ♟	Player vs Player, Player vs AI
Four in a Row (Connect-4)	Player vs Player, Player vs AI
Number Guessing Game	Player vs Player, Player vs AI

All multiplayer games feature:

Interactive UI

Game state maintained on backend

Frontend pages for gameplay

🧩 Tech Stack
🖥 Frontend

React + TypeScript

Vite

Tailwind CSS

React Router

Modern component-based UI

⚙ Backend

Python

Flask

Flask-CORS

Custom game engines

Reinforcement Learning logic

📁 Project Structure
GAME-HUB/
├── backend/
│   ├── app.py
│   └── games/
│       ├── cartpoleFinal.py
│       ├── frozenlakeFinal.py
│       ├── gridworldFinal.py
│       ├── chessmulti.py
│       ├── fourinarowmulti.py
│       └── numguessmulti.py
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── index.html
│   ├── package.json
│   ├── package-lock.json
│   └── vite.config.ts
│
└── README.md

▶️ How to Run the Project
1️⃣ Backend Setup (Flask)
cd backend
python app.py


Backend runs on:
http://127.0.0.1:5000

2️⃣ Frontend Setup (React)
cd frontend
npm install
npm run dev


Frontend runs on:
http://localhost:8080
 (or the port shown in terminal)

🎯 Game Flow

AI Games

Trigger backend training

Results displayed in frontend result pages

Multiplayer Games

Open frontend game pages

Interact with backend APIs for game logic

🔗 API Endpoints (Key)
AI Games
GET /play/cartpole
GET /play/frozenlake
GET /play/gridworld

Chess
POST /api/chess/state
POST /api/chess/player
POST /api/chess/agent

Four in a Row
GET  /api/connect4/state
POST /api/connect4/move
POST /api/connect4/reset
POST /api/connect4/mode

Number Guess
POST /api/numguess/ai
POST /api/numguess/user
POST /api/numguess/reset

🧪 Learning Outcomes

Practical implementation of Reinforcement Learning algorithms

Full-stack integration of AI systems

State management between frontend and backend

Clean modular code structure

Industry-style project organization

👥 Team Notes

Individual game logic contributed by team members

Backend unified into a single Flask application

Frontend redesigned into a unified Game Hub UI

All games integrated consistently

📌 Submission Notes

node_modules is intentionally excluded

Install dependencies using npm install

Python dependencies handled via system Python / virtual environment

Project tested locally on Windows

🏁 Final Note

This project demonstrates real-world AI + Web Development integration, making it suitable for:

College projects

Internships

Portfolio demonstration

Viva / evaluation
