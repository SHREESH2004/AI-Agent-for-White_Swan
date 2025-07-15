
# 🤖✈️ MCP AI Agent — Autonomous Flight Booking for White Swan

A next-gen AI agent that autonomously interacts with the **White Swan Flight Booking Microservices Platform** using the **Model Context Protocol (MCP)**. This intelligent agent can **search**, **book**, and **manage** flights end-to-end — securely and without human intervention.

> 🧠 Think of it as your backend co-pilot — capable of executing complex workflows like a human, but faster and more reliably.

---

## 🚀 Features

- 🔐 **JWT Auth Integration** — Secure login with White Swan’s Auth Service.
- 🛫 **Flight Discovery** — Fetches live flights using Flight Service.
- 🧾 **Smart Booking** — Automates seat booking using Booking Service APIs.
- ⏱️ **Auto Expiry-Aware** — Handles booking expiry with cron compatibility.
- 🤖 **Contextual AI** — Uses MCP to make decisions based on memory and goals.
- 🧠 **Agent-to-Agent (A2A) Ready** — Easily pluggable into autonomous agent ecosystems.

---

## 🧰 Tech Stack

| Tech        | Purpose                              |
|-------------|---------------------------------------|
| Node.js     | Backend runtime                       |
| Express.js  | API routing and logic                 |
| Axios       | Inter-service communication           |
| JWT         | Secure authentication                 |
| dotenv      | Secure environment configuration      |
| MCP         | AI context protocol for autonomous ops |

---

## 🗂️ Directory Structure

```bash
mcp-ai-agent/
├── mcp/                   # Core MCP logic
│   └── agent.js
├── services/              # Integration with White Swan services
│   ├── authService.js
│   ├── flightService.js
│   └── bookingService.js
├── controllers/           # Action orchestration
│   └── bookingController.js
├── utils/                 # Utility functions
│   └── tokenManager.js
├── .env                   # Config for secrets and URLs
├── index.js               # Agent entry point
└── README.md              # You’re here!
````

---

## ⚙️ Getting Started

### 1. Clone the Repo

```bash
git clone https://github.com/SHREESH2004/AI-Agent-for-White_Swan.git
cd AI-Agent-for-White_Swan
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Set Up `.env`

```env
AUTH_SERVICE_URL=http://localhost:9001
FLIGHT_SERVICE_URL=http://localhost:9002
BOOKING_SERVICE_URL=http://localhost:9003
JWT_SECRET=your_secret_key
```

### 4. Run the Agent

```bash
node index.js
```

---

## 💡 Why MCP + Microservices?

> Traditional automation can trigger APIs.
> **MCP Agents** can **understand, decide, and adapt** based on system context.

By combining MCP with microservices, this agent can:

* React to system changes (e.g., seat availability, payment failures)
* Chain multiple services into autonomous workflows
* Easily integrate with A2A-based agent networks

---

## 🧠 Future-Ready

✅ Modular
✅ Docker-Ready
✅ Microservices Compatible
🧠 LangChain & Kubernetes support coming soon

---

## 📸 Preview Architecture

![White Swan AI Agent Architecture](https://github.com/user-attachments/assets/dacab108-53f3-4255-a4ad-f84e1a222e73)

---

## 🤝 Contribute & Collaborate

We welcome PRs, forks, issues, and collabs from developers interested in:

* AI agent ecosystems
* MCP/A2A protocols
* Scalable backend architectures

📫 DM me on [LinkedIn](https://linkedin.com/in/your-profile)
⭐ Star the [GitHub Repo](https://github.com/SHREESH2004/AI-Agent-for-White_Swan.git) to support the project!

---

## 🔖 License

MIT — Use it, extend it, automate with it.
*White Swan agents don’t sleep.* 🕊️

```

---

Would you like:

- A **badge row** (e.g. stars, license, tech)?
- **Live demo** GIF of agent workflow (can embed if you send video)?
- **Agent logs** or **interaction sample** in the README?

Let me know if you want it ready for Hackathons or DevFolio/Showwcase too!
```
