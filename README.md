# 🤖 AtlasHub
### More than a bot — a full automation hub

![version](https://img.shields.io/badge/version-1.9-blue)
![node](https://img.shields.io/badge/node-18+-green)
![license](https://img.shields.io/badge/license-MIT-orange)
![status](https://img.shields.io/badge/status-stable-brightgreen)

> All-in-one WhatsApp automation platform with economy, games, moderation, leveling system and web dashboard.

---

# 🚀 What is AtlasHub?

**AtlasHub** is an advanced WhatsApp bot platform developed by **Kinetic Space Inc.**

It is designed to go beyond simple chatbot behavior and act as a **complete automation hub**:

- 💰 Virtual economy
- 🎮 Games
- 🛡 Moderation tools
- 📊 Rankings & leveling
- 🌐 Web dashboard
- ⚙ Modular architecture

AtlasHub is built for:
- Communities
- Businesses
- Large groups
- Developers

---

# ✨ Features

| System | Included |
|-----------|------------|
| Economy system | ✅ |
| Cooldowns / anti-spam | ✅ |
| Games | ✅ |
| Levels & XP | ✅ |
| Moderation tools | ✅ |
| Web Panel | ✅ |
| Modular commands | ✅ |
| Multi-group support | ✅ |
| Persistent database | ✅ |

---

# 🛠 Tech Stack

```
Node.js
whatsapp-web.js
Express
Puppeteer
JSON / SQLite
```

---

# 📦 Installation

## Requirements
- Node.js 18+
- NPM
- WhatsApp account

## Setup

```bash
git clone https://github.com/YOUR_USER/atlashub
cd atlashub
npm install
node index.js
```

---

# ⚙ Configuration

Create `.env` file:

```
PREFIX=#
PORT=3000
SESSION_NAME=atlas
```

---

# 🔑 Command Prefix

```
#
```

Example:

```
#menu
```

---

# 📚 Commands

## 💰 Economy
```
#daily
#work
#balance
#bank
#deposit
#withdraw
#pay
```

## 🎮 Games
```
#coinflip
#dice
#slots
#rps
#blackjack
```

## 👤 Profile
```
#profile
#level
#rank
#top
```

## ⚙ Utility
```
#menu
#ping
#uptime
#info
```

## 👑 Admin
```
#warn
#reset
#addcoins
#ban
#unban
```

---

# 🧠 Architecture

```
WhatsApp User
      │
      ▼
whatsapp-web.js
      │
      ▼
AtlasHub Core
      │
 ┌────┼─────┐
 ▼    ▼     ▼
Economy Games Commands
      │
      ▼
Database
      │
      ▼
Web Panel (Express)
```

---

# 📁 Project Structure

```
atlashub/
│
├─ src/
│   ├─ core/
│   ├─ commands/
│   ├─ database/
│   └─ utils/
│
├─ panel/
├─ data/
├─ docs/
│
├─ index.js
├─ package.json
├─ .env.example
├─ README.md
└─ LICENSE
```

---

# 🔌 Developer API

## Create a command

```js
module.exports = {
  name: "ping",
  cooldown: 3000,
  run: async (client, message, args) => {
    message.reply("Pong!");
  }
}
```

## Register events

```js
client.on("message", handler)
client.on("ready", () => console.log("AtlasHub ready"))
```

---

# 🌐 Web Panel

Run:

```bash
npm run panel
```

Open:

```
http://localhost:3000
```

Panel features:
- View users
- Manage economy
- Stats
- Logs
- System control

---

# 🔒 Security

AtlasHub includes:

- Cooldowns
- Anti-spam checks
- Input validation
- Safe session handling
- Error protection
- Modular isolation

---

# 🤝 Contributing

We welcome contributions!

1. Fork the repo
2. Create a branch
3. Commit changes
4. Open Pull Request

---

# 🗺 Roadmap

- [ ] Achievements system
- [ ] More games
- [ ] Advanced dashboard
- [ ] SQLite DB
- [ ] Plugin marketplace
- [ ] Multi-instance scaling
- [ ] REST API

---

# 🏢 Organization

Developed by:

**Kinetic Space Inc.**

Software • Automation • AI • Platforms

---

# 📬 Contact

### 🤖 AI Department
Kinetic.AI@post.com

### 🌐 General / Business
KineticSpaceOfficial@gmail.com

---

# 📜 License

MIT License  
© 2026 Kinetic Space Inc.

---

# ⭐ AtlasHub
### More than a bot — a full automation hub
