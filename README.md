<div align="center">

# 🚀 Cynet AI Studio v2.5
### Next-Gen Serverless AI Workspace | Zero Backend API Keys Required

[![YouTube Main](https://img.shields.io/badge/YouTube-CynetX-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@cynetxir)
[![Telegram Channel](https://img.shields.io/badge/Telegram-@CynetX-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/cynetx)
[![Telegram Community](https://img.shields.io/badge/Group-CynetGap-0088cc?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/cynetgap)
[![Gaming Channel](https://img.shields.io/badge/YouTube-KhodeNyx-D9230F?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@khodenyx)

<br/>

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](https://opensource.org/licenses/MIT)
[![Node.js](https://img.shields.io/badge/Node.js-v16%2B-green.svg?style=flat-square)](https://nodejs.org/)
[![Powered by Puter.js](https://img.shields.io/badge/Powered%20By-Puter.js%20v2-6366f1.svg?style=flat-square)](https://puter.com)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen.svg?style=flat-square)](https://github.com/)

<p align="center">
  <b>Cynet AI Studio</b> is an ultra-fast, modern, privacy-focused web interface designed to interact with cutting-edge Large Language Models (including <b>Claude 3.5 Sonnet</b>, <b>GPT-4o</b>, <b>DeepSeek R1 Reasoner</b>, and <b>Gemini 2.0 Flash</b>) with <b>Zero Server API Keys</b> and <b>Free Monthly Allowances</b> powered by <b>Puter.js</b>.
</p>

[🌐 Official Network](#-official-cynet-network--community) • [✨ Key Features](#-key-features) • [🧠 Supported Models](#-supported-ai-models) • [📊 Token Economics](#-token-economics--free-quota) • [🚀 Quick Start](#-quick-start) • [☁️ Deployment](#️-deployment)

---

</div>

## 🌐 Official Cynet Network & Community

All intellectual property, development, and brand rights belong to the **Cynet Network**. Connect with our official communities, tools, gaming channels, and services through the verified channels below:

| Platform / Service | Description | Direct Access Link |
| :--- | :--- | :--- |
| 🎬 **Official YouTube** | Main channel for AI tutorials, tech reviews, and development | [YouTube @cynetxir](https://www.youtube.com/@cynetxir) |
| 📢 **Official Telegram** | Primary announcements, software releases, and updates | [Telegram @cynetx](https://t.me/cynetx) |
| 💬 **Telegram Supergroup** | Community discussion, Q&A, developer support, and chat | [Telegram @cynetgap](https://t.me/cynetgap) |
| 🛡️ **Cynet VPN Store** | High-speed, secure, and dedicated private VPN services | [Telegram @cynetvpnn](https://t.me/cynetvpnn) |
| 💻 **Software & Community** | Specialized software hub, security tools, and tech community | [Telegram @cynetcommunity](https://t.me/cynetcommunity) |
| 🎮 **Gaming YouTube** | Official gaming, streaming, and gameplay channel (*KhodeNyx*) | [YouTube @khodenyx](https://www.youtube.com/@khodenyx) |
| ⛏️ **Cynet Minecraft Server** | Official Cynet MC gaming server & server configuration | [Server Post & Details](https://t.me/cynetx/2257) |

---

## ✨ Key Features

* 🔑 **Zero Backend API Keys**: Eliminate the need to store expensive OpenAI, Anthropic, or Google API keys on your backend server. All authentication and model execution are handled client-side via the user's free Puter account.
* ⚡ **Real-Time Token Streaming**: Experience instantaneous token-by-token generation with smart auto-scrolling.
* 📝 **Local High-Performance Markdown Engine**:
  * Bundled with an offline, lightweight parser ([marked.min.js](file:///c:/Users/Norah/Documents/New%20folder%20(2)/marked.min.js)).
  * Automatic programming language detection (`python`, `javascript`, `cpp`, `html`, `bash`, `sql`, etc.).
  * Dedicated code headers with a one-click **Copy Code** button and visual feedback (`Copied!`).
* 💾 **Persistent Multi-Session History**: Organize distinct chats with ease. Sessions are stored in the browser's `localStorage`, allowing you to switch between chats or delete them at any time.
* 📊 **Transparent Quota Meter**: Live tracking of your monthly usage and spending, complete with a direct shortcut to the Puter token consumption dashboard.
* 🛡️ **Zero-Dependency Lightweight Server**: Built purely on Node.js core modules (`http`, `fs`, `path`). Runs immediately without requiring an oversized `node_modules` directory!

---

## 🧠 Supported AI Models

Cynet AI Studio provides direct access to industry-leading frontier models across top AI providers:

```text
├── 🟣 Anthropic Claude
│   ├── Claude 3.5 Sonnet (State-of-the-art coding and analytical reasoning)
│   ├── Claude Fable 5.1 (Deep step-by-step logic)
│   ├── Claude 3 Opus (High complexity contextual comprehension)
│   └── Claude 3.5 Haiku (Ultra-fast and cost-efficient)
├── 🟢 OpenAI
│   ├── GPT-4o (Frontier Multimodal flagship)
│   └── GPT-4o Mini (High-speed balanced model)
├── 🔵 DeepSeek
│   ├── DeepSeek R1 Reasoner (Advanced reasoning & math)
│   └── DeepSeek V3 (General conversation & coding)
└── 🟠 Google Gemini
    ├── Gemini 2.0 Flash (Next-gen rapid generation)
    ├── Gemini 1.5 Pro (Long-context multimodal reasoning)
    └── Gemini 1.5 Flash (Lightweight, ultra-fast responses)
```

---

## 📊 Token Economics & Free Quota

Every user receives **1,000 free monthly credits** upon signing into their Puter account:

* **Claude 3.5 Sonnet / Sonnet 5**:
  * Output tokens: ~30 credits per 1,000 tokens (~0.03 credits/token).
  * Input tokens: ~6 credits per 1,000 tokens.
  * Yield: **~33,000 output tokens** (~25,000 words) completely free every month per account!
* **DeepSeek V3 & GPT-4o Mini**:
  * Minimal credit consumption with substantial conversation allowances.
* **Free Cloud Storage**:
  * 25 MB free cloud file storage included for user persistence and configurations.

---

## 📁 Project Structure

```text
cynet-ai-studio/
├── index.html       # Complete frontend interface, styles, and Puter.js integration
├── server.js        # Zero-dependency local Node.js HTTP server (Port 3000)
├── marked.min.js    # Local lightweight Markdown parser (offline & CDN-resilient)
├── game.html        # Classic Canvas Snake Game with touch & keyboard controls
└── README.md        # Comprehensive documentation, network links, and setup guide
```

---

## 🚀 Quick Start

### Prerequisites
* [Node.js](https://nodejs.org/) (Version 16 or higher).
* Any modern web browser (Chrome, Edge, Firefox, Brave, Safari).

### 1. Clone or Download the Repository
```bash
git clone https://github.com/cynetx/cynet-ai-studio.git
cd cynet-ai-studio
```

### 2. Launch the Built-in Server
No `npm install` needed! Simply start the server:
```bash
node server.js
```

Console output:
```text
==================================================
  🚀 Cynet AI Studio Server is running!
  🌐 Open in browser: http://127.0.0.1:3000
==================================================
```

### 3. Open in Your Browser
Navigate to:
```text
http://127.0.0.1:3000
```

> **Security Note**: Due to browser OAuth popup security protocols, opening `index.html` via `file:///` is restricted by Puter.js. Always run it via `http://localhost:3000` or deploy it to a live static web server.

---

## ☁️ Deployment

Because Cynet AI Studio is client-driven and requires no server-side secrets:

1. **Puter Hosting (One-Click Free Hosting)**:
   - Upload the project directory to your Puter drive and enable public hosting instantly.
2. **GitHub Pages / Vercel / Netlify**:
   - Push this repository to GitHub.
   - Deploy [index.html](file:///c:/Users/Norah/Documents/New%20folder%20(2)/index.html) and [marked.min.js](file:///c:/Users/Norah/Documents/New%20folder%20(2)/marked.min.js) as a static site.

---

## 🔒 Security & Privacy

- **No Server Secrets**: Eliminates the risk of private API key leaks.
- **Local Chat Storage**: Chat sessions are stored solely in the client's browser `localStorage` and never transmitted to unauthorized databases.
- **Secure OAuth**: User authentication is handled directly through Puter's isolated authentication layer.

---

## 📄 License & Attribution

This project is open-source and released under the [MIT License](LICENSE).

<div align="center">

**Developed with ❤️ by [Cynet Network](https://t.me/cynetx)**  
*Empowering developers and creators with serverless AI tools*

</div>
