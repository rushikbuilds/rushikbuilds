<h1 align="center">Hey there, I'm Rushikesh 👋</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1000&color=2D9CDB&center=true&vCenter=true&width=500&height=40&lines=Full-Stack+Developer;Systems+Programmer;AI+%26+ML+Developer" alt="Typing SVG" />
</p>

<p align="center">
  <strong>Build it fast. Make it scale. Keep it simple.</strong>
</p>

---

## GitHub Achievements

<p align="left">
  <img
    src="https://github.githubassets.com/images/modules/profile/achievements/yolo-default.png"
    width="100"
    alt="YOLO"
  />
  <img
    src="https://github.githubassets.com/images/modules/profile/achievements/pull-shark-default.png"
    width="100"
    alt="Pull Shark"
  />
</p>

---

## 🛠️ Tech Stack

### Languages
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

### Frontend
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)

### Backend & APIs
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![Spring Boot](https://img.shields.io/badge/springboot-000000?style=for-the-badge&logo=springboot&logoColor=green)

### Databases & Caching
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/postgresql-4169e1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4479A1?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)

### Systems & DevOps
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=for-the-badge&logo=socketdotio&logoColor=white)

### Networking & AI
![QUIC](https://img.shields.io/badge/QUIC-2D9CDB?style=for-the-badge&logoColor=white)
![aioquic](https://img.shields.io/badge/aioquic-6A5ACD?style=for-the-badge&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-ffffff?logo=langchain&logoColor=green)
![LangGraph](https://img.shields.io/badge/LangGraph-000000?style=flat&logo=python&logoColor=white)

---

## Featured Projects

### [SwiftTalk - Chat Messaging App](https://github.com/rushikbuilds/SwiftTalk-Chat-Messaging-App)
A real-time chat application with AI-powered enhancements.

- **Real-Time Messaging**: Instant delivery, typing indicators, read receipts, and online status via Socket.IO, with 1-on-1 chats, group chats (admin management), and media/file sharing.
- **Scalable Architecture**: Dedicated WebSocket server (`:3002`) decoupled from the REST API (`:3001`), horizontally scaled with `@socket.io/redis-adapter` and `@socket.io/redis-emitter`.
- **AI Assistance**: Smart replies, chat summarization, and message translation powered by Groq (LLaMA 3.3).
- **Auth & Security**: JWT access/refresh rotation, email OTP (Resend), OAuth 2.0 (Google & GitHub), bcrypt hashing, user blocking, and granular CORS.
- Stack: **React, Node.js, Express, Socket.IO, MySQL, Prisma, Redis, Docker**

---

### [NAT Traversal UDP Hole Punching Framework](https://github.com/rushikbuilds/nat-traversal-udp-hole-punching-over-quic)
A peer-to-peer networking framework for NAT traversal and relay fallback.

- **NAT Detection & Hole Punching**: Classifies full cone, restricted cone, port-restricted, and symmetric NAT, then runs simultaneous UDP hole punching with retry logic.
- **QUIC Transport**: `aioquic` with 0-RTT session resumption and built-in TLS 1.3 certificate-based authentication.
- **Relay Fallback & Metrics**: WebSocket relay when hole punching fails, plus a real-time metrics dashboard over HTTP.
- **C++ Core**: Native extension (via `pybind11`) for UDP burst punching and QUIC stream framing, bypassing Python's GIL and event-loop overhead.
- Stack: **Python, C++, aioquic, sockets, Docker**

---

### [Event Sourced Ledger](https://github.com/rushikbuilds/Event-Sourced-Ledger)
An event-sourced bank transaction ledger where every state change is captured as an immutable event, enabling full audit trails, time-travel debugging, and projection rebuilds.

- **Event Sourcing & CQRS**: Immutable append-only log with separate read (projections) and write models (aggregates).
- **Projections**: Account balances and transaction histories are derived dynamically from events.
- **Auto-Evicting Cache**: Redis-backed distributed caching for read query endpoints.
- **FX Conversion**: Real-time cross-currency transfer support.
- Stack: **Java, Spring Boot, Postgres, Redis**

---

### [Raylib Chess Game](https://github.com/RushiK8626/Raylib-Chess-Game)
A fully playable chess game with AI integration.

- Human vs Human and **Human vs Stockfish**
- Full chess rules, FEN generation, and algebraic notation
- Sound effects and custom UI/fonts
- Stack: **C++, Raylib, Stockfish**

---

## 🚀 Currently Exploring

- 🤖 Agentic AI workflows with **LangGraph**
- ⚡ Low-latency networking and **systems-level performance**
- 🧱 Scalable, event-driven **backend architectures**

---

## 🤝 Let's Connect

I'm always open to collaborating on interesting projects, discussing ideas, or just talking tech.

<p align="center">
  <a href="https://github.com/RushiK8626">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/rushikesh-kadepurkar-9a9006292/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:rushikeshk2005@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

<p align="center">
  <em>⭐ Thanks for stopping by, happy building!</em>
</p>
