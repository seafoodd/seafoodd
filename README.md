# 👋 Hi, I'm seafood
I'm a middle full-stack developer who enjoys turning ideas into solid, scalable apps — with a focus on clean architecture and real-time systems.

## 💻 Tech Stack
- **Frontend:** Next.js, React, Tailwind, Sass
- **Backend:** NestJS, Express.js, WebSockets, Redis, MongoDB, PostgreSQL
- **DevOps:** Docker, CI/CD, NGINX, AWS, DigitalOcean

## 🧠 Interests
- Architecting scalable web applications
- Creating real-time multiplayer games (e.g. [ultiTTT](https://ultittt.org))
- Automation and utility scripting

## 📦 Projects
### 🎮 [ultiTTT](https://ultittt.org) — competitive real-time Ultimate Tic Tac Toe
A fully custom-built implementation of Ultimate Tic Tac Toe, designed for competitive 1v1 play.
**Tech Overview:**
- **Frontend:**
  - Built with **Next.js** + **Tailwind CSS**
  - Uses **WebSockets** for real-time game state updates
  - Clean, minimal UI focused on speed, clarity, and responsiveness

- **Backend:**
  - Built with **NestJS** (modular structure, feature-based)
  - **Redis** for real-time game state storage
  - **MongoDB** for persistent storage of finished matches and accounts
  - Stateless architecture — all active games live in Redis, not in the database

- **Realtime:**  
  - Uses **socket.io** for bi-directional communication  
  - Each move is validated server-side before being broadcasted  
  - Handles edge cases like disconnects, invalid moves, game timeouts

- **Infrastructure:**  
  - Containerized with **Docker**
  - Fully automated CI/CD pipelines
  - Automatic database backups

## 🧪 Currently Exploring
- Structuring codebases with **clean module design** (especially with NestJS)
- Building PWA apps with service workers
- Studying system design, algorithms, and writing solid backend logic

## 🗂️ Contact & Links
- Telegram: [@seafood_dev](https://t.me/seafood_dev)  
- Discord: `seafood__`
- LinkedIn: [@seafood_dev](https://www.linkedin.com/in/seafood-dev/)
- GitHub: [@seafood](https://github.com/seafoodd)

---

Feel free to reach out or check out my work — I'm always building something new.
