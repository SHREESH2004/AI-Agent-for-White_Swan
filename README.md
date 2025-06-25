

````markdown
# 🤖✈️ MCP AI Agent — Autonomous Flight Booking for White Swan


A next-gen AI agent built to autonomously interact with the **White Swan Flight Booking Microservices Platform** using the **Model Context Protocol (MCP)**. This smart agent can **search**, **book**, and **manage** flights end-to-end — securely and autonomously.


> 🧠 Think of it as your backend co-pilot — capable of executing complex flight bookings like a human, but faster and more reliably.

---

## 🚀 What Can It Do?

- 🔐 **Authenticate Users** — Logs in via JWT with White Swan's Auth Service.
- 🛫 **Search Flights** — Fetches real-time flight data from the Flight Service.
- 📩 **Book Flights** — Places bookings using validated APIs.
- ⏱️ **Handle Auto-Expiry** — Fully compatible with cron-based 5-minute unpaid booking expiry logic.
- 🤖 **Context-Aware Decisions** — Uses MCP to act based on agent memory and goals.
- 🧠 **Plug-in Ready for A2A Systems** — Future-proof agent ready to collaborate in autonomous agent ecosystems.

---

## 🧰 Tech Stack

| Tech        | Usage                                 |
|-------------|----------------------------------------|
| Node.js     | Runtime                                |
| Express.js  | Lightweight API framework              |
| Axios       | Microservice communication             |
| dotenv      | Secure environment variable management |
| JWT         | Authentication                         |
| MCP         | Contextual agent protocol              |

---

## 🗂️ Directory Structure

```bash
mcp-ai-agent/
├── mcp/                   # Core agent logic (MCP context, triggers)
│   └── agent.js
├── services/              # API integrations (Auth, Flight, Booking)
│   ├── authService.js
│   ├── flightService.js
│   └── bookingService.js
├── controllers/           # Agent action orchestration
│   └── bookingController.js
├── utils/                 # Token and helper utilities
│   └── tokenManager.js
├── .env                   # Environment variables
├── index.js               # Agent entry point
└── README.md

````

---

https://github.com/user-attachments/assets/dacab108-53f3-4255-a4ad-f84e1a222e73

## ⚙️ Getting Started

### 1. 🚧 Clone the Project

```bash
git clone https://github.com/your-username/mcp-ai-agent.git
cd mcp-ai-agent
```

### 2. 📦 Install Dependencies

```bash
npm install
```




## 💡 Why MCP + Microservices?

> Traditional automation can trigger APIs.
> MCP Agents **understand context**, make decisions, and can scale autonomously.

With White Swan’s decoupled services, MCP agents can:

* React to system state (e.g. available seats)
* Automate flows (e.g. booking + payment retries)
* Integrate into a future network of AI agents via A2A

---

## 📦 Ready for the Future

✅ Microservices Friendly
✅ Docker-Ready
✅ Modular & Extensible
🚧 Kubernetes & LangChain support coming soon

---

## 🤝 Contributions & Collaboration

This project is open to feedback, forks, and forward-thinking collabs in the **AI automation + backend** space. If you're working on AI agents, MCP, or autonomous workflows — let's connect!

📫 DM me on [LinkedIn]([https://linkedin.com/in/your-profile)]
⭐ Star the [GitHub Repo]((https://github.com/SHREESH2004/AI-Agent-for-White_Swan.git)) if this inspires you!


## 🔖 License

MIT — Use it, build on it, and fly with it.
