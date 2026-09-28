<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=MEGA-MD&fontSize=72&fontColor=fff&animation=twinkling&fontAlignY=32&desc=High%20Performance%20WhatsApp%20Bot&descAlignY=55&descSize=20" width="100%"/>

<br/>

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=22&pause=1000&color=25D366&center=true&vCenter=true&width=600&lines=Multi-Device+WhatsApp+Bot;250%2B+Commands+%26+Counting;Plugin+Architecture+%7C+Auto-Loading;Deploy+Anywhere+in+Minutes)](https://git.io/typing-svg)

<br/>

[![Version](https://img.shields.io/badge/Version-6.0.0-blue?style=for-the-badge&logo=github)](https://github.com/GlobalTechInfo/MEGA-MD)
[![Node.js](https://img.shields.io/badge/Node.js-20%2B-339933?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org)
[![WhatsApp](https://img.shields.io/badge/Baileys-7.x-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://github.com/WhiskeySockets/Baileys)
[![Stars](https://img.shields.io/github/stars/GlobalTechInfo/MEGA-MD?style=for-the-badge&logo=starship&color=gold)](https://github.com/GlobalTechInfo/MEGA-MD/stargazers)
[![Forks](https://img.shields.io/github/forks/GlobalTechInfo/MEGA-MD?style=for-the-badge&logo=git&color=orange)](https://github.com/GlobalTechInfo/MEGA-MD/network/members)

<br/>

**250+ Commands · Multi-Platform · Multi-Database · Plugin Architecture**

<br/>

[📦 Installation](#-installation) · [🔐 Session Setup](#-getting-your-session-id) · [⚙️ Configuration](#️-configuration) · [🚀 Deployment](#-deployment) · [🔌 Plugins](#-plugin-system)

<br/>

---

### 🌍 Deploy on your favourite platform

[![Heroku](https://img.shields.io/badge/Heroku-430098?style=for-the-badge&logo=heroku&logoColor=white)](https://heroku.com)
[![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black)](https://render.com)
[![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white)](https://railway.app)
[![Koyeb](https://img.shields.io/badge/Koyeb-121212?style=for-the-badge&logo=koyeb&logoColor=white)](https://koyeb.com)
[![Fly.io](https://img.shields.io/badge/Fly.io-7B3FE4?style=for-the-badge&logo=flydotio&logoColor=white)](https://fly.io)
[![Replit](https://img.shields.io/badge/Replit-F26207?style=for-the-badge&logo=replit&logoColor=white)](https://replit.com)
[![VPS](https://img.shields.io/badge/Linux_VPS-FCC624?style=for-the-badge&logo=linux&logoColor=black)](#-vps--linux-server)
[![Termux](https://img.shields.io/badge/Termux-000000?style=for-the-badge&logo=android&logoColor=white)](#-termux-android)
[![Windows](https://img.shields.io/badge/Windows_WSL-0078D4?style=for-the-badge&logo=windows&logoColor=white)](#-windows-wsl)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](#-dockerfile)

</div>

---

## 📋 Table of Contents

- [✨ Features](#-features)
- [📌 Requirements](#-requirements)
- [⚡ Quick Start](#-quick-start)
- [🔐 Getting Your Session ID](#-getting-your-session-id)
- [⚙️ Configuration](#️-configuration)
- [📦 Installation](#-installation)
- [🚀 Deployment](#-deployment)
  - [📱 Termux](#-termux-android)
  - [🖥️ VPS Linux Server](#-vps-linux-server)
  - [🪟 Windows WSL](#-windows-wsl)
  - [🔁 Replit](#-replit)
  - [🟣 Heroku](#-heroku)
  - [🎨 Render](#-render)
  - [🚂 Railway](#-railway)
  - [☁️ Koyeb](#-koyeb)
  - [🪂 Fly.io](#-flyio)
  - [🐳 Dockerfile](#-dockerfile)
  - [🎮 Discord Panels](#-discord-panels-pterodactyl)
- [🗄️ Storage Backends](#️-storage-backends)
- [🛠️ Environment Variables](#️-environment-variables)
- [📜 npm Scripts](#-npm-scripts)
- [🔌 Plugin System](#-plugin-system)
- [🔧 Troubleshooting](#-troubleshooting)
- [🤝 Contributing](#-contributing)

---

## ✨ Features

| | Feature | Description |
|---|---|---|
| 🔌 | **Auto-loading Plugins** | Drop a `.ts` file in `plugins/` — it loads automatically, zero registration |
| 💬 | **250+ Commands** | Group management, privacy, moderation, fun, AI, media, utilities |
| 🗄️ | **5 Storage Backends** | MongoDB, PostgreSQL, MySQL, SQLite, or JSON files |
| 🛡️ | **Group Protection** | Anti-spam, bad word filter, link detection, anti-tag abuse |
| 👑 | **Role System** | Owner, Sudo, Admin, and User permission levels |
| ⏰ | **Scheduled Messages** | Schedule messages with natural time input |
| 🤖 | **AI Chatbot** | Per-chat AI conversation mode |
| 🔒 | **Privacy Controls** | Full WhatsApp privacy management via commands |
| 📊 | **Polls & Voting** | Create polls with live vote tracking in groups |
| 📡 | **Broadcast** | Bulk message all groups or all DM contacts at once |
| 🔁 | **Auto-Reply** | Configurable trigger-based auto responses with `{name}` support |
| 🎮 | **Games** | TicTacToe and more built in |
| ⏳ | **Disappearing Messages** | Set per-chat or default timers via commands |
| 📱 | **Multi-Platform** | Runs on Termux, VPS, Railway, Render, Heroku, Koyeb, Fly.io, Replit |

---

## 📌 Requirements

| Requirement | Version | Notes |
|---|---|---|
| ![Node.js](https://img.shields.io/badge/Node.js-20%2B-339933?logo=node.js&logoColor=white) | **20.x or higher** | Required |
| ![npm](https://img.shields.io/badge/npm-8%2B-CB3837?logo=npm&logoColor=white) | 8.x or higher | Included with Node.js |
| ![Git](https://img.shields.io/badge/Git-latest-F05032?logo=git&logoColor=white) | Any recent | For cloning |
| ![ffmpeg](https://img.shields.io/badge/ffmpeg-latest-007808?logo=ffmpeg&logoColor=white) | Latest | Media processing |
| ![libvips](https://img.shields.io/badge/libvips-latest-blueviolet) | Latest | Image processing |
| ![libwebp](https://img.shields.io/badge/libwebp-latest-blue) | Latest | Sticker creation |

> [!WARNING]
> **Never use your personal WhatsApp number for the bot.** Always use a dedicated number.

---

## ⚡ Quick Start

```bash
git clone https://github.com/GlobalTechInfo/MEGA-MD.git
cd MEGA-MD
npm install
cp sample.env .env
# Edit .env → add SESSION_ID and OWNER_NUMBER
npm start
```

---

## 🔐 Getting Your Session ID
> [!IMPORTANT]
> The bot uses a **Session ID** to connect to WhatsApp without scanning QR every time. Generate it once and paste it in `.env`.

### Step 1 — Open the session generator

> 🌐 **https://mega-pairing.onrender.com**

### Step 2 — Generate your session

**Option A — Pair Code** *(Recommended)*

1. Enter your bot's WhatsApp number with country code (e.g. `923001234567`)
2. Click **Generate Pair Code**
3. An 8-character code appears (e.g. `J38K-4PNS`)
4. On your phone: **WhatsApp → ⋮ Menu → Linked Devices → Link a Device → Link with phone number**
5. Enter the code — session is created
6. Copy the **Session ID** shown on the page

**Option B — QR Code**

1. Click the **QR Code** tab
2. Scan the QR code with your WhatsApp
3. Copy the **Session ID** shown after scanning

### Step 3 — Add to `.env`

```env
SESSION_ID=GlobalTechInfo/MEGA-MD_xxxxxxxxxxxxxxxxxxxxxxxx
```

### Alternative — Pairing via terminal

Leave `SESSION_ID` empty and set:

```env
PAIRING_NUMBER=923001234567
```

> [!NOTE]
> The bot will print an 8-character pairing code in the terminal on startup. Link it via **WhatsApp → Linked Devices → Link with phone number** within 60 seconds.

---

## ⚙️ Configuration

Copy `sample.env` to `.env`:

```bash
cp sample.env .env
```

```env
# ── REQUIRED (choose one) ────────────────────────────────────
SESSION_ID=GlobalTechInfo/MEGA-MD_your_gist_id_here
# OR
PAIRING_NUMBER=923001234567

# ── REQUIRED ─────────────────────────────────────────────────
OWNER_NUMBER=923000000000        # No + sign

# ── BOT IDENTITY ─────────────────────────────────────────────
BOT_NAME=MEGA-MD-PRO
BOT_OWNER=GlobalTechInfo
PACKNAME=MEGA-MD

# ── BEHAVIOUR ────────────────────────────────────────────────
PREFIXES=.,!,/                   # Comma-separated
COMMAND_MODE=public              # public or private
TIMEZONE=Asia/Karachi

# ── OPTIONAL API KEYS ────────────────────────────────────────
REMOVEBG_KEY=                    # https://remove.bg/api
GIPHY_API_KEY=                   # https://developers.giphy.com

# ── PERFORMANCE ──────────────────────────────────────────────
PORT=5000
MAX_STORE_MESSAGES=50

# ── DATABASE (all empty = JSON files) ────────────────────────
MONGO_URL=
POSTGRES_URL=
MYSQL_URL=
DB_URL=                          # SQLite: ./data/baileys.db
```

---

## 📦 Installation

### Manual Install

```bash
# 1. Clone
git clone https://github.com/GlobalTechInfo/MEGA-MD.git
cd MEGA-MD

# 2. Install dependencies
npm install

# 3. Configure
cp sample.env .env
nano .env

# 4. Start
npm start
```

### One-Line VPS Installer

```bash
sudo bash <(curl -fsSL https://raw.githubusercontent.com/GlobalTechInfo/MEGA-MD/main/lib/install.sh)
```
> [!IMPORTANT]
> This automatically installs Node.js 20, ffmpeg, libvips, libwebp, PM2, clones the repo, builds it, and sets up data files.

```bash
# After install:
nano /root/MEGA-MD/.env
cd /root/MEGA-MD && pm2 start dist/index.js --name mega-md
pm2 save && pm2 startup
```

---

## 🚀 Deployment

### 📱 Termux (Android)

```bash
# Update packages
pkg update && pkg upgrade -y

# Install proot-distro (recommended for full Linux environment)
pkg install proot-distro -y
proot-distro install ubuntu
proot-distro login ubuntu

# Inside Ubuntu — install dependencies
apt update && apt upgrade -y
apt install -y git ffmpeg build-essential libvips-dev webp nodejs npm curl

# Clone and setup
git clone https://github.com/GlobalTechInfo/MEGA-MD.git
cd MEGA-MD
npm install
cp sample.env .env && nano .env
npm start
```

**Keep running after closing Termux:**

```bash
apt install tmux -y

tmux new -s mega-md    # Start new session
npm start

# Detach:     Ctrl+B → D
# Re-attach:  tmux attach -t mega-md
# List:       tmux ls
# Kill:       tmux kill-session -t mega-md
```

---

### 🖥️ VPS Linux Server

[![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)](https://ubuntu.com)
[![Debian](https://img.shields.io/badge/Debian-A81D33?style=flat-square&logo=debian&logoColor=white)](https://debian.org)

**One-line install (recommended):**
```bash
sudo bash <(curl -fsSL https://raw.githubusercontent.com/GlobalTechInfo/MEGA-MD/main/lib/install.sh)
```

**Manual:**
```bash
curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -
sudo apt install -y nodejs git ffmpeg libvips-dev libwebp-dev build-essential

git clone https://github.com/GlobalTechInfo/MEGA-MD.git
cd MEGA-MD
npm install
cp sample.env .env && nano .env

# Keep alive with PM2
npm install -g pm2
pm2 start dist/index.js --name mega-md
pm2 save && pm2 startup
```

**PM2 commands:**

| Command | Description |
|---|---|
| `pm2 logs mega-md` | Live logs |
| `pm2 restart mega-md` | Restart |
| `pm2 stop mega-md` | Stop |
| `pm2 status` | Status overview |

---

### 🪟 Windows (WSL)

[![Windows](https://img.shields.io/badge/Windows_11-0078D4?style=flat-square&logo=windows11&logoColor=white)](https://microsoft.com/windows)

```bash
# In WSL Ubuntu terminal
sudo apt update
curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -
sudo apt install -y nodejs git ffmpeg libvips-dev libwebp-dev build-essential

git clone https://github.com/GlobalTechInfo/MEGA-MD.git
cd MEGA-MD
npm install
cp sample.env .env && nano .env
npm start
```

---

### 🔁 Replit

[![Replit](https://img.shields.io/badge/Replit-F26207?style=flat-square&logo=replit&logoColor=white)](https://replit.com)
> [!NOTE]
> The repo includes pre-configured `.replit` and `replit.nix`.

1. Go to [replit.com](https://replit.com) → **Create Repl** → **Import from GitHub**
2. Paste: `https://github.com/GlobalTechInfo/MEGA-MD`
3. Open **Secrets** tab (🔒) and add:

   | Key | Value |
   |---|---|
   | `SESSION_ID` | `GlobalTechInfo/MEGA-MD_your_gist_id` |
   | `OWNER_NUMBER` | `923001234567` |

4. Click **Run**

`replit.nix` automatically installs: Node.js 20, ffmpeg, imagemagick, libwebp, SQLite, pm2 etc.

> [!TIP]
> Free Replit instances sleep after inactivity. Use [UptimeRobot](https://uptimerobot.com) to ping your Replit URL every 5 minutes to keep it alive.
> [!NOTE]
> Production deployment uses `npm run start:optimized` (512MB memory limit) — configured in `.replit`'s `[deployment]` section.

---

### 🟣 Heroku

[![Heroku](https://img.shields.io/badge/Heroku-430098?style=flat-square&logo=heroku&logoColor=white)](https://heroku.com)
> [!NOTE]
> The repo includes `heroku.yml` and `app.json` for Docker-based deployment.
> 
> Either you can deploy via dashboard or using heroku cli

**One-line Deployer:**
```bash
bash <(curl -s https://raw.githubusercontent.com/GlobalTechInfo/MEGA-MD/main/lib/heroku.sh)
```
**Manual:**
```bash
heroku login
heroku create your-bot-name
heroku stack:set container

heroku config:set SESSION_ID=GlobalTechInfo/MEGA-MD_your_gist_id
heroku config:set OWNER_NUMBER=923001234567
heroku config:set MONGO_URL=your_mongodb_url   # Recommended

git push heroku main
heroku ps:scale web=1
heroku logs --tail
```

> [!IMPORTANT]
> Heroku's filesystem is **ephemeral** — data is lost on restart. Use MongoDB or PostgreSQL for persistent storage.
> [!NOTE]
> Heroku uses `heroku.yml` → Docker build → runs `npm run start:optimized`.

---

### 🎨 Render

[![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black)](https://render.com)
> [!NOTE]
> The repo includes `render.yaml` for one-click Blueprint deployment.

1. Fork this repo
2. [render.com](https://render.com) → **New** → **Blueprint** → connect your fork
3. Render reads `render.yaml` automatically
4. Set environment variables in the dashboard:
   - `SESSION_ID`
   - `OWNER_NUMBER`
5. Deploy

> [!IMPORTANT]
> Render uses Docker (`Dockerfile`) and runs `npm run start:optimized`. Use a database for persistent storage on Render's free tier.

---

### 🚂 Railway

[![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white)](https://railway.app)

1. Fork this repo
2. [railway.app](https://railway.app) → **New Project** → **Deploy from GitHub Repo**
3. Select your fork
4. **Variables** tab → add:

   | Key | Value |
   |---|---|
   | `SESSION_ID` | `GlobalTechInfo/MEGA-MD_your_gist_id` |
   | `OWNER_NUMBER` | `923001234567` |

5. Railway auto-builds via `Dockerfile` and deploys

---

### ☁️ Koyeb

[![Koyeb](https://img.shields.io/badge/Koyeb-121212?style=flat-square&logo=koyeb&logoColor=white)](https://app.koyeb.com)

1. Fork this repo
2. [app.koyeb.com](https://app.koyeb.com) → **Create App** → **GitHub**
3. Select your fork — Koyeb reads `koyeb.yaml`
4. Set `SESSION_ID` and `OWNER_NUMBER` in env vars
5. Deploy

---

### 🪂 Fly.io

[![Fly.io](https://img.shields.io/badge/Fly.io-7B3FE4?style=flat-square&logo=flydotio&logoColor=white)](https://fly.io)
> [!NOTE]
> The repo includes `fly.toml` pre-configured (512MB RAM, port 5000, region: US East).
> 
> Either deploy via dashboard or using cli

**One-line Deployer:**
```bash
bash <(curl -s https://raw.githubusercontent.com/GlobalTechInfo/MEGA-MD/main/lib/fly.sh)
```
**Manual:**
```bash
curl -L https://fly.io/install.sh | sh
fly auth login

fly launch --no-deploy
fly secrets set SESSION_ID=GlobalTechInfo/MEGA-MD_your_gist_id
fly secrets set OWNER_NUMBER=923001234567
fly deploy

fly logs   # View logs
```

`fly.toml` settings: auto-start enabled, auto-stop **disabled** so the bot stays running 24/7.

---

### 🐳 Dockerfile

[![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)](https://docker.com)
> [!NOTE]
> The repo includes a `Dockerfile` for any Docker-compatible platform.

```bash
# Build image
docker build -t mega-md .

# Run
docker run -d \
  -e SESSION_ID=GlobalTechInfo/MEGA-MD_your_gist_id \
  -e OWNER_NUMBER=923001234567 \
  -p 5000:5000 \
  --name mega-md \
  mega-md

# Logs
docker logs -f mega-md
```

---

### 🎮 Discord Panels (Pterodactyl)
> [!IMPORTANT]
> For Pterodactyl-based hosting panels (Fosshost, Skynode, Optiklink etc.):
> Use brave browser or any adguard to avoid ads from hosting panels

1. Create server with a **Node.js 20+ egg**
2. Set startup command:
   ```
   npm install && npm start
   ```
3. Upload files via SFTP or file manager
4. Add env vars in the **Startup** tab: `SESSION_ID`, `OWNER_NUMBER`
5. Start the server

> [!IMPORTANT]
> Ensure the egg uses **Node.js 20 or newer**. If your panel supports Docker, use the included `Dockerfile` instead for best compatibility.

---

## 🗄️ Storage Backends

> [!NOTE]
> Set one database URL in `.env`. If all are empty, JSON file storage is used automatically — no setup needed.

| Backend | Badge | Best For |
|---|---|---|
| **JSON Files** | ![JSON](https://img.shields.io/badge/JSON-000000?style=flat-square&logo=json&logoColor=white) | Local, Termux |
| **MongoDB** | ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) | Cloud (recommended) |
| **PostgreSQL** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) | Cloud / VPS |
| **MySQL** | ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) | Cloud / VPS |
| **SQLite** | ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) | VPS (no external DB) |

```env
# MongoDB
MONGO_URL=mongodb+srv://user:password@cluster.mongodb.net/megamd

# PostgreSQL
POSTGRES_URL=postgresql://user:password@host:5432/megamd

# MySQL
MYSQL_URL=mysql://user:password@host:3306/megamd

# SQLite
DB_URL=./data/baileys.db
```

> [!TIP]
> Get a free MongoDB cluster at [MongoDB Atlas](https://cloud.mongodb.com) — best choice for cloud deployments where the filesystem resets.

---

## 🛠️ Environment Variables

| Variable | Required | Default | Description |
|---|---|---|---|
| `SESSION_ID` | ✅ *one of* | — | From mega-pairing.onrender.com |
| `PAIRING_NUMBER` | ✅ *one of* | — | Phone number for terminal pairing |
| `OWNER_NUMBER` | ✅ | `923051391007` | Your number, no `+` |
| `BOT_NAME` | ❌ | `MEGA-MD` | Bot display name |
| `BOT_OWNER` | ❌ | `Qasim Ali` | Owner display name |
| `PACKNAME` | ❌ | `MEGA-MD` | Sticker pack name |
| `PREFIXES` | ❌ | `.,!,/,#` | Comma-separated prefixes |
| `COMMAND_MODE` | ❌ | `public` | `public` or `private` |
| `TIMEZONE` | ❌ | `Asia/Karachi` | Your timezone |
| `PORT` | ❌ | `5000` | HTTP server port |
| `MAX_STORE_MESSAGES` | ❌ | `20` | Messages stored per chat |
| `REMOVEBG_KEY` | ❌ | — | [remove.bg](https://remove.bg) API key |
| `GIPHY_API_KEY` | ❌ | — | [Giphy](https://developers.giphy.com) API key |
| `MONGO_URL` | ❌ | — | MongoDB connection string |
| `POSTGRES_URL` | ❌ | — | PostgreSQL connection string |
| `MYSQL_URL` | ❌ | — | MySQL connection string |
| `DB_URL` | ❌ | — | SQLite file path |
| `CLEANUP_INTERVAL` | ❌ | `3600000` | Temp cleanup interval (ms) |
| `STORE_WRITE_INTERVAL` | ❌ | `10000` | Store write interval (ms) |

---

## 📜 npm Scripts

| Script | Description |
|---|---|
| `npm start` | Start the bot |
| `npm run start:optimized` | Start with 512MB memory cap *(cloud use)* |
| `npm run start:fresh` | Reset data files then start |
| `npm run dev` | Watch mode with auto-restart |
| `npm run reset-data` | Re-initialize all JSON data files |
| `npm run reset-session` | Delete `session/` folder |
| `npm run lint` | Run ESLint |
| `npm test` | Run all tests |

---

## 🔌 Plugin System

> [!IMPORTANT]
> Plugins live in `plugins/` and are auto-loaded on startup — no registration needed. Each file must export a `default` object.

### Plugin Template

```js
export default {
    command: 'mycommand',
    aliases: ['mc', 'mycmd'],
    category: 'utility',
    description: 'Does something cool',
    usage: '.mycommand <input>',

    // Optional permission flags
    ownerOnly: false,      // Owner/sudo only
    groupOnly: false,      // Groups only
    adminOnly: false,      // Group admins only
    isPrefixless: true,    // Works without prefix too
    cooldown: 5,           // Cooldown in seconds

    async handler(sock: any, message: any, args: any[], context: any = {}) {
        const {
            chatId,           // Chat JID
            senderId,         // Sender JID
            isGroup,          // boolean
            isSenderAdmin,    // boolean
            isBotAdmin,       // boolean
            senderIsOwnerOrSudo, // boolean
            rawText,          // Full message text
            userMessage,      // Lowercase message
            config,           // Bot configuration 
            channelInfo       // MEGA-MD branding spread
        } = context;

        await sock.sendMessage(chatId, {
            text: `You said: ${args.join(' ')}`,
            ...channelInfo
        }, { quoted: message });
    }
};
```

---

## 🔧 Troubleshooting

### Bot not connecting

> [!IMPORTANT]
> - Verify `SESSION_ID` starts with `GlobalTechInfo/MEGA-MD_`
> - If using `PAIRING_NUMBER`, link within 60 seconds of the code appearing
> - Reset session and reconnect: `npm run reset-session && npm start`

### `myAppStateKey not present` (pin/star broken)

Session lost its app state keys. Fix:

```bash
node -e "
const fs = require('fs');
const c = JSON.parse(fs.readFileSync('session/creds.json','utf8'));
delete c.myAppStateKeyId;
fs.writeFileSync('session/creds.json', JSON.stringify(c, null, 2));
console.log('Done');
"
npm start
```

Send any message to the bot — WhatsApp re-syncs keys automatically. They are now preserved across restarts.

### Commands not responding

- Check you're using the right prefix (default `.`)
- `COMMAND_MODE=private` → only owner can use commands
- `OWNER_NUMBER` must have no `+` sign

### Data lost after restart

> [!CAUTION]
> Cloud platforms reset the filesystem on redeploy. Add `MONGO_URL` to use MongoDB — [MongoDB Atlas](https://cloud.mongodb.com) has a free tier.

### Port conflict

```bash
PORT=3000 npm start
```

---

## 🧪 Testing

The codebase has a comprehensive test suite covering all core systems:

```bash
npm test                # Run all 178 tests
npm run test:coverage   # Run with coverage report
npm run test:watch      # Watch mode during development
```

| Test Suite | What's Covered |
|---|---|
| Unit — `myfunc` | 21 utility function tests with real input/output assertions |
| Unit — `commandHandler` | Command registration, alias routing, toggle, suggestions |
| Unit — `isOwner` | JID matching, device suffix stripping, sudo checks |
| Unit — `isBanned` | File-based ban list read/write |
| Unit — `paths` | Data directory resolution |
| Integration — plugins | ALL plugins load, no duplicate commands/aliases, correct field types |
| Integration — `messageHandler` | Full message flow, banned users, error handling |
| Integration — group events | add/remove/promote/demote without crashing |
| Integration — call handling | Anticall reject, warn, empty call safety |

> Uses [Vitest](https://vitest.dev) with a custom Baileys socket mock that simulates real WhatsApp message flows without requiring a live connection.

---

## 🤝 Contributing

1. Fork the repo
2. Create your plugin in `plugins/yourfeature.ts`
3. Follow the plugin template above
4. Test thoroughly
5. Open a Pull Request

---

## 📞 Support

<div align="center">

[![Telegram](https://img.shields.io/badge/Telegram-FF0000?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/Global_TechInfo)
[![WhatsApp](https://img.shields.io/badge/WhatsApp_Channel-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://whatsapp.com/channel/0029VagJIAr3bbVBCpEkAM07)
[![GitHub Issues](https://img.shields.io/badge/GitHub_Issues-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/GlobalTechInfo/MEGA-MD/issues)

</div>

---

## ⚠️ Disclaimer

> [!CAUTION]
> This project is **not affiliated with WhatsApp Inc.** Use responsibly and within [WhatsApp's Terms of Service](https://www.whatsapp.com/legal/terms-of-service). The developers are not responsible for account bans or misuse.

---

## 📄 License

[MIT License](LICENSE) · Made with ❤️ by **Qasim Ali** · [GlobalTechInfo](https://github.com/GlobalTechInfo)

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>

⭐ **If this project helped you, please give it a star!** ⭐

</div>
# Basic writing and formatting syntax

Create sophisticated formatting for your prose and code on GitHub with simple syntax.

## Headings

To create a heading, add one to six <kbd>#</kbd> symbols before your heading text. The number of <kbd>#</kbd> you use will determine the hierarchy level and typeface size of the heading.

```markdown
# A first-level heading
## A second-level heading
### A third-level heading
```

![Screenshot of rendered GitHub Markdown showing sample h1, h2, and h3 headers, which descend in type size and visual weight to show hierarchy level.](/assets/images/help/writing/headings-rendered.png)

When you use two or more headings, GitHub automatically generates a table of contents that you can access by clicking the "Outline" menu icon <svg version="1.1" width="16" height="16" viewBox="0 0 16 16" class="octicon octicon-list-unordered" aria-label="Table of Contents" role="img"><path d="M5.75 2.5h8.5a.75.75 0 0 1 0 1.5h-8.5a.75.75 0 0 1 0-1.5Zm0 5h8.5a.75.75 0 0 1 0 1.5h-8.5a.75.75 0 0 1 0-1.5Zm0 5h8.5a.75.75 0 0 1 0 1.5h-8.5a.75.75 0 0 1 0-1.5ZM2 14a1 1 0 1 1 0-2 1 1 0 0 1 0 2Zm1-6a1 1 0 1 1-2 0 1 1 0 0 1 2 0ZM2 4a1 1 0 1 1 0-2 1 1 0 0 1 0 2Z"></path></svg> within the file header. Each heading title is listed in the table of contents and you can click a title to navigate to the selected section.

![Screenshot of a README file with the drop-down menu for the table of contents exposed. The table of contents icon is outlined in dark orange.](/assets/images/help/repository/headings-toc.png)

## Styling text

You can indicate emphasis with bold, italic, strikethrough, subscript, or superscript text in comment fields and `.md` files.

| Style                  | Syntax              | Keyboard shortcut                                                                     | Example                                  | Output                                 |                                                   |
| ---------------------- | ------------------- | ------------------------------------------------------------------------------------- | ---------------------------------------- | -------------------------------------- | ------------------------------------------------- |
| Bold                   | `** **` or `__ __`  | <kbd>Command</kbd>+<kbd>B</kbd> (Mac) or <kbd>Ctrl</kbd>+<kbd>B</kbd> (Windows/Linux) | `**This is bold text**`                  | **This is bold text**                  |                                                   |
| Italic                 | `* *` or `_ _`      | <kbd>Command</kbd>+<kbd>I</kbd> (Mac) or <kbd>Ctrl</kbd>+<kbd>I</kbd> (Windows/Linux) | `_This text is italicized_`              | *This text is italicized*              |                                                   |
| Strikethrough          | `~~ ~~` or `~ ~`    | None                                                                                  | `~~This was mistaken text~~`             | ~~This was mistaken text~~             |                                                   |
| Bold and nested italic | `** **` and `_ _`   | None                                                                                  | `**This text is _extremely_ important**` | **This text is *extremely* important** |                                                   |
| All bold and italic    | `*** ***`           | None                                                                                  | `***All this text is important***`       | ***All this text is important***       | <!-- markdownlint-disable-line emphasis-style --> |
| Subscript              | `<sub> </sub>`      | None                                                                                  | `This is a <sub>subscript</sub> text`    | This is a <sub>subscript</sub> text    |                                                   |
| Superscript            | `<sup> </sup>`      | None                                                                                  | `This is a <sup>superscript</sup> text`  | This is a <sup>superscript</sup> text  |                                                   |
| Underline              | `<ins> </ins>`      | None                                                                                  | `This is an <ins>underlined</ins> text`  | This is an <ins>underlined</ins> text  |                                                   |

## Quoting text

You can quote text with a <kbd>></kbd>.

```markdown
Text that is not a quote

> Text that is a quote
```

Quoted text is indented with a vertical line on the left and displayed using gray type.

![Screenshot of rendered GitHub Markdown showing the difference between normal and quoted text.](/assets/images/help/writing/quoted-text-rendered.png)

> \[!NOTE]
> When viewing a conversation, you can automatically quote text in a comment by highlighting the text, then typing <kbd>R</kbd>. You can quote an entire comment by clicking <svg version="1.1" width="16" height="16" viewBox="0 0 16 16" class="octicon octicon-kebab-horizontal" aria-label="The horizontal kebab icon" role="img"><path d="M8 9a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3ZM1.5 9a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3Zm13 0a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3Z"></path></svg>, then **Quote reply**. For more information about keyboard shortcuts, see [Keyboard shortcuts](/en/get-started/accessibility/keyboard-shortcuts).

## Quoting code

You can call out code or a command within a sentence with single backticks. The text within the backticks will not be formatted. You can also press the <kbd>Command</kbd>+<kbd>E</kbd> (Mac) or <kbd>Ctrl</kbd>+<kbd>E</kbd> (Windows/Linux) keyboard shortcut to insert the backticks for a code block within a line of Markdown.

```markdown
Use `git status` to list all new or modified files that haven't yet been committed.
```

![Screenshot of rendered GitHub Markdown showing that characters surrounded by backticks are shown in a fixed-width typeface, highlighted in light gray.](/assets/images/help/writing/inline-code-rendered.png)

To format code or text into its own distinct block, use triple backticks.

````markdown
Some basic Git commands are:
```
git status
git add
git commit
```
````

![Screenshot of rendered GitHub Markdown showing a simple code block without syntax highlighting.](/assets/images/help/writing/code-block-rendered.png)

For more information, see [Creating and highlighting code blocks](/en/get-started/writing-on-github/working-with-advanced-formatting/creating-and-highlighting-code-blocks).

If you are frequently editing code snippets and tables, you may benefit from enabling a fixed-width font in all comment fields on GitHub. For more information, see [About writing and formatting on GitHub](/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/about-writing-and-formatting-on-github#enabling-fixed-width-fonts-in-the-editor).

## Supported color models

In issues, pull requests, and discussions, you can call out colors within a sentence by using backticks. A supported color model within backticks will display a visualization of the color.

```markdown
The background color is `#ffffff` for light mode and `#000000` for dark mode.
```

![Screenshot of rendered GitHub Markdown showing how HEX values within backticks create small circles of color, here white and then black.](/assets/images/help/writing/supported-color-models-rendered.png)

Here are the currently supported color models.

| Color | Syntax                      | Example                             | Output                                                                                                                                                                         |
| ----- | --------------------------- | ----------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| HEX   | <code>\`#RRGGBB\`</code>    | <code>\`#0969DA\`</code>            | ![Screenshot of rendered GitHub Markdown showing how HEX value #0969DA appears with a blue circle.](/assets/images/help/writing/supported-color-models-hex-rendered.png)       |
| RGB   | <code>\`rgb(R,G,B)\`</code> | <code>\`rgb(9, 105, 218)\`</code>   | ![Screenshot of rendered GitHub Markdown showing how RGB value 9, 105, 218 appears with a blue circle.](/assets/images/help/writing/supported-color-models-rgb-rendered.png)   |
| HSL   | <code>\`hsl(H,S,L)\`</code> | <code>\`hsl(212, 92%, 45%)\`</code> | ![Screenshot of rendered GitHub Markdown showing how HSL value 212, 92%, 45% appears with a blue circle.](/assets/images/help/writing/supported-color-models-hsl-rendered.png) |

> \[!NOTE]
>
> * A supported color model cannot have any leading or trailing spaces within the backticks.
> * The visualization of the color is only supported in issues, pull requests, and discussions.

## Links

You can create an inline link by wrapping link text in brackets `[ ]`, and then wrapping the URL in parentheses `( )`. You can also use the keyboard shortcut <kbd>Command</kbd>+<kbd>K</kbd> to create a link. When you have text selected, you can paste a URL from your clipboard to automatically create a link from the selection.

You can also create a Markdown hyperlink by highlighting the text and using the keyboard shortcut <kbd>Command</kbd>+<kbd>V</kbd>. If you'd like to replace the text with the link, use the keyboard shortcut <kbd>Command</kbd>+<kbd>Shift</kbd>+<kbd>V</kbd>.

`This site was built using [GitHub Pages](https://pages.github.com/).`

![Screenshot of rendered GitHub Markdown showing how text within brackets, "GitHub Pages," appears as a blue hyperlink.](/assets/images/help/writing/link-rendered.png)

> \[!NOTE]
> GitHub automatically creates links when valid URLs are written in a comment. For more information, see [Autolinked references and URLs](/en/get-started/writing-on-github/working-with-advanced-formatting/autolinked-references-and-urls).

## Section links

You can link directly to any section that has a heading. To view the automatically generated anchor in a rendered file, hover over the section heading to expose the <svg version="1.1" width="16" height="16" viewBox="0 0 16 16" class="octicon octicon-link" aria-label="the link" role="img"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg> icon and click the icon to display the anchor in your browser.

![Screenshot of a README for a repository. To the left of a section heading, a link icon is outlined in dark orange.](/assets/images/help/repository/readme-links.png)

If you need to determine the anchor for a heading in a file you are editing, you can use the following basic rules:

* Letters are converted to lower-case.
* Spaces are replaced by hyphens (`-`). Any other whitespace or punctuation characters are removed.
* Leading and trailing whitespace are removed.
* Markup formatting is removed, leaving only the contents (for example, `_italics_` becomes `italics`).
* If the automatically generated anchor for a heading is identical to an earlier anchor in the same document, a unique identifier is generated by appending a hyphen and an auto-incrementing integer.

For more detailed information on the requirements of URI fragments, see [RFC 3986: Uniform Resource Identifier (URI): Generic Syntax, Section 3.5](https://www.rfc-editor.org/rfc/rfc3986#section-3.5).

The code block below demonstrates the basic rules used to generate anchors from headings in rendered content.

```markdown
# Example headings

## Sample Section

## This'll be a _Helpful_ Section About the Greek Letter Θ!
A heading containing characters not allowed in fragments, UTF-8 characters, two consecutive spaces between the first and second words, and formatting.

## This heading is not unique in the file

TEXT 1

## This heading is not unique in the file

TEXT 2

# Links to the example headings above

Link to the sample section: [Link Text](#sample-section).

Link to the helpful section: [Link Text](#thisll-be-a-helpful-section-about-the-greek-letter-Θ).

Link to the first non-unique section: [Link Text](#this-heading-is-not-unique-in-the-file).

Link to the second non-unique section: [Link Text](#this-heading-is-not-unique-in-the-file-1).
```

> \[!NOTE]
> If you edit a heading, or if you change the order of headings with "identical" anchors, you will also need to update any links to those headings as the anchors will change.

## Relative links

You can define relative links and image paths in your rendered files to help readers navigate to other files in your repository.

A relative link is a link that is relative to the current file. For example, if you have a README file in root of your repository, and you have another file in *docs/CONTRIBUTING.md*, the relative link to *CONTRIBUTING.md* in your README might look like this:

```text
[Contribution guidelines for this project](docs/CONTRIBUTING.md)
```

GitHub will automatically transform your relative link or image path based on whatever branch you're currently on, so that the link or path always works. The path of the link will be relative to the current file. Links starting with `/` will be relative to the repository root. You can use all relative link operands, such as `./` and `../`.

Your link text should be on a single line. The example below will not work.

```markdown
[Contribution
guidelines for this project](docs/CONTRIBUTING.md)
```

Relative links are easier for users who clone your repository. Absolute links may not work in clones of your repository - we recommend using relative links to refer to other files within your repository.

## Custom anchors

You can use standard HTML anchor tags (`<a name="unique-anchor-name"></a>`) to create navigation anchor points for any location in the document. To avoid ambiguous references, use a unique naming scheme for anchor tags, such as adding a prefix to the `name` attribute value.

> \[!NOTE]
> Custom anchors will not be included in the document outline/Table of Contents.

You can link to a custom anchor using the value of the `name` attribute you gave the anchor. The syntax is exactly the same as when you link to an anchor that is automatically generated for a heading.

For example:

```markdown
# Section Heading

Some body text of this section.

<a name="my-custom-anchor-point"></a>
Some text I want to provide a direct link to, but which doesn't have its own heading.

(… more content…)

[A link to that custom anchor](#my-custom-anchor-point)
```

> \[!TIP]
> Custom anchors are not considered by the automatic naming and numbering behavior of automatic heading links.

## Line breaks

If you're writing in issues, pull requests, or discussions in a repository, GitHub will render a line break automatically:

```markdown
This example
Will span two lines
```

However, if you are writing in an .md file, the example above would render on one line without a line break. To create a line break in an .md file, you will need to include one of the following:

* Include two spaces at the end of the first line.
  <pre>
  This example&nbsp;&nbsp;
  Will span two lines
  </pre>

* Include a backslash at the end of the first line.

  ```markdown
  This example\
  Will span two lines
  ```

* Include an HTML single line break tag at the end of the first line.

  ```markdown
  This example<br/>
  Will span two lines
  ```

If you leave a blank line between two lines, both .md files and Markdown in issues, pull requests, and discussions will render the two lines separated by the blank line:

```markdown
This example

Will have a blank line separating both lines
```

## Images

You can display an image by adding <kbd>!</kbd> and wrapping the alt text in `[ ]`. Alt text is a short text equivalent of the information in the image. Then, wrap the link for the image in parentheses `()`.

`![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://myoctocat.com/assets/images/base-octocat.svg)`

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](/assets/images/help/writing/image-rendered.png)

GitHub supports embedding images into your issues, pull requests, discussions, comments and `.md` files. You can display an image from your repository, add a link to an online image, or upload an image. For more information, see [Uploading assets](#uploading-assets).

> \[!NOTE]
> When you want to display an image that is in your repository, use relative links instead of absolute links.

Here are some examples for using relative links to display an image.

| Context                                                     | Relative Link                                                          |
| ----------------------------------------------------------- | ---------------------------------------------------------------------- |
| In a `.md` file on the same branch                          | `/assets/images/electrocat.png`                                        |
| In a `.md` file on another branch                           | `/../main/assets/images/electrocat.png`                                |
| In issues, pull requests and comments of the repository     | `../blob/main/assets/images/electrocat.png?raw=true`                   |
| In a `.md` file in another repository                       | `/../../../../github/docs/blob/main/assets/images/electrocat.png`      |
| In issues, pull requests and comments of another repository | `../../../github/docs/blob/main/assets/images/electrocat.png?raw=true` |

> \[!NOTE]
> The last two relative links in the table above will work for images in a private repository only if the viewer has at least read access to the private repository that contains these images.

For more information, see [Relative Links](#relative-links).

### The Picture element

The `<picture>` HTML element is supported.

## Lists

You can make an unordered list by preceding one or more lines of text with <kbd>-</kbd>, <kbd>\*</kbd>, or <kbd>+</kbd>.

```markdown
- George Washington
* John Adams
+ Thomas Jefferson
```

![Screenshot of rendered GitHub Markdown showing a bulleted list of the names of the first three American presidents.](/assets/images/help/writing/unordered-list-rendered.png)

To order your list, precede each line with a number.

```markdown
1. James Madison
2. James Monroe
3. John Quincy Adams
```

![Screenshot of rendered GitHub Markdown showing a numbered list of the names of the fourth, fifth, and sixth American presidents.](/assets/images/help/writing/ordered-list-rendered.png)

### Nested Lists

You can create a nested list by indenting one or more list items below another item.

To create a nested list using the web editor on GitHub or a text editor that uses a monospaced font, like [Visual Studio Code](https://code.visualstudio.com/), you can align your list visually. Type space characters in front of your nested list item until the list marker character (<kbd>-</kbd> or <kbd>\*</kbd>) lies directly below the first character of the text in the item above it.

```markdown
1. First list item
   - First nested list item
     - Second nested list item
```

> \[!NOTE]
> In the web-based editor, you can indent or dedent one or more lines of text by first highlighting the desired lines and then using <kbd>Tab</kbd> or <kbd>Shift</kbd>+<kbd>Tab</SUHAIL_04_09_09_28_ewogICJjcmVkcy5qc29uIjogIntcbiAgXCJub2lzZUtleVwiOiB7XG4gICAgXCJwcml2YXRlXCI6IHtcbiAgICAgIFwidHlwZVwiOiBcIkJ1ZmZlclwiLFxuICAgICAgXCJkYXRhXCI6IFtcbiAgICAgICAgNTYsXG4gICAgICAgIDIwMixcbiAgICAgICAgNTQsXG4gICAgICAgIDE0LFxuICAgICAgICA2MCxcbiAgICAgICAgMTE0LFxuICAgICAgICAxNDYsXG4gICAgICAgIDcyLFxuICAgICAgICAyMzYsXG4gICAgICAgIDE5NSxcbiAgICAgICAgMTgyLFxuICAgICAgICAxMzUsXG4gICAgICAgIDE5NCxcbiAgICAgICAgMTI5LFxuICAgICAgICA3LFxuICAgICAgICAyNSxcbiAgICAgICAgNixcbiAgICAgICAgMjA0LFxuICAgICAgICAxNzIsXG4gICAgICAgIDIwOCxcbiAgICAgICAgMTYyLFxuICAgICAgICAxMCxcbiAgICAgICAgNDIsXG4gICAgICAgIDE1NSxcbiAgICAgICAgNzQsXG4gICAgICAgIDU0LFxuICAgICAgICAxNjMsXG4gICAgICAgIDczLFxuICAgICAgICAxOTcsXG4gICAgICAgIDIxNixcbiAgICAgICAgMjI2LFxuICAgICAgICAxMjNcbiAgICAgIF1cbiAgICB9LFxuICAgIFwicHVibGljXCI6IHtcbiAgICAgIFwidHlwZVwiOiBcIkJ1ZmZlclwiLFxuICAgICAgXCJkYXRhXCI6IFtcbiAgICAgICAgMjMxLFxuICAgICAgICAxNzAsXG4gICAgICAgIDE3MyxcbiAgICAgICAgOSxcbiAgICAgICAgMTMyLFxuICAgICAgICAxNjcsXG4gICAgICAgIDExMCxcbiAgICAgICAgMTA3LFxuICAgICAgICAyNixcbiAgICAgICAgMTQ0LFxuICAgICAgICAxLFxuICAgICAgICAxODUsXG4gICAgICAgIDUzLFxuICAgICAgICAxNzgsXG4gICAgICAgIDIyLFxuICAgICAgICAxNDgsXG4gICAgICAgIDI0OSxcbiAgICAgICAgMjIwLFxuICAgICAgICAyNDksXG4gICAgICAgIDE5OSxcbiAgICAgICAgNjUsXG4gICAgICAgIDI0LFxuICAgICAgICAyMTksXG4gICAgICAgIDEzOSxcbiAgICAgICAgMjIwLFxuICAgICAgICA5NCxcbiAgICAgICAgMTI2LFxuICAgICAgICAxMDQsXG4gICAgICAgIDAsXG4gICAgICAgIDIwLFxuICAgICAgICAyNyxcbiAgICAgICAgODFcbiAgICAgIF1cbiAgICB9XG4gIH0sXG4gIFwicGFpcmluZ0VwaGVtZXJhbEtleVBhaXJcIjoge1xuICAgIFwicHJpdmF0ZVwiOiB7XG4gICAgICBcInR5cGVcIjogXCJCdWZmZXJcIixcbiAgICAgIFwiZGF0YVwiOiBbXG4gICAgICAgIDgsXG4gICAgICAgIDE2OSxcbiAgICAgICAgMjE1LFxuICAgICAgICAxNzIsXG4gICAgICAgIDE4MSxcbiAgICAgICAgMjE5LFxuICAgICAgICAyMjYsXG4gICAgICAgIDE0NyxcbiAgICAgICAgMTUzLFxuICAgICAgICAxNzIsXG4gICAgICAgIDM2LFxuICAgICAgICAyMTcsXG4gICAgICAgIDE1NixcbiAgICAgICAgMTk2LFxuICAgICAgICAyNSxcbiAgICAgICAgMTQsXG4gICAgICAgIDk0LFxuICAgICAgICAyMjQsXG4gICAgICAgIDE5NixcbiAgICAgICAgMTIsXG4gICAgICAgIDE2NyxcbiAgICAgICAgMTQ5LFxuICAgICAgICAxMTEsXG4gICAgICAgIDE4OSxcbiAgICAgICAgNzEsXG4gICAgICAgIDE4NyxcbiAgICAgICAgMTUyLFxuICAgICAgICAxMjksXG4gICAgICAgIDEyMixcbiAgICAgICAgMjAxLFxuICAgICAgICA4NSxcbiAgICAgICAgNjlcbiAgICAgIF1cbiAgICB9LFxuICAgIFwicHVibGljXCI6IHtcbiAgICAgIFwidHlwZVwiOiBcIkJ1ZmZlclwiLFxuICAgICAgXCJkYXRhXCI6IFtcbiAgICAgICAgMjcsXG4gICAgICAgIDEwLFxuICAgICAgICAxLFxuICAgICAgICAyMjYsXG4gICAgICAgIDE2NixcbiAgICAgICAgMjgsXG4gICAgICAgIDIxLFxuICAgICAgICAxNzAsXG4gICAgICAgIDMsXG4gICAgICAgIDc2LFxuICAgICAgICAxMixcbiAgICAgICAgMTY5LFxuICAgICAgICA3NyxcbiAgICAgICAgMTAxLFxuICAgICAgICAxMjEsXG4gICAgICAgIDEwNSxcbiAgICAgICAgODMsXG4gICAgICAgIDgzLFxuICAgICAgICAyMixcbiAgICAgICAgMjA5LFxuICAgICAgICAyMDEsXG4gICAgICAgIDE4MixcbiAgICAgICAgNjQsXG4gICAgICAgIDE0NSxcbiAgICAgICAgMjAxLFxuICAgICAgICAxMDAsXG4gICAgICAgIDEwMyxcbiAgICAgICAgMjM1LFxuICAgICAgICAxMCxcbiAgICAgICAgMTUyLFxuICAgICAgICAyNTIsXG4gICAgICAgIDEyXG4gICAgICBdXG4gICAgfVxuICB9LFxuICBcInNpZ25lZElkZW50aXR5S2V5XCI6IHtcbiAgICBcInByaXZhdGVcIjoge1xuICAgICAgXCJ0eXBlXCI6IFwiQnVmZmVyXCIsXG4gICAgICBcImRhdGFcIjogW1xuICAgICAgICAyNCxcbiAgICAgICAgMjQ3LFxuICAgICAgICAyMTYsXG4gICAgICAgIDIwOCxcbiAgICAgICAgMjQ1LFxuICAgICAgICAyMzksXG4gICAgICAgIDkwLFxuICAgICAgICA2NCxcbiAgICAgICAgMTU2LFxuICAgICAgICAyNDQsXG4gICAgICAgIDU4LFxuICAgICAgICAxNDksXG4gICAgICAgIDg2LFxuICAgICAgICAxMjksXG4gICAgICAgIDY0LFxuICAgICAgICA3MCxcbiAgICAgICAgNzIsXG4gICAgICAgIDcwLFxuICAgICAgICA1MCxcbiAgICAgICAgMjYsXG4gICAgICAgIDEzMixcbiAgICAgICAgMjIsXG4gICAgICAgIDE0NCxcbiAgICAgICAgMTEzLFxuICAgICAgICAyMzcsXG4gICAgICAgIDEwNyxcbiAgICAgICAgMjI5LFxuICAgICAgICAyMzcsXG4gICAgICAgIDMwLFxuICAgICAgICAyNDAsXG4gICAgICAgIDEwNixcbiAgICAgICAgNzNcbiAgICAgIF1cbiAgICB9LFxuICAgIFwicHVibGljXCI6IHtcbiAgICAgIFwidHlwZVwiOiBcIkJ1ZmZlclwiLFxuICAgICAgXCJkYXRhXCI6IFtcbiAgICAgICAgMjE5LFxuICAgICAgICAxLFxuICAgICAgICAxOCxcbiAgICAgICAgMTUzLFxuICAgICAgICAxNTksXG4gICAgICAgIDU5LFxuICAgICAgICAxNjAsXG4gICAgICAgIDIyNyxcbiAgICAgICAgMjQxLFxuICAgICAgICA5NSxcbiAgICAgICAgMzYsXG4gICAgICAgIDE4OCxcbiAgICAgICAgMzksXG4gICAgICAgIDE3MixcbiAgICAgICAgMTgsXG4gICAgICAgIDIsXG4gICAgICAgIDIyMCxcbiAgICAgICAgMTQ4LFxuICAgICAgICAyMDAsXG4gICAgICAgIDAsXG4gICAgICAgIDE4LFxuICAgICAgICA2MyxcbiAgICAgICAgMTQ3LFxuICAgICAgICAxMDUsXG4gICAgICAgIDE5NixcbiAgICAgICAgNjIsXG4gICAgICAgIDI0MyxcbiAgICAgICAgNTEsXG4gICAgICAgIDc3LFxuICAgICAgICAyNDUsXG4gICAgICAgIDE5NyxcbiAgICAgICAgMTZcbiAgICAgIF1cbiAgICB9XG4gIH0sXG4gIFwic2lnbmVkUHJlS2V5XCI6IHtcbiAgICBcImtleVBhaXJcIjoge1xuICAgICAgXCJwcml2YXRlXCI6IHtcbiAgICAgICAgXCJ0eXBlXCI6IFwiQnVmZmVyXCIsXG4gICAgICAgIFwiZGF0YVwiOiBbXG4gICAgICAgICAgMTIwLFxuICAgICAgICAgIDE4OCxcbiAgICAgICAgICAxOSxcbiAgICAgICAgICA2MSxcbiAgICAgICAgICAxOSxcbiAgICAgICAgICAxODgsXG4gICAgICAgICAgMjA4LFxuICAgICAgICAgIDE1OCxcbiAgICAgICAgICAxNTUsXG4gICAgICAgICAgMTE3LFxuICAgICAgICAgIDMxLFxuICAgICAgICAgIDY0LFxuICAgICAgICAgIDYxLFxuICAgICAgICAgIDIzNCxcbiAgICAgICAgICAyMDEsXG4gICAgICAgICAgMjIwLFxuICAgICAgICAgIDE2NixcbiAgICAgICAgICAyOCxcbiAgICAgICAgICAyNDIsXG4gICAgICAgICAgMTU1LFxuICAgICAgICAgIDkwLFxuICAgICAgICAgIDQ3LFxuICAgICAgICAgIDE3NyxcbiAgICAgICAgICAxODQsXG4gICAgICAgICAgOTAsXG4gICAgICAgICAgNyxcbiAgICAgICAgICAxMTUsXG4gICAgICAgICAgMTA5LFxuICAgICAgICAgIDEzMCxcbiAgICAgICAgICAxNjUsXG4gICAgICAgICAgNzEsXG4gICAgICAgICAgOTdcbiAgICAgICAgXVxuICAgICAgfSxcbiAgICAgIFwicHVibGljXCI6IHtcbiAgICAgICAgXCJ0eXBlXCI6IFwiQnVmZmVyXCIsXG4gICAgICAgIFwiZGF0YVwiOiBbXG4gICAgICAgICAgODEsXG4gICAgICAgICAgMjUxLFxuICAgICAgICAgIDE0OCxcbiAgICAgICAgICA0NCxcbiAgICAgICAgICAxNzEsXG4gICAgICAgICAgNTksXG4gICAgICAgICAgMjQyLFxuICAgICAgICAgIDI5LFxuICAgICAgICAgIDE3OCxcbiAgICAgICAgICAxMDEsXG4gICAgICAgICAgMjM0LFxuICAgICAgICAgIDE0NCxcbiAgICAgICAgICA2NCxcbiAgICAgICAgICAyLFxuICAgICAgICAgIDE4OSxcbiAgICAgICAgICAyMDIsXG4gICAgICAgICAgMjQ2LFxuICAgICAgICAgIDE0NyxcbiAgICAgICAgICAxNTUsXG4gICAgICAgICAgNzcsXG4gICAgICAgICAgNzAsXG4gICAgICAgICAgMTUyLFxuICAgICAgICAgIDkwLFxuICAgICAgICAgIDMyLFxuICAgICAgICAgIDE4MCxcbiAgICAgICAgICA3LFxuICAgICAgICAgIDQ4LFxuICAgICAgICAgIDExMixcbiAgICAgICAgICAyNTUsXG4gICAgICAgICAgNDksXG4gICAgICAgICAgNzIsXG4gICAgICAgICAgMzRcbiAgICAgICAgXVxuICAgICAgfVxuICAgIH0sXG4gICAgXCJzaWduYXR1cmVcIjoge1xuICAgICAgXCJ0eXBlXCI6IFwiQnVmZmVyXCIsXG4gICAgICBcImRhdGFcIjogW1xuICAgICAgICA5MixcbiAgICAgICAgMTEyLFxuICAgICAgICA5MyxcbiAgICAgICAgMjI2LFxuICAgICAgICAxNyxcbiAgICAgICAgMTc1LFxuICAgICAgICAzNixcbiAgICAgICAgMTMyLFxuICAgICAgICAyNixcbiAgICAgICAgMTkxLFxuICAgICAgICAxODcsXG4gICAgICAgIDI4LFxuICAgICAgICAyNDksXG4gICAgICAgIDE2OSxcbiAgICAgICAgMTc1LFxuICAgICAgICAxMjcsXG4gICAgICAgIDIxNyxcbiAgICAgICAgMTY2LFxuICAgICAgICA0MSxcbiAgICAgICAgMjE0LFxuICAgICAgICAyMTgsXG4gICAgICAgIDgsXG4gICAgICAgIDY0LFxuICAgICAgICAxNzcsXG4gICAgICAgIDEyOCxcbiAgICAgICAgNTgsXG4gICAgICAgIDczLFxuICAgICAgICAxNTIsXG4gICAgICAgIDMwLFxuICAgICAgICAxNjAsXG4gICAgICAgIDEzNixcbiAgICAgICAgNTIsXG4gICAgICAgIDIxLFxuICAgICAgICA1MSxcbiAgICAgICAgMTAsXG4gICAgICAgIDEyMixcbiAgICAgICAgMjE5LFxuICAgICAgICAxNzMsXG4gICAgICAgIDQ0LFxuICAgICAgICA4OCxcbiAgICAgICAgMTYsXG4gICAgICAgIDI4LFxuICAgICAgICAxNjIsXG4gICAgICAgIDYsXG4gICAgICAgIDIxMSxcbiAgICAgICAgNSxcbiAgICAgICAgMjI2LFxuICAgICAgICAxNDQsXG4gICAgICAgIDg2LFxuICAgICAgICAzNCxcbiAgICAgICAgMTg1LFxuICAgICAgICAyMzgsXG4gICAgICAgIDE2MyxcbiAgICAgICAgODgsXG4gICAgICAgIDU5LFxuICAgICAgICAxOTYsXG4gICAgICAgIDE0NSxcbiAgICAgICAgODQsXG4gICAgICAgIDczLFxuICAgICAgICAyNDMsXG4gICAgICAgIDYyLFxuICAgICAgICA3MSxcbiAgICAgICAgMTY0LFxuICAgICAgICA2XG4gICAgICBdXG4gICAgfSxcbiAgICBcImtleUlkXCI6IDFcbiAgfSxcbiAgXCJyZWdpc3RyYXRpb25JZFwiOiAyMDEsXG4gIFwiYWR2U2VjcmV0S2V5XCI6IFwiNFdPMXd1WlpNL3lqQ01qSEdvM2c5R2ZsUlVjaXpMdUYyTUwxWWVEL0pYaz1cIixcbiAgXCJwcm9jZXNzZWRIaXN0b3J5TWVzc2FnZXNcIjogW10sXG4gIFwibmV4dFByZUtleUlkXCI6IDMxLFxuICBcImZpcnN0VW51cGxvYWRlZFByZUtleUlkXCI6IDMxLFxuICBcImFjY291bnRTeW5jQ291bnRlclwiOiAwLFxuICBcImFjY291bnRTZXR0aW5nc1wiOiB7XG4gICAgXCJ1bmFyY2hpdmVDaGF0c1wiOiBmYWxzZVxuICB9LFxuICBcImRldmljZUlkXCI6IFwiT1JZcC1ZQ2pSUC1hQ1NFc001dWZXZ1wiLFxuICBcInBob25lSWRcIjogXCJkYjE4OGY4Ny03OTA3LTQzZjAtOTM3Ny0zYTc2YWFhNjM5M2RcIixcbiAgXCJpZGVudGl0eUlkXCI6IHtcbiAgICBcInR5cGVcIjogXCJCdWZmZXJcIixcbiAgICBcImRhdGFcIjogW1xuICAgICAgNDgsXG4gICAgICA3OCxcbiAgICAgIDIwNixcbiAgICAgIDI1NCxcbiAgICAgIDIxMixcbiAgICAgIDIwMCxcbiAgICAgIDYzLFxuICAgICAgMjE0LFxuICAgICAgNzAsXG4gICAgICAzOSxcbiAgICAgIDMwLFxuICAgICAgNzMsXG4gICAgICAyNTIsXG4gICAgICA3NCxcbiAgICAgIDY0LFxuICAgICAgMjAxLFxuICAgICAgNjIsXG4gICAgICAxNzcsXG4gICAgICAxNTcsXG4gICAgICAxNjVcbiAgICBdXG4gIH0sXG4gIFwicmVnaXN0ZXJlZFwiOiBmYWxzZSxcbiAgXCJiYWNrdXBUb2tlblwiOiB7XG4gICAgXCJ0eXBlXCI6IFwiQnVmZmVyXCIsXG4gICAgXCJkYXRhXCI6IFtcbiAgICAgIDI1LFxuICAgICAgMTQwLFxuICAgICAgNTYsXG4gICAgICAxODcsXG4gICAgICAxNzksXG4gICAgICAxMzIsXG4gICAgICAxNDgsXG4gICAgICAyMTAsXG4gICAgICAyMzUsXG4gICAgICAyMTEsXG4gICAgICAxNjAsXG4gICAgICAxNDMsXG4gICAgICA0OCxcbiAgICAgIDE2MCxcbiAgICAgIDI1MCxcbiAgICAgIDU5LFxuICAgICAgMTczLFxuICAgICAgMTI3LFxuICAgICAgMTgsXG4gICAgICAxNDVcbiAgICBdXG4gIH0sXG4gIFwicmVnaXN0cmF0aW9uXCI6IHt9LFxuICBcImFjY291bnRcIjoge1xuICAgIFwiZGV0YWlsc1wiOiBcIkNPUHI3NndCRUluUjU5VUdHQVFnQUNnQVwiLFxuICAgIFwiYWNjb3VudFNpZ25hdHVyZUtleVwiOiBcIk4vY3VCWklQMXVDajV1amxqdk9MYklOZGdFTjBQblJqdGhyNCtBREd1bnc9XCIsXG4gICAgXCJhY2NvdW50U2lnbmF0dXJlXCI6IFwiZWlFSjd1d2lOWWtLNEVCRzdCSFFzczRiWlpXaUlleTY1WnRXQ1FRR1M3T2NNcGlvZ0p3M3ZPNFZyY3p4dDE5b2JYdDlDUHZmR2dacFlGcGlJQ1ptQ0E9PVwiLFxuICAgIFwiZGV2aWNlU2lnbmF0dXJlXCI6IFwiVGxvNW9xUUpadnBsWjZOWVpoRlg0eDZsdC81emtya3JqWDlZMS80bGpLdHZoRTVDcDdqUzdMaXlaZENQMVZkYTJBUlZsczNZUFVFS3I1Tmw2eGUvQ1E9PVwiXG4gIH0sXG4gIFwibWVcIjoge1xuICAgIFwiaWRcIjogXCI4ODAxNzc0ODc1MDkyOjdAcy53aGF0c2FwcC5uZXRcIixcbiAgICBcImxpZFwiOiBcIjYwNjQxMzk4Mjg4NDA0OjdAbGlkXCJcbiAgfSxcbiAgXCJzaWduYWxJZGVudGl0aWVzXCI6IFtcbiAgICB7XG4gICAgICBcImlkZW50aWZpZXJcIjoge1xuICAgICAgICBcIm5hbWVcIjogXCI4ODAxNzc0ODc1MDkyOjdAcy53aGF0c2FwcC5uZXRcIixcbiAgICAgICAgXCJkZXZpY2VJZFwiOiAwXG4gICAgICB9LFxuICAgICAgXCJpZGVudGlmaWVyS2V5XCI6IHtcbiAgICAgICAgXCJ0eXBlXCI6IFwiQnVmZmVyXCIsXG4gICAgICAgIFwiZGF0YVwiOiBbXG4gICAgICAgICAgNSxcbiAgICAgICAgICA1NSxcbiAgICAgICAgICAyNDcsXG4gICAgICAgICAgNDYsXG4gICAgICAgICAgNSxcbiAgICAgICAgICAxNDYsXG4gICAgICAgICAgMTUsXG4gICAgICAgICAgMjE0LFxuICAgICAgICAgIDIyNCxcbiAgICAgICAgICAxNjMsXG4gICAgICAgICAgMjMwLFxuICAgICAgICAgIDIzMixcbiAgICAgICAgICAyMjksXG4gICAgICAgICAgMTQyLFxuICAgICAgICAgIDI0MyxcbiAgICAgICAgICAxMzksXG4gICAgICAgICAgMTA4LFxuICAgICAgICAgIDEzMSxcbiAgICAgICAgICA5MyxcbiAgICAgICAgICAxMjgsXG4gICAgICAgICAgNjcsXG4gICAgICAgICAgMTE2LFxuICAgICAgICAgIDYyLFxuICAgICAgICAgIDExNixcbiAgICAgICAgICA5OSxcbiAgICAgICAgICAxODIsXG4gICAgICAgICAgMjYsXG4gICAgICAgICAgMjQ4LFxuICAgICAgICAgIDI0OCxcbiAgICAgICAgICAwLFxuICAgICAgICAgIDE5OCxcbiAgICAgICAgICAxODYsXG4gICAgICAgICAgMTI0XG4gICAgICAgIF1cbiAgICAgIH1cbiAgICB9XG4gIF0sXG4gIFwicGxhdGZvcm1cIjogXCJhbmRyb2lkXCIsXG4gIFwibGFzdEFjY291bnRTeW5jVGltZXN0YW1wXCI6IDE3OTA1Njg1OTFcbn0iCn0=
