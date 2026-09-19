

# `>_ PARK-BIT` 
<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=2500&pause=800&color=00F7FF&center=true&vCenter=true&width=800&lines=AI+%7C+ML+%7C+Data+Science+Student;Full-Stack+Developer+%7C+Builder;Turning+caffeine+into+models+and+shipped+features;Always+building.+Always+shipping.+Always+learning.)](https://git.io/typing-svg)


</div>

---

## `whoami`

```
$ whoami

park-bit (he/him)

$ cat /etc/profile

Final-Year B.Tech, Artificial Intelligence & Data Science
AI/ML Engineer
Full-Stack Developer
```

I'm a final-year **AI & Data Science** student who likes taking a project from idea to deployed product: the model, the API, the UI, and the pipeline that keeps it running.

I care about **local-first, privacy-respecting software**, tools that run in your browser or on your machine instead of somebody else's server.

[Portfolio](https://parthbhuskade.vercel.app/)

Currently exploring:

-  Applied ML & LLM tooling (RAG, local inference)
-  Privacy-first & encrypted systems (WebRTC, E2EE)
-  DevOps & CI/CD automation
-  Backend engineering with FastAPI & Node.js
-  Data engineering & analytics
-  Data structures & algorithms (placement prep)

---

## `tech_stack`

### AI & Machine Learning

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-FFD21E?style=for-the-badge)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google%20Gemini-4285F4?style=for-the-badge&logo=googlegemini&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-f55036?style=for-the-badge)
![Ollama](https://img.shields.io/badge/Ollama-black?style=for-the-badge)

### Data Science & Analytics

![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=white)

### Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)

### Web & Microservices

![Next.js](https://img.shields.io/badge/Next.js-black?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![WebRTC](https://img.shields.io/badge/WebRTC-333333?style=for-the-badge&logo=webrtc&logoColor=white)
![discord.py](https://img.shields.io/badge/discord.py-5865F2?style=for-the-badge&logo=discord&logoColor=white)

### Databases & Infrastructure

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

# `projects/`

##  [Nephilis](https://github.com/park-bit/Nephilis)

A privacy-focused, **end-to-end encrypted P2P chat app** (previously Cipher Mesh) built on WebRTC signaling. Messages go peer-to-peer when both sides are online. When a peer is offline, they're encrypted with the recipient's public key and queued in a zero-knowledge mailbox.
DOWNLOAD FROM RELEASES
```
Peer A ◄──────────── WebRTC (P2P) ────────────► Peer B
   │                                               │
   └──► Signaling server (auth · ICE config) ◄─────┘
                        │
                        └──► Zero-knowledge mailbox (E2E encrypted, offline peers)
```

**Stack:** `WebRTC` `ICE / STUN` `E2E Encryption` `Push Notifications`
**Highlights:** IP masking & stealth mode · zero-knowledge offline mailbox · multi-node failover with health probing · cached auth for instant app resume · versioned releases (currently v1.0.24)

---


##  [SQLide](https://github.com/park-bit/SQLide) · [live](https://sql-ide.vercel.app/)

A professional, browser-based SQL IDE for fast querying, ER-diagram visualization and schema management. Powered by **sql.js (SQLite compiled to WebAssembly)**, so everything runs in your browser's memory with no backend and no database server.

```
┌───────────┐     ┌────────────────┐     ┌───────────────┐
│ Query UI  │ ──► │ WASM SQL Core  │ ──► │ Results Grid  │
└───────────┘     └────────────────┘     └───────────────┘
        no backend · no server · your data stays in the tab
```

**Stack:** `React` `TypeScript` `Vite` `sql.js (SQLite WASM)` `Monaco Editor` `Vercel`
**Highlights:** Monaco editor with SQL autocomplete · interactive ER diagrams with foreign-key detection · schema explorer · import/export `.sqlite` files · export results to CSV/JSON

---

##  [Antarixsh](https://github.com/park-bit/Antarixsh) · [live](https://antarixsh.dev)

A competitive-programming practice platform for **TCS NQT and DSA prep**, with original problem statements, sandboxed code execution, and a head-to-head Versus mode.

```
React + Monaco ──► FastAPI ──► Supabase / Postgres
                      │
                      ├──► Piston (sandboxed execution)
                      └──► WebSocket (Versus mode)
```

**Stack:** `React` `Vite` `TypeScript` `Tailwind CSS` `FastAPI` `SQLAlchemy` `Supabase` `Piston`
**Highlights:** timed practice · bookmarks & attempt tracking · admin review page · AI-assisted test-case pipeline where ground truth always comes from real execution, never from LLM output

---

##  [Scrawny-Spend](https://github.com/park-bit/Scrawny-Spend) · [live](https://scrawnyspend.netlify.app/)

An AI-powered personal finance platform with expense tracking, automated categorization, budget prediction and real-time insights.

```
React ──► Node.js API ──► MongoDB
              │
              └──► ML pipeline ──► categorization · forecasts · insights
```

**Stack:** `React` `Node.js` `MongoDB` `Neural Networks`

---

##  [DocMeant](https://github.com/park-bit/DocMeant)

A local-first document intelligence platform for **private RAG**: semantic search, Q&A and summarization over your documents, fully offline.

```
Docs ──► Chunking ──► Embeddings ──► Vector Store
                                          │
Question ──► Retriever ◄──────────────────┘
                 │
                 ▼
     Local LLM (GPU-optimized) ──► Answer
```

**Stack:** `Python` `LangChain` `Vector Embeddings` `Ollama` `Multi-LLM`

---

##  [PasMa-desktop](https://github.com/park-bit/PasMa-desktop)

A desktop password manager and credential vault: local encrypted storage, password generation, no cloud.

```
Master Auth ──► Encrypted Local Vault ──► Credentials / Generator
```

**Stack:** `Python`

---

##  [ELstrm](https://github.com/park-bit/ELstrm)

An Android TV IPTV player, rebuilt from scratch, with D-pad-first navigation.

```
Android TV (React + Capacitor)
          │
          ▼
       FastAPI ──► M3U proxy ──► TTL cache ──► per-channel fallback
```

**Stack:** `React` `Capacitor` `FastAPI`

---

##  [LeetTrack](https://github.com/park-bit/LeetTrack)

A fully automated **LeetCode tracking bot for Discord servers**. Every midnight it pulls each user's accepted submissions from LeetCode's public GraphQL API and posts a report with streaks, leaderboards and roadmap progress. Can be hosted on Render's free tier.

```
APScheduler (midnight) ──► LeetCode GraphQL ──► Diff new solves
                                                     │
      Streaks · Leaderboards · Roadmap progress ◄────┘
                                                     │
                                      Discord embeds (edited daily)
```

**Stack:** `Python` `asyncio` `APScheduler` `LeetCode GraphQL` `Discord API`
**Highlights:** daily / weekly / monthly leaderboards · streak tracking · custom problem roadmaps · slash commands (`/status`, `/run`, `/leaderboard`) · self-healing retries with exponential backoff · atomic JSON persistence

---

##  [RunnerUP](https://github.com/park-bit/RunnerUP)

A tiny, resource-frugal Discord bot that **executes Python from fenced code blocks** and replies with the output. Built to fit Render's free tier (512 MB RAM), with every snippet run in an isolated, resource-limited subprocess.

```
Discord message ──► Code-block parser ──► AST validator ──► Rate limiter
                                                                 │
      Formatted reply ◄── Isolated subprocess (timeout · RLIMITs) ◄──┘
```

**Stack:** `Python 3.12` `discord.py` `FastAPI` `Docker` `Render` `pytest`
**Highlights:** stripped-environment subprocess so secrets never reach user code · AST checks + import blocklist · CPU / memory / time / output caps · per-user and global rate limits · designed for trusted/private servers

---

##  Experiments

Not everything ships as a polished repo. Some things are just fun:

```
Camera
   ↓
MediaPipe Hand Detection
   ↓
Gesture Classification
   ↓
Sound Trigger (via Discord bot)
```

A private Vencord plugin that turns hand gestures into soundboard triggers.

---

# `learning/`

Currently levelling up in:

- Data structures & algorithms (TCS NQT prep: aptitude, reasoning, verbal, coding)
- Applied ML & LLM tooling
- DevOps & CI/CD
- System design
- Data engineering

---

# `github_stats/`

<div align="center">

[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=park-bit&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)

![Top Languages](https://github-stats-extended.vercel.app/api/top-langs/?username=park-bit&layout=compact&theme=tokyonight&hide_border=true)

</div>



---

# `current_status`

```
╔══════════════════════════════════════════════╗
║                                              ║
║  B.Tech · AI & Data Science · Final Year     ║
║  Building → Shipping → Breaking → Fixing     ║
║                                              ║
║   AI / ML                                    ║
║   Full-Stack                                 ║
║    DevOps                                    ║
║   Data & Analytics                           ║
║   DSA                                        ║
║                                              ║
╚══════════════════════════════════════════════╝
```

---

# `connect`

[![GitHub](https://img.shields.io/badge/GitHub-park--bit-181717?style=for-the-badge&logo=github)](https://github.com/park-bit)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/parth-bhuskade)
[![](https://img.shields.io/badge/X-Follow-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/wtfuhighondude)

---

> If you're having a hard time, don't.
> *~park-bit*

<summary><b>✨ Still Here? ✨</b></summary>

```text
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣀⣀⣤⣤⣶⡴⠶⠾⠛⠛⠛⠛⠛⠛⠋⠉⠉⠉⠉⠉⠉⠉⠉⠉⠉⠉⠉⠉⠉⠉⠙⠛⠛⠓⠚⠳⠶⠶⣤⣤⣄⣀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣠⣤⣤⡶⠶⠾⠛⠛⠉⠉⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀    ⠀⠀⠀⠀⠀⠀⠀⠀⠉⠉⠛⠷⢶⣤⣀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣀⣤⣴⠶⠟⠛⠉⠉⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀    ⠀⠀⠀⠈⠙⠻⣦⣄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣠⣴⠾⠛⠉⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀     ⠙⠻⣦⡀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣴⠟⠋⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀      ⠀⠀⠀⠈⠻⣦⡀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣴⡟⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀       ⠀⠈⢿⣆⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣼⠏⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀       ⢹⣷⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⡟⠀⠀⠀⠀⠀⠰⢶⡶⠶⠆⠀⠀⠀⠀⢰⡾⠓⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢰⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠶⠄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣾⠀⠀⠀⠀⠀     ⠀⠀⢻⣇⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⣇⠀⠀⠀⠀⠀⠀⢸⡗⠀⠀⠀⠀⠀⠰⣾⡷⠦⠀⣰⠞⢳⣦⠀⣰⡞⢻⣦⠀⢸⡇⠀⠀⠀⠀⣴⠛⠷⠀⣠⡾⠷⣦⠀⠀⠀⠀⣰⡞⠳⠆⠀⣶⠀⢠⣶⠟⣶⠄⢰⡷⠷⣶⠿⣶⠀⣠⡶⢳⡗⠀⣿⠀⠀⠀⠀⠀⠀⠀⠸⣿⡄⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠘⣿⡀⠀⠀⠀⠀⠀⣸⡇⢀⠀⠀⠀⠀⠀⣸⡇⠀⠀⢿⡉⢉⣉⠀⢿⣉⠉⣉⠀⣼⡇⠀⠀⠀⢀⡉⠛⣶⠄⢿⡄⢀⣿⠀⠀⠀⠀⣉⠙⣷⡆⠀⣿⠀⢼⣇⣀⣾⠀⢸⡇⠀⣇⠀⣿⠀⣿⡀⢸⡇⠀⠛⠀⠀⠀⠀⠀⠀⠀⠀ ⣿⡇⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠙⣧⡀⠀⠀⠀⠈⠉⠉⠋⠁⠀⠀⠀⠀⠙⠁⠀⠀⠈⠉⠉⠁⠀⠀⠉⠉⠉⠀⠉⠁⠀⠀⠀⠈⠉⠛⠉⠀⠀⠙⠉⠁⠀⠀⠀⠀⠉⠉⠉⠀⠀⠉⠀⠀⠉⢉⣿⠀⠈⠁⠈⠁⠀⠉⠀⠈⠉⠉⠉⠀⠙  ⠀⠀      ⠀⣿⡇⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠘⢿⣦⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠉⠋⠋⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀         ⢰⣿⠁⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠘⠳⣦⣄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀          ⢠⣾⠃⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠙⠻⢶⣤⣀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀        ⢀⣴⠟⠉⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠙⠛⠷⢶⣤⣄⣀⣀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀      ⠀⠀⠀⣠⣴⠟⠁⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠙⠛⠛⠛⠳⠶⠶⠶⣶⠶⢶⣶⣤⣤⣤⣤⣤⣤⣀⣀⣀⣀⣀⣀⣀⣄⣀⣀⣀⣀⣀⣤⣀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣀⣤⡶⠟⠋⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠉⠉⠉⠉⠉⠉⠉⠉⠉⠉⠉⠉⢹⣿⠉⠀⠀⠀⠀⠀⠀⢰⣶⣦⣤⣤⣤⣠⣀⣤⣤⣤⣶⠶⠾⠛⠉⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⡿⠀⠀⠀⠀⠀⣠⡶⠟⠁⠀⠀⠀⠈⠉⠉⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⡏⠀⠀⠀⢀⣼⠟⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⡧⠀⠀⣴⡟⠋⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠸⣿⣴⡾⠋⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣠⢺⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡷⣤⠀⠀⠀⠀⠀⠀⠀⠀⣰⠃⠘⣷⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣠⢧⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣷⢄⠀⠀⠀⠀⠀⠀⠀⠀⢳⡈⠓⢦⣀⠀⠀⠀⠀⠀⣿⠀⠀⠹⡙⣄⠀⠀⠀⠀⠀⠀⠀⣀⡤⠚⢁⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⡆⠹⢆⡀⠀⠀⠀⠀⠀⠀⣿⠀⠀⠈⠹⢶⣀⠀⠀⣿⠀⠀⠀⢷⠈⢷⣀⣀⣀⣰⠾⠉⠀⠀⢀⡿⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣰⣿⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠻⣦⡀⠈⠙⠒⠦⣤⣀⣀⠈⠳⣄⠀⠀⠀⠈⠉⠑⠻⠄⠀⠀⠀⠀⠀⠀⠉⠀⠀⠀⠀⠰⠒⠛⠒⣒⣒⣒⣒⡶⠶⠦⠶⠒⠋⢩⡞⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠣⣕⠤⣀⠀⠀⠀⠀⠈⠉⠉⠑⠂⣀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣠⠴⠚⠉⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣀⡠⠤⠽⠒⠈⠀⠀⠀⣀⣠⠔⠊⠁⠐⠀⠀⢀⡠⠀⢀⡶⠀⠀⠠⡄⠀⢠⡀⠀⠙⠲⢄⡀⠀⠀⠀⠀⠀⠈⠉⠛⠒⠦⢤⣀⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⢀⠀⠀⠀⠀⠀⠀⠀⣀⡀⠄⠒⠊⠉⠀⠀⠀⠀⠀⠀⠀⠖⠋⠁⠀⠀⠀⢀⡠⠖⠉⠀⢀⡴⠋⠀⠀⠀⢰⠇⠀⠀⢷⠀⠀⠀⠀⠉⠲⣄⠀⢀⡀⠀⠀⠀⠀⠀⠀⠀⠉⠓⠒⠠⢄⣀⣀⣀⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠈⠙⠭⢍⣉⣉⠉⠁⠀⠀⠀⡠⠀⣀⡠⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⡠⠖⠉⠀⠀⣀⡴⠋⠀⠀⠀⠀⠀⢸⡇⠀⠀⠘⡆⠀⠀⠀⠀⠀⠈⠳⡄⡉⠢⣄⠀⠀⠀⠀⠀⠢⣄⣀⣀⣀⣈⠩⠬⠕⠋⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠈⠉⠁⢒⠔⣫⠔⠋⠁⠀⠀⠀⠀⠀⠀⠀⠀⢀⡴⠋⠀⠀⠀⠀⠀⠁⠀⠀⠀⠀⠀⡀⢠⡟⠀⢰⠆⠀⢿⠀⠀⠀⠀⠀⠀⠀⠙⢧⠀⠀⠙⢦⡀⠀⠀⠀⠀⠉⠓⠤⣄⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⢠⡴⠗⠋⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⡼⠋⠀⠀⢰⠇⠀⠀⠀⢠⠆⠀⠀⢠⠄⠀⠀⢀⡾⠁⢠⠏⡄⠀⠈⣀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠉⠀⠀⠀⠲⣄⣀⠀⠀⠈⠙⠒⠤⠤⠄⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⢀⣠⠴⠚⣁⠠⠔⠊⠀⢀⡄⠀⠀⠀⠀⠀⠀⣰⠏⠀⢀⣾⠀⢰⠃⣠⣿⠂⠂⣰⣿⠀⣤⠀⡾⢁⣴⢯⢠⠇⠀⠀⣿⠀⠀⢠⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠳⣌⠉⠉⠁⠉⠈⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⡀⠀⠠⠀⣚⠩⠄⠂⠡⠤⣰⠆⠀⣠⠟⠀⠀⡀⠀⠀⠀⠀⠀⠀⠀⣰⡇⢠⠇⣼⣿⡇⠀⣴⣿⡿⠀⣸⠞⣠⡟⢁⠇⣼⣱⠀⠀⣿⣧⠀⢸⣧⡀⠀⠀⡄⢷⠀⠀⠀⠀⠀⠀⠀⠈⠲⢄⡈⠙⢦⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⢀⣠⠔⠋⣀⠴⡾⠃⢀⡇⣼⠁⠀⠀⠀⠀⡔⠀⣴⣿⠀⡏⣼⡿⢿⡇⢰⣿⢫⢇⣜⣱⠟⠉⠀⡼⢸⣫⣽⠀⢸⣯⠻⡆⢈⣿⣷⣄⠀⠸⣸⡄⠀⣤⠈⣦⡀⣆⢠⡀⠐⠬⣓⣀⠉⠓⠤⣀⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⢀⣀⡤⠖⠥⠒⠚⠉⢁⡞⡡⢠⠟⠀⣿⠀⠀⠀⠀⢠⠟⠀⣿⠀⠀⠀⠀⢠⠇⣰⡿⢿⠰⣿⣿⣥⣼⢀⣿⢃⣾⢛⣼⣿⠂⠂⢰⣱⣿⠋⢽⠀⣾⣿⣤⣽⡀⡷⠼⢿⣆⠀⣧⣇⠀⢸⠀⣿⡽⣌⣧⢿⢦⡀⠀⣙⠢⢉⡉⠁⠉⠉⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⣠⡯⢎⡴⣫⢆⣧⣿⢀⠀⡆⠀⣸⢠⡿⣁⣚⢸⣏⣠⣤⣭⣾⣯⣽⠇⣼⣟⢻⠀⣴⣿⠿⢳⣿⡟⣰⣟⣯⣴⣦⣿⣥⣀⣈⣿⣧⠸⣗⠀⢸⢰⢹⣷⣌⠀⠘⣏⠛⠲⠤⣍⣀⣈⣓⡲⠤⠄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⢀⡼⣫⣴⠿⢋⣿⣿⣿⣿⠸⡄⡇⠀⢱⣾⣷⡿⢿⠛⣿⣿⣿⣿⠿⣿⣿⡺⠉⠙⢏⣰⠟⠃⠘⠉⠉⢽⣿⡿⢿⣿⣿⣿⣟⠛⠻⣷⣿⣇⣯⠀⣆⡟⣼⢷⣹⣧⡀⠻⣆⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⣀⣴⠟⠛⠉⠀⢠⣟⣾⡏⠛⢻⡄⣷⡱⢀⢸⠃⠉⣷⣤⣶⣿⣿⣿⣿⣿⣻⣿⣦⡄⠘⢻⠅⠀⠀⠀⣠⣴⣾⣿⣿⣿⣿⣿⣿⣿⣦⣀⡿⠁⠘⣯⠀⣿⣷⣿⠛⠋⢿⠙⠳⢿⣦⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠈⠁⠀⠀⠀⠀⠴⠛⠁⠘⣧⡀⠼⣷⣹⣿⡄⣯⣇⣼⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣀⣀⣀⣀⣀⣼⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣧⣤⣾⣏⣰⣿⣭⣿⠂⣠⡿⠀⠀⠀⠀⠉⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠉⠿⢦⣈⠙⠿⢷⣸⠹⢻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠟⠻⠿⠿⠟⠻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡏⠉⣹⣿⠿⠟⢋⣤⡾⠋⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠙⢿⣤⠀⠹⣇⠀⠙⠿⣿⣿⣿⣿⣿⣿⣿⣿⠿⠃⠠⣤⣀⢠⣤⠀⠘⠻⠿⣿⣿⣿⣿⣿⣿⡿⠟⠃⠀⢠⡿⠁⠀⣤⡿⠃⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠉⠓⠒⢻⣇⠀⠀⠀⠀⠉⠉⠉⠁⠀⠀⠀⠀⠀⠀⠉⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠁⠀⠀⠀⢀⣾⠗⠒⠛⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢿⣆⠀⠀⠀⠀⠀⠦⣤⣄⣀⣀⣀⣀⣠⣀⣀⣀⣀⣤⣤⣤⣤⡤⠶⠓⠀⠀⠀⠀⢀⣾⠏⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣿⣷⣬⣀⠀⠀⠀⠀⠀⠀⠀⠀⠶⠶⠶⠶⠶⠶⠒⠂⠀⠀⠀⠀⠀⠀⢄⣠⣶⣿⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣸⢿⣿⢹⢳⣤⣀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣤⡶⣟⣿⡟⣿⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣀⣨⣿⢻⣏⠻⢍⠳⣦⣄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣀⣤⡶⠻⠍⣾⢧⣿⣥⣤⣀⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⣿⣿⣿⣿⣿⣬⣿⣃⣂⣓⠓⠯⣟⣦⣤⣀⣀⣀⣀⣠⣴⡞⢫⣁⣡⣙⣸⣯⣥⣿⣿⣿⣿⣿⡆⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣯⣽⣝⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀
```
</details>
