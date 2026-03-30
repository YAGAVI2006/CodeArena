# CodeArena+

An AI-powered real-time coding platform built with the MERN stack.

## Tech Stack
- MongoDB, Express, React, Node.js
- Tailwind CSS, Monaco Editor
- Socket.io, Judge0 API, OpenAI API

## Installation

1. **Clone & Setup:**
```bash
git clone <repo-url>
cd CodeArena/
```

2. **Backend Setup:**
```bash
cd server
npm install
cp .env.example .env 
# Add your MongoDB URI, JWT Secret, RapidAPI Key (Judge0), and OpenAI API Key.
npm run dev
```

3. **Frontend Setup:**
```bash
cd ../client
npm install
npm run dev
```

## Features
- **User Authentication:** JWT based secure login.
- **Code Execution:** Compiles and runs Python, C, and Java code against test cases using Judge0.
- **AI Coach:** Integrates with OpenAI API to explain code, suggest logic fixes, and help debug errors.
- **Battle Mode (Basic):** Real-time 1v1 coding battle using Socket.io. First to submit passing code wins.
- **Global Leaderboard:** Track your points across the platform.

## Deployment Notes
- Frontend: Deploy `client/` to Vercel. Ensure build command is `npm run build` and publish dir is `dist`.
- Backend: Deploy `server/` to Render. Configure MongoDB Atlas as your database. Update `vite.config.js` proxy and Socket.io client URL to point to production backend.
