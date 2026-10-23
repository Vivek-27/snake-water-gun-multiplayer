# 🎮 Real-Time Multiplayer Snake Water Gun Game

[![Node.js](https://img.shields.io/badge/Node.js-18+-339933?style=flat-square&logo=node.js&logoColor=white)](https://nodejs.org)
[![Express](https://img.shields.io/badge/Express-4.18-000000?style=flat-square&logo=express&logoColor=white)](https://expressjs.com)
[![Socket.IO](https://img.shields.io/badge/Socket.IO-v4-010101?style=flat-square&logo=socket.io&logoColor=white)](https://socket.io)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org)

A real-time multiplayer web implementation of the classic Indian variant of Rock-Paper-Scissors (**Snake, Water, Gun**). Built with **Node.js, Express, and Socket.IO WebSockets**, enabling strangers or friends to match into live rooms, make simultaneous moves, and view immediate game results with score tracking.

---

## 🕹️ Game Rules

| Choice | Defeats | Defeated By | Real-world Logic |
| :--- | :--- | :--- | :--- |
| **🐍 Snake** | 💧 Water | 🔫 Gun | Snake drinks water; Gun shoots snake |
| **💧 Water** | 🔫 Gun | 🐍 Snake | Water rusts / douses gun; Snake drinks water |
| **🔫 Gun** | 🐍 Snake | 💧 Water | Gun shoots snake; Water douses gun |

---

## 🌟 Key Features

- ⚡ **Real-Time Matchmaking:** Players connect via WebSockets and are paired into game lobbies.
- 🔄 **Turn Synchronization:** Simultaneous hidden choice locking to prevent cheating or premature reveals.
- 🏆 **Scoreboard & Game Loops:** Live round-by-round point tallies with rematch capabilities.
- 📡 **Instant State Broadcasts:** Low-latency bi-directional messaging handled by Socket.IO.

---

## ⚡ Quick Start

```bash
# Clone the repository
git clone https://github.com/Vivek-27/Snake_Water_Gun.git
cd Snake_Water_Gun

# Install dependencies
npm install

# Start the game server
npm start
```

Open your browser to: `http://localhost:3000` (or configured port). Open two separate browser tabs to play against each other locally!
