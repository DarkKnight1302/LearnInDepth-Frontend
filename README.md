# ✨ LearnInDepth - Front-End Web Application

> **State-of-the-Art AI-Powered Technical Learning Engine**

LearnInDepth is a modern single-page web application (SPA) built with HTML5, Vanilla CSS3 (Dark Theme, Glassmorphism, Neon Gradients, Animations), and Vanilla JavaScript. It interfaces directly with the LearnInDepth AI Backend deployed on Azure to generate comprehensive multi-chapter courses, interactive quizzes, and hands-on coding assignments evaluated by AI.

---

## 🌟 Key Features

- 🎨 **State-of-the-Art Design**: Deep dark mode palette (`#090c15`), glowing radial background orbs, glassmorphic translucent panels (`backdrop-filter: blur(16px)`), neon gradients, smooth micro-interactions, and custom scrollbars.
- ⚡ **Instant Topic Generation**: Enter any complex technical topic (e.g. *System Design & Microservices*, *Rust Async Runtime*, *Postgres Storage Engine*) or click popular topic pills to generate custom multi-chapter learning paths.
- 📊 **Real-Time Progress Monitor**: Live polling status screen tracking chapter creation across Content, Quiz, and Assignment generation pipeline, with percent complete metrics and artifact readiness indicators.
- 📖 **Deep-Dive Chapter Reader**: Formatted HTML course material with key concepts, interview focus tags, copyable code blocks, and smooth chapter switching.
- 📝 **Interactive Quiz Engine**: Difficulty badges (`Easy`, `Medium`, `Hard`), interview-style questions, server-side grading, and a score breakdown modal with detailed explanations.
- 💻 **Solution Studio & AI Evaluator**: Problem statement breakdown, task checklists, expandable hints, solution code editor with line counts and template preloader, and instant AI Feedback report (Score, Verdict badge, What Went Well, Corrections, Interview Tips).
- 🔐 **Authentication & Quick Demo Mode**: Email OTP verification plus a one-click Quick Demo Mode for immediate zero-config testing.

---

## 🚀 Live Deployed Backend API

This front-end automatically connects to the production Azure backend:
```
https://learnindepth-cvhda0bzgsgcfsdz.centralindia-01.azurewebsites.net
```

---

## 📁 Repository Structure

```
LearnInDepth-Frontend/
├── index.html        # Main SPA HTML5 file
├── css/
│   └── styles.css    # Custom CSS Design System, Glassmorphism & Themes
└── js/
    ├── api.js        # API Client wrapper, headers, Azure URL & offline mock fallback
    ├── auth.js       # Authentication & OTP/Demo Mode controller
    ├── dashboard.js  # Hero section, topic creation & library grid
    ├── status.js     # Real-time generation progress monitor
    ├── reader.js     # Course plan outline & HTML chapter reader
    ├── quiz.js       # Interactive quiz engine & score modal
    ├── assignment.js # Coding solution studio & AI feedback evaluator
    └── app.js        # Main SPA navigation & application orchestrator
```

---

## 🛠️ Getting Started

### Option 1: Direct Browser
Simply open `index.html` in any modern web browser!

### Option 2: Local HTTP Server
Run any simple static server:
```bash
# Using Python
python3 -m http.server 8000

# Using Node npx
npx serve .
```
Navigate to `http://localhost:8000`.

---

## 🔒 License
MIT License. Created for LearnInDepth AI Learning Platform.
