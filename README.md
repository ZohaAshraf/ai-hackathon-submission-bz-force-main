<div align="center">

<img src="https://img.shields.io/badge/Built%20at-Build%20with%20AI%20Hackathon%202026-00E5FF?style=for-the-badge&logo=google&logoColor=white" />
<img src="https://img.shields.io/badge/GDG%20on%20Campus-FAST%20NUCES%20CFD-EF9F27?style=for-the-badge&logo=google&logoColor=white" />
<img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" />

<br/><br/>

# ⚡ StackSense

### AI Intelligence Layer for Technical Founders

> **The AI analyst that reads every changelog, pricing page, and deprecation notice — so you don't have to.**

<br/>

[![Live Demo](https://img.shields.io/badge/🚀%20Live%20Demo-stack--sense.web.app-00E5FF?style=for-the-badge)](https://stack-sense.web.app/)
[![Video Demo](https://img.shields.io/badge/🎥%20Video%20Demo-Watch%20Now-EF9F27?style=for-the-badge)](https://github.com/user-attachments/assets/4b510c68-9502-4deb-a4b1-be8d5f99ac49)
[![Devpost](https://img.shields.io/badge/🏆%20Devpost-Submission-E24B4A?style=for-the-badge&logo=devpost)](https://devpost.com/your-submission-link)

</div>

---

## 📋 Table of Contents

- [The Problem](#-the-problem)
- [Solution](#-solution)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Architecture](#-architecture)
- [Getting Started](#-getting-started)
- [Project Structure](#-project-structure)
- [Demo](#-demo)
- [Team](#-team)
- [Hackathon](#-hackathon)
- [License](#-license)

---

## 🎯 The Problem

Technical co-founders lose real money every week to tooling chaos they never see coming.

| What Happened | What It Cost |
|---|---|
| Gemini Flash pricing dropped 40% | Didn't notice for **3 weeks** — overpaid $240 |
| New open-source agent framework released | Could replace a **$400/month** SaaS — no bandwidth to evaluate |
| Deprecation notice buried in a changelog | Will **break an embeddings integration** in 2 weeks |
| Competitors already switched stacks | You didn't. |

> *"Technical founders spend hours every week trying to keep up with a tooling landscape that reshuffles itself faster than they can ship. Pricing changes, deprecation notices, framework releases — all buried in changelogs nobody has time to read."*

**StackSense fixes this.**

---

## 💡 Solution

StackSense is an AI-powered intelligence layer that continuously monitors your entire technical stack — pricing pages, changelogs, deprecation notices, competitor tooling — and surfaces only what matters, with dollar-denominated impact attached.

It doesn't just alert you. It tells you **how much it costs**, **what to do about it**, and **how hard it is to migrate** — all grounded in your exact architecture.

---

## ✨ Features

### 🧩 Conversational Stack Onboarding
Describe your stack in plain English. No forms, no dropdowns. Gemini parses it in real time into structured tech cards, each showing the tool name, category, and estimated monthly cost. A typewriter placeholder cycles through real founder archetypes to help you get started immediately.

### ⚡ Live Scan Engine
Hit **Scan Now**. Watch a real-time terminal feed as Gemini searches the live web across every tool in your stack — pricing pages, changelogs, release notes — all of it.

```
[14:22:01] 🔍 Scanning Vertex AI pricing page...
[14:22:03] 🔍 Reading Cohere v2 changelog...
[14:22:06] ⚡ Detected: Gemini 2.5 Flash pricing update — -40% on input tokens
[14:22:09] ⚠️  Cohere v2 embeddings endpoint deprecating in 18 days
[14:22:11] ✅ Scan complete — 2 items need your attention
```

Powered by **Gemini's streaming API + live web search**. Every result is fetched fresh, not cached. Critical findings trigger a red border flash on the terminal.

### 📊 Impact-Ranked Intelligence Dashboard
Findings surface as cinematic alert cards ranked by business impact:

- 🔴🟡🟢 **Severity tier** — Critical / Watch / FYI
- 💰 **Dollar impact** — animated counter ticking up to the exact figure
- ⚡ **Action recommendation** — specific and immediately actionable
- 📅 **Detected date + source link**
- ⏰ **Urgency chip** — *"Act within 18 days"* when time-sensitive

### 🪟 Floating Detail Windows
Click **Expand Details** on any alert to open a draggable floating panel with the full cost breakdown (current spend → new spend → monthly saving → annual saving), a migration checklist with functional checkboxes, and the direct source link. Stack multiple windows open and drag them anywhere.

### 💬 Ask Gemini — Inline Chat
Every alert card has an expandable Gemini chat pre-loaded with your full stack context and the specific finding. Ask *"How hard is it to migrate?"* or *"Will this break our current setup?"* — Gemini responds with expert, architecture-specific guidance, streamed in real time.

### 🤝 Founder Sync (Paul ↔ Sam)
Bridge the business and technical sides of your company. Load your business state (leads, deadlines, tasks, promises) and run a sync against active technical alerts. The app returns a prioritized action list for the business co-founder and highlights promise-vs-delivery conflicts — useful for both internal standups and investor due diligence.

### ⌨️ Command Palette (Cmd+K)
Press **Cmd+K** from anywhere to open a floating command palette. Ask anything in natural language — *"What's my most urgent action?"*, *"Calculate total potential savings"*, *"What changed in my AI tools this week?"* — Gemini answers with full awareness of your stack and current alerts.

### 🔍 Stack Inspector Pill
A persistent floating pill in the bottom-right corner shows live health status for every tool in your stack with color-coded indicators (green / amber / red). Click any tool to open its detail window — always one click away, never in the way.

### 📈 Runway Impact Meter
A live SVG arc gauge with a slot-machine digit counter displaying your current monthly tooling spend, savings detected this session, and projected annual runway impact. Updates dynamically as new alerts arrive.

### 🏥 Stack Health Score
Gemini scores your stack 0–100 across four dimensions:

| Dimension | What It Measures |
|---|---|
| **Cost Efficiency** | Are you overpaying for what you use? |
| **Deprecation Risk** | How close are you to a breaking change? |
| **Vendor Lock-in** | How tied are you to proprietary platforms? |
| **Competitive Modernity** | Are you running what the best teams run? |

Displayed as an animated radial gauge. Scores update after every scan.

### 📧 Weekly Digest Email Preview
Generates a ready-to-send HTML email digest. Gemini writes the subject line, body bullets, and call to action. Preview in-app and copy the HTML directly.

### 🛡️ Offline Failsafe & Robust Streaming
All Gemini-backed endpoints include resilient offline fallbacks that preserve the same data contract as live responses. The inline chat streams mock chunks in valid SSE format when Gemini is unavailable, so the UI remains fully operational during demos without an API key.

---

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| **Frontend** | React 19, TypeScript, Tailwind CSS v4 |
| **Build Tool** | Vite 6 |
| **AI Engine** | Gemini API (`gemini-2.5-flash`, `gemini-pro`) |
| **AI Features** | Streaming API, Live Web Search, Multi-turn Chat |
| **Backend** | Node.js, Express.js |
| **Containerization** | Docker |
| **Deployment — Frontend** | Firebase Hosting |
| **Deployment — Backend** | Google Cloud Run |
| **Charts & Visualization** | Recharts, HTML5 Canvas, custom SVG |
| **Animation** | Motion (Framer Motion), CSS animations |

### Google / Firebase Services Used

| Service | How It's Used |
|---|---|
| **Gemini Developer API** | Core AI engine — stack parsing, live scanning, chat, health scoring, digest generation |
| **Firebase Hosting** | Production hosting for the React/Vite frontend |
| **Google Cloud Run** | Serverless containerized deployment for the Express.js backend proxy |
| **Google AI Studio** | Prompt engineering, architecture planning, and frontend scaffolding |
| **Antigravity / Project IDX** | Initial project bootstrapping and environment scaffolding |

### Why Gemini Is Non-Negotiable

Remove Gemini and the product is nothing. Gemini performs live web searches across unstructured changelog text, filters findings by relevance to a specific founder's stack, estimates dollar impact from pricing page data, and provides contextual migration advice — none of which is achievable with a rule-based system or a simple feed aggregator. The streaming API makes the live terminal experience feel real, not simulated.

---

## 🏗 Architecture

```
┌─────────────────────────────────────────────────────────────┐
│                        React Frontend                        │
│  Onboarding → Stack Cards → Scan Terminal → Alert Dashboard  │
│         Command Palette · Stack Inspector · Gauges           │
└───────────────────────────┬─────────────────────────────────┘
                            │ REST + SSE
┌───────────────────────────▼─────────────────────────────────┐
│               Express.js Backend (Cloud Run)                 │
│    /api/parse-stack  /api/scan  /api/ask  /api/sync          │
│         Gemini streaming proxy + offline failsafe            │
└───────────────────────────┬─────────────────────────────────┘
                            │ Gemini API
┌───────────────────────────▼─────────────────────────────────┐
│                  Google Gemini API                           │
│        gemini-2.5-flash (speed) · gemini-pro (reasoning)    │
│            Live Web Search Tool · Streaming                  │
└─────────────────────────────────────────────────────────────┘
```

---

## 🚀 Getting Started

### Prerequisites

- Node.js ≥ 18
- A [Gemini API key](https://aistudio.google.com/app/apikey)
- Docker (optional, for running the backend locally in a container)

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/your-username/stacksense.git
cd stacksense

# 2. Install frontend dependencies
npm install

# 3. Install backend dependencies
cd backend && npm install && cd ..

# 4. Set up environment variables
cp .env.example .env.local
```

Edit `.env.local` and add your API key:

```env
GEMINI_API_KEY=your_gemini_api_key_here
FRONTEND_ORIGIN=http://localhost:3000
```

### Running Locally

```bash
# Start the backend (from /backend)
cd backend
node src/index.js

# Start the frontend (from root, in a separate terminal)
npm run dev
```

The frontend runs at **`http://localhost:3000`**  
The backend runs at **`http://localhost:8787`**

### Running with Docker

```bash
# Build and run the backend container
cd backend
docker build -t stacksense-backend .
docker run -p 8787:8787 --env GEMINI_API_KEY=your_key stacksense-backend
```

---

## 📁 Project Structure

```
stacksense/
├── src/
│   ├── App.tsx                    # Root component — screen routing & global state
│   ├── main.tsx                   # Entry point
│   ├── types.ts                   # TypeScript interfaces & enums
│   ├── index.css                  # Design tokens + global styles
│   ├── components/
│   │   ├── AlertCard.tsx          # Impact-ranked alert cards with dollar counter
│   │   ├── ArchitectureView.tsx   # Mermaid.js architecture diagram renderer
│   │   ├── Dashboard.tsx          # Main dashboard with tab navigation
│   │   ├── InsightsTab.tsx        # Stack insights and trend analysis
│   │   ├── Onboarding.tsx         # Conversational stack input with typewriter UX
│   │   ├── RunwayProjections.tsx  # Runway impact SVG gauge + slot-machine counter
│   │   ├── Sidebar.tsx            # Navigation sidebar
│   │   ├── StackManager.tsx       # Tech card grid with parsed stack items
│   │   ├── TerminalView.tsx       # Real-time streaming scan terminal
│   │   └── WeeklyDigest.tsx       # Gemini-generated email digest preview
│   ├── services/
│   │   ├── api.ts                 # Backend API client (fetch + SSE helpers)
│   │   └── geminiService.ts       # Direct Gemini client for frontend calls
│   └── lib/
│       └── utils.ts               # Shared utility functions
├── backend/
│   ├── src/
│   │   └── index.js               # Express server — all /api routes
│   ├── Dockerfile
│   ├── .dockerignore
│   └── package.json
├── index.html
├── vite.config.ts
├── tsconfig.json
├── firebase.json
├── .firebaserc
└── package.json
```

---

## 🎬 Demo

> **[▶ Watch the 2-minute demo →](https://your-video-url-here.com)**

**Walkthrough:**

1. **Boot screen** — cinematic intro animation plays
2. **Onboarding** — stack is entered in plain English; typewriter placeholder shows real founder examples
3. **Tech cards** spring into view — each tool parsed, categorized, and costed
4. **Scan Now** — Gemini searches the live web; terminal fills in real time with streaming output
5. **Alert cards** animate in: a pricing drop and an upcoming deprecation, both with dollar figures
6. **Expand Details** — draggable floating window opens with full cost breakdown and migration checklist
7. **Ask Gemini** on the pricing alert — *"How hard is it to migrate?"* — a streaming migration plan appears
8. **Cmd+K** palette opens — *"What's my most urgent action?"* — instant answer
9. **Health score** and **runway gauge** animate into view with live data

---

## 👥 Team

| Name | Role | GitHub | LinkedIn |
|---|---|---|---|
| **Zoha Ashraf** | Co-founder · Frontend & AI Integration | [github.com/zoha-ashraf](https://github.com/zoha-ashraf) | [linkedin.com/in/zoha-ashraf](https://linkedin.com/in/zoha-ashraf) |
| **Bilal Rauf** | Co-founder · Backend & Deployment | [github.com/bilal-rauf](https://github.com/bilal-rauf) | [linkedin.com/in/bilal-rauf](https://linkedin.com/in/bilal-rauf) |

---

## 🏆 Hackathon

Built at **Build with AI Hackathon 2026**  
Organized by **GDG on Campus, FAST NUCES CFD**

[![Hackathon](https://img.shields.io/badge/Event-Build%20with%20AI%202026-00E5FF?style=flat-square)](https://your-hackathon-event-link.com)
[![Devpost](https://img.shields.io/badge/Submission-Devpost-003E54?style=flat-square&logo=devpost)](https://devpost.com/your-submission-link)

---

## 📄 License

MIT © 2026 Zoha Ashraf & Bilal Rauf — see [LICENSE](LICENSE) for details.

---

<div align="center">

*If StackSense would've saved Sam $340/month — give it a ⭐*

**[stack-sense.web.app](https://stack-sense.web.app/) · Built with Gemini · GDG on Campus FAST NUCES CFD**

</div>
