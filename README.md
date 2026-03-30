# Casino System

A full-featured online casino system with backend API, frontend interface, real-time games, analytics, and admin management. Built with **Node.js**, **Express**, **MongoDB**, and **React**.

---

## Features

### Player Features
- User registration & login (JWT authentication)
- Deposit, withdraw, and wallet management
- Real-time casino games:
  - Slot machines
  - Roulette
  - Blackjack
- Multi-line payline system
- Progressive jackpot with animations
- Leaderboards & stats
- Responsive and mobile-friendly design

### Admin Features
- Dashboard with analytics & user stats
- Game management (RTP, house edge, jackpots)
- User management (ban, credit, role)
- Transaction monitoring
- Real-time game session monitoring

### Tech Stack
- **Backend**: Node.js, Express.js, MongoDB, Mongoose
- **Frontend**: React, Redux, Tailwind CSS
- **Authentication**: JWT, bcrypt
- **Realtime**: Socket.io for multiplayer game updates
- **Deployment**: Docker-ready, can run on VPS or cloud servers
- **Testing**: Jest (backend), React Testing Library (frontend)

---

## Installation

### Prerequisites
- Node.js >= 18
- MongoDB >= 6
- npm or yarn
- Docker (optional, for containerized deployment)

### Setup Backend
```bash
cd backend
npm install
cp .env.example .env
# edit .env with your MongoDB URI and JWT secret
npm run dev
