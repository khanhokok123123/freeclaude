# Cynet AI Studio 🚀

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Node.js](https://img.shields.io/badge/Node.js-v16%2B-green.svg)](https://nodejs.org/)
[![Powered by Puter.js](https://img.shields.io/badge/Powered%20By-Puter.js-6366f1.svg)](https://puter.com)
[![Status](https://img.shields.io/badge/Status-Production%20Ready-success.svg)]()

**Cynet AI Studio** is a modern, lightweight, privacy-focused AI web interface that allows users to chat with cutting-edge Large Language Models (**Claude 3.5 Sonnet**, **Claude Sonnet 5**, **Claude Fable 5.1**, **GPT-4o**, **DeepSeek R1 Reasoner**, **Gemini 2.0 Flash**, and more) with **Zero Server API Keys** and **Free Client-Side Allowances** powered by [Puter.js](https://puter.com).

---

## ✨ Features

- 🔑 **Zero Backend API Keys**: No need to provide Anthropic, OpenAI, or Google API keys on your backend server. All requests are authenticated client-side via the user's free Puter account.
- 🧠 **Multi-Vendor Frontier Models**:
  - **Anthropic:** Claude 3.5 Sonnet (`claude-3-5-sonnet`), Claude Sonnet 5 (`claude-sonnet-5`), Claude Fable 5.1 (`claude-fable-5-1`), Claude 3 Opus, Claude 3.5 Haiku.
  - **OpenAI:** GPT-4o, GPT-4o Mini.
  - **DeepSeek:** DeepSeek R1 (Reasoner), DeepSeek V3.
  - **Google:** Gemini 2.0 Flash, Gemini 1.5 Pro, Gemini 1.5 Flash.
- ⚡ **Real-Time Streaming**: Instant word-by-word token streaming with dynamic auto-scrolling.
- 📝 **Full Markdown & Code Syntax Highlighting**:
  - High-performance local Markdown parser (`marked.min.js`).
  - Automatic language badge tags (`js`, `python`, `html`, `bash`, etc.).
  - One-click **Copy Code** button with visual feedback.
- 💾 **Local Multi-Session History**: Persistent chats stored directly in browser `localStorage`. Create new sessions, switch seamlessly, or delete chats anytime.
- 🔒 **Auth-Gated UI**: Ensures proper authentication before prompting. Shows live username and monthly spend status.
- 📊 **Quota & Usage Transparency**: Direct shortcut to the live Puter usage meter (`puter.com/dashboard#usage`) to monitor exact tokens and credit consumption.
- 🛡️ **Zero External Dependency Server**: Runs with standard Node.js built-ins (`http`, `fs`, `path`). No heavy `node_modules` required!

---

## 📊 Token Economics & Free Quota

Each user receives **1,000 free monthly credits** upon signing into their Puter account. 

According to live telemetry from the Puter metering backend:
- **Claude Sonnet 5**:
  - Output tokens: ~30 credits per 1,000 tokens (~0.03 credits/token).
  - Input tokens: ~6 credits per 1,000 tokens (~0.006 credits/token).
  - Yield: **~33,000 output tokens** (~25,000 words) completely free per account!
- **Claude Fable 5.1**:
  - Output tokens: ~100 credits per 1,000 tokens (~0.1 credits/token).
  - High-precision reasoning architecture.
- **Storage & Bandwidth**:
  - 25 MB cloud storage included for free.
  - Sub-cent egress and key-value database operations.

---

## 📁 Project Structure

```text
cynet-ai-studio/
├── index.html       # Complete frontend interface, styles, and Puter.js integration
├── server.js        # Zero-dependency local Node.js HTTP server
├── marked.min.js    # Local lightweight Markdown parser (offline & CDN-resilient)
└── README.md        # Documentation and setup instructions
```

---

## 🚀 Quick Start

### Prerequisites
- [Node.js](https://nodejs.org/) (version 16 or higher installed).
- A modern web browser (Chrome, Edge, Firefox, Brave, Safari).

### 1. Clone or Download the Repository
```bash
git clone https://github.com/your-username/cynet-ai-studio.git
cd cynet-ai-studio
```

### 2. Start the Server
Run the built-in zero-dependency server:
```bash
node server.js
```

You should see output similar to:
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

> **Note**: Due to browser security protocols, opening `index.html` directly as `file:///` is not supported by Puter.js. Always run it via `http://localhost:3000` or host it on any static web host (e.g. Vercel, Netlify, GitHub Pages, or Puter Hosting).

---

## 🛠️ Deployment

Because Cynet AI Studio is fully client-side and requires no server-side secrets:

1. **GitHub Pages / Vercel / Netlify**:
   - Push this directory to GitHub.
   - Deploy `index.html` and `marked.min.js` directly as static files.
2. **Puter Hosting**:
   - Host it directly on your Puter drive with zero configuration!

---

## 🔒 Security & Privacy

- **No Secrets on Server**: You don't have to keep expensive API keys on a private server.
- **Client-Side Storage**: Chat logs are stored locally in the user's browser `localStorage` and are never dispatched to unauthorized third parties.
- **Official Authentications**: User credentials are handled safely via Puter's secure OAuth flow.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE). Feel free to use, customize, and build upon it!
