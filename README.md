<div align="center">

# 🚀 Cynet AI Studio v2.5
### The Ultimate Free, Serverless, Multi-Model AI Workspace | Zero API Keys Required

[![YouTube Main](https://img.shields.io/badge/YouTube-CynetX-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@cynetxir)
[![Telegram Channel](https://img.shields.io/badge/Telegram-@CynetX-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/cynetx)
[![Telegram Community](https://img.shields.io/badge/Group-CynetGap-0088cc?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/cynetgap)
[![Gaming Channel](https://img.shields.io/badge/YouTube-KhodeNyx-D9230F?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@khodenyx)

<br/>

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](https://opensource.org/licenses/MIT)
[![Node.js](https://img.shields.io/badge/Node.js-v16%2B-green.svg?style=flat-square)](https://nodejs.org/)
[![Powered by Puter.js](https://img.shields.io/badge/Powered%20By-Puter.js%20v2-6366f1.svg?style=flat-square)](https://puter.com)
[![Status: Production](https://img.shields.io/badge/Status-Production%20Ready-success.svg?style=flat-square)](https://github.com/)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen.svg?style=flat-square)](https://github.com/)

<p align="center">
  <b>Cynet AI Studio</b> is a cutting-edge, self-hosted web interface that gives you <b>direct, unrestricted access to the world’s most powerful frontier AI models</b> (including <b>Claude 3.5 Sonnet</b>, <b>GPT-4o</b>, <b>DeepSeek R1 Reasoner</b>, and <b>Gemini 2.0 Flash</b>) with <b>Zero Server API Keys</b>, <b>Zero Credit Card Requirements</b>, and <b>Free Monthly Allowances</b> powered by <b>Puter.js</b>.
</p>

[📖 What Is This Project?](#-what-is-cynet-ai-studio) • [🌐 Official Network](#-official-cynet-network--community) • [⚙️ How It Works](#-how-it-works-architecture-under-the-hood) • [🧠 Models & Limits](#-supported-models--comparison-matrix) • [📊 Token Economics](#-token-economics--limits-breakdown) • [🚀 Quick Start Guide](#-complete-step-by-step-guide-0-to-100) • [❓ FAQ](#-frequently-asked-questions-faq)

---

</div>

## 📖 What Is Cynet AI Studio?

Accessing cutting-edge LLMs (Large Language Models) typically requires:
1. Purchasing paid API keys from multiple vendors (Anthropic, OpenAI, Google) using international credit cards.
2. Managing complex backend servers to safely store keys.
3. Dealing with regional censorship, payment gateways, and high monthly subscription costs.

**Cynet AI Studio completely solves this problem.**

It provides a stunning, ChatGPT/Claude-style dark-mode interface that runs directly in your browser. By leveraging **Puter.js**, all AI inference requests are authenticated and billed directly to the user's free client-side allowance, completely eliminating the need for server-side API keys.

> [!TIP]
> **Zero Setup Cost**: Anyone with a free Puter account can chat with Claude 3.5 Sonnet, GPT-4o, and DeepSeek R1 immediately without paying a single cent or entering credit card information.

---

## 🌐 Official Cynet Network & Community

All project development, tutorials, and brand rights belong to the **Cynet Network**. Join our verified community hubs, access support, and explore our specialized services:

| Platform / Service | Role & Description | Direct Link |
| :--- | :--- | :--- |
| 🎬 **Official YouTube** | Main channel for full tutorials, AI guides, and tech breakdowns | [YouTube @cynetxir](https://www.youtube.com/@cynetxir) |
| 📢 **Official Telegram Channel** | Primary releases, updates, news, and direct project links | [Telegram @cynetx](https://t.me/cynetx) |
| 💬 **Telegram Supergroup** | Community discussion, Q&A, developer help, and chat | [Telegram @cynetgap](https://t.me/cynetgap) |
| 🛡️ **Cynet VPN Store** | High-speed, private, dedicated VPN services for unrestricted access | [Telegram @cynetvpnn](https://t.me/cynetvpnn) |
| 💻 **Software & Tech Hub** | Specialized tech community, software tools, and educational guides | [Telegram @cynetcommunity](https://t.me/cynetcommunity) |
| 🎮 **Gaming YouTube** | Official gameplay, streaming, and gaming videos (*KhodeNyx*) | [YouTube @khodenyx](https://www.youtube.com/@khodenyx) |
| ⛏️ **Cynet Minecraft Server** | Official gaming Minecraft server with active community | [Server Details & Config](https://t.me/cynetx/2257) |

---

## ⚙️ How It Works: Architecture Under the Hood

Unlike traditional web applications where your server needs private API tokens to talk to OpenAI or Anthropic:

```
[ Traditional Architecture ]
Browser  --->  Your Backend Server (Holds Secret API Keys $)  --->  AI Providers (Billed to Server Owner)

[ Cynet AI Studio Architecture ]
Browser  --->  Puter.js SDK (Client OAuth Session)  --->  Puter Cloud Gateway  --->  AI Providers (Billed to User's Free Tier)
```

1. **Client-Side Authentication**: When you open the studio, you authenticate via Puter's secure OAuth popup.
2. **Zero-Secret Server**: The local Node.js server (`server.js`) only serves static assets (HTML/CSS/JS). It holds **zero secrets**, makes **zero outgoing API requests**, and logs **zero chats**.
3. **Puter AI Routing**: When a prompt is sent, `puter.ai.chat()` securely relays the prompt to Puter's unified multi-model router.
4. **Local Persistence**: All chat history and messages are stored directly in your browser's `localStorage`. Your conversations are never saved to an external database.

---

## 🧠 Supported Models & Comparison Matrix

Cynet AI Studio integrates the world's most capable models under one unified selector:

| Provider | Model Name in Studio | API Identifier | Best Use Case | Reasoning & Code Capability |
| :--- | :--- | :--- | :--- | :---: |
| **Anthropic** | **Claude 3.5 Sonnet** | `claude-sonnet-5` | World-class coding, system architecture, nuanced writing | ⭐⭐⭐⭐⭐ (Industry Leader) |
| **Anthropic** | **Claude Fable 5.1** | `claude-fable-5-1` | High-precision logical deductions & complex problem-solving | ⭐⭐⭐⭐⭐ |
| **Anthropic** | **Claude 3 Opus** | `claude-opus-5` | Deep comprehension of complex multi-layered documents | ⭐⭐⭐⭐ |
| **Anthropic** | **Claude 3.5 Haiku** | `claude-haiku-4-5` | High-speed drafting, translation, instant answers | ⭐⭐⭐ |
| **OpenAI** | **GPT-4o** | `gpt-4o` | Versatile multimodal intelligence, math, creative tasks | ⭐⭐⭐⭐⭐ |
| **OpenAI** | **GPT-4o Mini** | `gpt-4o-mini` | Super-fast everyday tasks with minimal token cost | ⭐⭐⭐⭐ |
| **DeepSeek** | **DeepSeek R1 (Reasoner)** | `deepseek-reasoner` | Open-weights reasoning giant, competitive with OpenAI o1 | ⭐⭐⭐⭐⭐ |
| **DeepSeek** | **DeepSeek V3** | `deepseek-chat` | General conversational agent, natural Persian/English fluency | ⭐⭐⭐⭐ |
| **Google** | **Gemini 2.0 Flash** | `gemini-2.0-flash` | Next-generation ultra-low-latency real-time responses | ⭐⭐⭐⭐⭐ |
| **Google** | **Gemini 1.5 Pro** | `gemini-1.5-pro` | Massive context processing and technical document ingestion | ⭐⭐⭐⭐ |
| **Google** | **Gemini 1.5 Flash** | `gemini-1.5-flash` | Lightweight, efficient, fast summaries | ⭐⭐⭐ |

---

## 📊 Token Economics & Limits Breakdown

### How the Free Allowance Works
When you create a free Puter account, you automatically receive:
* **1,000 Free Credits every month** (automatically allocated).
* **25 MB Free Cloud Storage** for configs and sandbox files.
* **Sub-cent data transfer allowances**.

### Real-World Consumption & Yield

| Model | Token Cost (Output / Input) | Monthly Yield with Free 1,000 Credits | Recommended Strategy |
| :--- | :--- | :--- | :--- |
| **Claude 3.5 Sonnet** | ~0.03 credits / output token<br/>~0.006 credits / input token | **~33,000 Output Tokens**<br/>(≈ 25,000 words or ~45 comprehensive coding answers) | Use for complex code, debugging, and serious development. |
| **Claude Fable 5.1** | ~0.10 credits / output token | **~10,000 Output Tokens** | Use when mathematical rigor or deep logical deduction is required. |
| **DeepSeek V3 / R1** | Extremely economical rate | **Over 100,000+ Tokens** | Ideal for high-volume daily conversations, brainstorming, and writing. |
| **GPT-4o Mini / Gemini Flash** | Fraction of a cent per 1k tokens | **Massive Volume (150,000+ words)** | Ideal for general queries, translations, summaries, and everyday chat. |

### Monitoring Your Usage Live
Inside Cynet AI Studio:
1. Look at the lower-left sidebar under **User Profile**.
2. **Month Spend**: Displays your exact live account spending (e.g. `$0.0042`).
3. Click the **📊 View Live Usage & Tokens ↗** button to open your real-time Puter telemetry meter (`puter.com/dashboard#usage`).

> [!NOTE]
> **What happens if you run out of credits?**
> If you reach your 1,000 monthly credits limit, you can simply wait for the monthly quota reset, connect another free Puter account, or add credit balance to your Puter profile as desired.

---

## ✨ Full Feature Overview

* ⚡ **Word-by-Word Streaming**: Token generation starts within milliseconds of sending your prompt.
* 📝 **Local Markdown & Code Highlighting**:
  * Formats headers, lists, quotes, tables, and inline code cleanly using local [marked.min.js](file:///c:/Users/Norah/Documents/New%20folder%20(2)/marked.min.js).
  * Automatically inspects fenced blocks (`python`, `js`, `bash`, `html`, etc.) and adds a labeled header.
  * Dedicated **Copy Code** button with feedback (`Copied!`).
* 💾 **Multi-Session Chat History**:
  * Click **+ New Chat** to create an isolated conversation thread.
  * Sessions auto-title based on your initial prompt.
  * Switch between past conversations or delete older threads anytime.
* 🛡️ **Zero-Dependency Portable Server**:
  * Written strictly with Node.js built-ins (`http`, `fs`, `path`).
  * No `npm install`, no `node_modules`, no security vulnerabilities from untrusted packages.
* 🎮 **Bonus Canvas Mini-Game**:
  * Includes [game.html](file:///c:/Users/Norah/Documents/New%20folder%20(2)/game.html) (Classic Snake Game in Persian) with responsive touch and keyboard controls.

---

## 🚀 Complete Step-by-Step Guide (0 to 100)

Follow these simple steps to run the studio on your machine in under 2 minutes:

### Step 1: Check Prerequisites
Ensure you have [Node.js](https://nodejs.org/) installed (Version 16 or newer). Check by opening your terminal or PowerShell and typing:
```bash
node -v
```

### Step 2: Download / Clone the Repository
Download the project ZIP or clone it via git:
```bash
git clone https://github.com/cynetx/cynet-ai-studio.git
cd cynet-ai-studio
```

### Step 3: Run the Built-In Server
You do **not** need to install any packages! Just launch the server:
```bash
node server.js
```

You will see the startup banner:
```text
==================================================
  🚀 Cynet AI Studio Server is running!
  🌐 Open in browser: http://127.0.0.1:3000
==================================================
```

### Step 4: Open in Your Web Browser
Open any modern web browser (Chrome, Brave, Edge, Firefox) and navigate to:
```text
http://127.0.0.1:3000
```

> [!IMPORTANT]
> **Why can't I just double-click `index.html`?**  
> Opening web files via `file:///` blocks browser security popups and cross-origin messages (`postMessage`). Puter's OAuth gateway strictly requires an `http://` or `https://` origin. Always use the local server (`http://127.0.0.1:3000`).

### Step 5: Sign In with Puter (1-Click)
1. When the page loads, click the **Sign In with Puter** button.
2. A secure Puter authentication window will open.
3. If you don't have an account, enter a username and password to create one in 10 seconds (no credit card or email verification needed).
4. Authorize the app. The lock screen will disappear immediately and your 1,000 monthly credits are active!

### Step 6: Select Your Model & Start Chatting
* Choose your desired model from the dropdown (e.g., **Claude 3.5 Sonnet** for coding, or **DeepSeek R1** for math).
* Type your prompt in the box below and press **Enter** (use **Shift + Enter** for line breaks).
* Enjoy real-time streaming answers and syntax-highlighted code!

---

## ☁️ Free Online Hosting & Deployment

Want to host your own Cynet AI Studio on the web so you can access it from your phone or share it with friends?

### Method 1: Puter Free Cloud Hosting (Recommended)
1. Go to [puter.com](https://puter.com) and log into your desktop environment.
2. Open the **Files** app and create a folder named `cynet-studio`.
3. Upload `index.html` and `marked.min.js`.
4. Right-click the folder and select **Host this directory**.
5. You instantly get a free, public HTTPS URL (e.g., `https://username.puter.site`)!

### Method 2: Vercel / Netlify / GitHub Pages
Because Cynet AI Studio is 100% static and requires no backend secrets:
1. Push this folder to a GitHub repository.
2. Connect the repository to **Vercel**, **Netlify**, or enable **GitHub Pages** from your repo settings.
3. Your web app will build and deploy in seconds with full SSL!

---

## 🔒 Security, Privacy & Data Isolation

| Concern | How Cynet AI Studio Protects You |
| :--- | :--- |
| **API Key Theft** | There are **no server keys**. An attacker hacking your server cannot steal any OpenAI or Anthropic balance. |
| **Chat Logging** | Messages are processed in memory and saved solely to your device's browser `localStorage`. No remote logging exists. |
| **Credential Safety** | You authenticate via Puter's isolated OAuth modal. The website code never sees or stores your password. |

---

## ❓ Frequently Asked Questions (FAQ)

#### Q1: Is this completely free forever?
**Yes.** Puter provides 1,000 free credits each month to every free account. For standard daily questions and coding tasks, this allowance is generous.

#### Q2: Do I need an Iranian or foreign bank card or PayPal?
**No.** No payment method, bank card, or phone number verification is required to sign up.

#### Q3: Which model is best for coding and fixing bugs?
**Claude 3.5 Sonnet** (`claude-sonnet-5`) is widely considered the undisputed benchmark for programming, web development, refactoring, and code explanation.

#### Q4: How do I switch models in the middle of a chat?
You can select a different model in the left sidebar at any time. The next prompt you send will automatically be routed to the newly selected model.

#### Q5: Can I run this on Linux or macOS?
**Yes.** Simply run `node server.js` in your terminal on Linux or Mac. The server uses cross-platform Node.js APIs.

---

## 📁 Repository Structure Reference

```text
cynet-ai-studio/
├── .gitignore       # Standard git ignore protecting against system and log files
├── index.html       # Primary UI, styles, state management, and Puter.js chat logic
├── server.js        # Zero-dependency local Node.js HTTP server (Runs on port 3000)
├── marked.min.js    # Local lightweight Markdown parser (offline & CDN-resilient)
├── game.html        # Classic Canvas Snake Game with touch & keyboard controls
└── README.md        # Comprehensive handbook, architecture, model specs & community links
```

---

## 📄 License & Attribution

This project is open-source under the **MIT License**.

<div align="center">

**Developed with ❤️ by [Cynet Network](https://t.me/cynetx)**  
*Official Community & Tutorials: [YouTube @cynetxir](https://www.youtube.com/@cynetxir) • [Telegram @cynetx](https://t.me/cynetx)*

</div>
