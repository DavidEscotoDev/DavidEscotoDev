<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=David%20Escoto&fontSize=50&fontColor=fff&animation=fadeIn&fontAlignY=35&desc=16-year-old%20Developer%20%7C%20Python%20%7C%20AI%2FML%20%7C%20Trading%20Bots&descAlignY=55&descAlign=62" alt="header" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=22&duration=3000&pause=1000&color=8B5CF6&center=true&vCenter=true&width=700&lines=Self-taught+Python+developer;Building+trading+bots+and+AI+tools;Learning+distributed+systems+and+MLOps;Open+to+mentorship+and+collaboration" alt="typing animation" />
</p>

<p align="center">
  <b style="font-size: 18px; color: #c084fc;">16-year-old Developer | Python | AI/ML | Trading Bots</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/High%20School-Developer-8B5CF6?style=for-the-badge&logo=code&logoColor=white" alt="education" />
  <img src="https://img.shields.io/badge/7+%20Years%20Coding-Age%209%20to%2016-8B5CF6?style=for-the-badge&logo=lightbulb&logoColor=white" alt="experience" />
</p>

<p align="center">
  <a href="mailto:real.david.escoto@gmail.com" target="_blank"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="email" /></a>
  <a href="https://github.com/DavidEscotoDev" target="_blank"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="github" /></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=DavidEscotoDev&color=8B5CF6&style=for-the-badge&label=Profile+Views" alt="profile views" />
  <img src="https://img.shields.io/github/followers/DavidEscotoDev?color=8B5CF6&style=for-the-badge&logo=github&logoColor=white" alt="followers" />
  <img src="https://img.shields.io/github/stars/DavidEscotoDev?color=8B5CF6&style=for-the-badge&logo=github&logoColor=white" alt="stars" />
</p>

---

### About Me

Self-taught developer who wrote my first line of Python at age 9. By 16, I have shipped production-grade trading bots, a multi-agent AI framework, and a document intelligence API -- all deployed and running in the real world. I learn best by building things that work.

- **Python** -- FastAPI, asyncio, pandas, NumPy, scikit-learn, ONNX Runtime
- **Trading Systems** -- Kalshi API, Kelly criterion, VaR models, shadow-mode validation, kill-switch architecture
- **AI / ML** -- RAG pipelines, HuggingFace Transformers, FAISS vector search, LLM agent orchestration
- **Infrastructure** -- Docker, GitHub Actions, Raspberry Pi (headless), Prometheus monitoring, systemd

**Currently engineering** -- reinforcement-learning position sizing, multi-modal document parsing, Kubernetes deployment for hobby clusters.

**Seeking** -- mentorship from senior engineers, open-source collaboration, internship opportunities where I can ship real code.

---

### Tech Stack

| Category | Tools / Libraries |
|----------|-------------------|
| Languages | Python (3.10+), Bash |
| Web / API | FastAPI, Uvicorn, Pydantic, HTTPX, REST, WebSockets |
| Data / ML | pandas, NumPy, scikit-learn, HuggingFace Transformers, ONNX Runtime, FAISS |
| Trading / Finance | Kalshi API, ccxt, Kelly criterion, VaR, backtesting frameworks |
| DevOps / CI | Docker, GitHub Actions, pytest, black, ruff, Prometheus |
| Hardware | Raspberry Pi (Zero 2 W, Pi 4), headless Linux, GPIO |
| Databases | SQLite, PostgreSQL, Redis (basic) |

---

### AI / ML Expertise

| Domain | Proficiency | Details |
|--------|-------------|---------|
| Document Intelligence | Expert | OCR pipelines, layout parsing, pdfplumber, Tesseract, multi-format extraction |
| LLM Integration | Advanced | RAG with FAISS, OpenAI/Claude API, prompt engineering, agent orchestration |
| Model Serving | Advanced | FastAPI + ONNX Runtime, Dockerised inference, CPU-optimised, sub-second latency |
| Trading Algorithms | Expert | Kelly sizing, VaR 95% limits, kill-switch architecture, shadow-mode validation, backtesting |
| Multi-Agent Systems | Advanced | Agent orchestration, sandbox execution, task decomposition, code generation pipelines |
| Computer Vision | Intermediate | OCR preprocessing, image classification, Pillow, OpenCV basics |

---

### Featured Projects

<details>
<summary><strong>doc-intel-api</strong> -- Document Intelligence REST API</summary>

FastAPI service that extracts structured data from PDFs and images using OCR and layout analysis. Designed for production deployment on low-cost hardware.

| Aspect | Details |
|--------|---------|
| Stack | Python, FastAPI, Tesseract, pdfplumber, Pillow, Docker |
| Scale | ~200 requests/min on Pi 4 (4 GB) |
| Performance | Avg 350ms per page, CPU-only |
| Security | Input validation, file-type whitelist, rate limiting |
| Repo | [github.com/DavidEscotoDev/doc-intel-api](https://github.com/DavidEscotoDev/doc-intel-api) |

*Production-ready document extraction pipeline built from scratch. Handles PDFs, scanned images, and multi-page documents with structured JSON output.*
</details>

<details>
<summary><strong>Framework</strong> -- Multi-Agent Coding Assistant</summary>

Lightweight framework for orchestrating LLM-based agents that autonomously generate, review, and test code. Control plane with sandboxed execution environment.

| Aspect | Details |
|--------|---------|
| Stack | Python, FastAPI, asyncio, Docker sandbox, OpenAI-compatible API |
| Scale | 5 concurrent agents, extensible architecture |
| Performance | Agent turnaround < 2s for standard tasks |
| Safety | Container-isolated execution, static analysis hooks |
| Repo | [github.com/DavidEscotoDev/Framework](https://github.com/DavidEscotoDev/Framework) |

*Orchestration engine for autonomous code generation. Agents collaborate on complex tasks with human-in-the-loop validation.*
</details>

<details>
<summary><strong>kalshi-pi-bot</strong> -- Trading Bot for Raspberry Pi</summary>

Headless trading bot running 24/7 on a Raspberry Pi, connected to Kalshi prediction-market API. Order placement, position tracking, and risk controls.

| Aspect | Details |
|--------|---------|
| Stack | Python, asyncio, aiohttp, SQLite, systemd |
| Scale | 24/7 operation on Pi Zero 2 W, < 5% CPU |
| Reliability | Auto-reconnect, exponential backoff, health-check endpoint, Prometheus metrics |
| Repo | [github.com/DavidEscotoDev/kalshi-pi-bot](https://github.com/DavidEscotoDev/kalshi-pi-bot) |

*Always-on trading infrastructure running on $15 hardware. Combines networking, persistent state, and production monitoring.*
</details>

<details>
<summary><strong>kalshi_bot</strong> -- Advanced Trading Bot with Risk Management</summary>

Sophisticated trading system with Kelly-criterion position sizing, Value-at-Risk limits, kill-switches, and shadow-mode validator that simulates trades before committing capital.

| Aspect | Details |
|--------|---------|
| Stack | Python, asyncio, pandas, NumPy, PostgreSQL, Prometheus |
| Scale | 100+ markets simultaneously, sub-second order execution |
| Risk Controls | Kelly sizing, VaR 95%, max-drawdown guard, audit log, shadow mode |
| Repo | [github.com/DavidEscotoDev/kalshi_bot](https://github.com/DavidEscotoDev/kalshi_bot) |

*Quantitative trading system with institutional-grade risk controls. Shadow mode validates every trade decision before real execution.*
</details>

<details>
<summary><strong>PAPYRUS-AI</strong> -- LLM-Powered Document Intelligence</summary>

Natural-language interface over document collections using open-source LLMs via ONNX Runtime for fully on-device inference.

| Aspect | Details |
|--------|---------|
| Stack | Python, ONNX Runtime, FastAPI, FAISS, Streamlit |
| Scale | Indexes thousands of documents, ~1s query latency |
| Architecture | RAG pipeline with vector search, reranking, and context synthesis |
| Repo | [github.com/DavidEscotoDev/PAPYRUS-AI](https://github.com/DavidEscotoDev/PAPYRUS-AI) |

*On-device RAG engine. No cloud dependency -- runs entirely locally with privacy-first architecture.*
</details>

---

### Experience

| Period | Role | Highlights |
|--------|------|------------|
| 2023 -- Present | Independent Developer | Designed, built, and deployed 5+ production projects including trading infrastructure, AI microservices, and agent orchestration systems. Wrote CI/CD pipelines, comprehensive tests, and operational monitoring. |
| 2022 -- 2023 | High School Coding Club Lead | Founded and led weekly Python workshops. Mentored 15+ peers on Git, GitHub, and web development. Built club infrastructure with Flask and automated deployment. |

---

### Achievements

| Recognition | Details |
|-------------|---------|
| GitHub Arctic Code Vault Contributor | Code preserved in the 2025 GitHub Archive snapshot. |
| First Place -- School Hackathon (2024) | Built real-time sensor dashboard on Raspberry Pi with live data visualisation. |
| Open Source Contributor | Active contributions to Python tooling and AI/ML open-source projects. 100+ commits across public repositories. |

---

### Certifications & Credentials

**In progress / Planned:**

- **AWS Certified Cloud Practitioner** -- *Studying, exam Q4 2026*
- **Python Institute -- PCEP** (Certified Entry-Level Python Programmer) -- *Scheduled*
- **DeepLearning.AI -- TensorFlow Developer Certificate** -- *Curriculum in progress*
- **freeCodeCamp -- Scientific Computing with Python** -- *400+ hours of structured computer science curriculum completed*

Each certification represents a milestone in a structured engineering education path I designed for myself.

---

### Coding Profiles

- LeetCode -- [leetcode.com/DavidEscotoDev](https://leetcode.com/DavidEscotoDev) -- 150+ problems solved, weekly contests
- Codeforces -- [codeforces.com/profile/DavidEscotoDev](https://codeforces.com/profile/DavidEscotoDev) -- Rating 1300+, division 3

---

### GitHub Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=DavidEscotoDev&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&rank_icon=percentile&show=reviews,discussions_started,discussions_answered,prs_merged,prs_merged_percentage" alt="github stats" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=DavidEscotoDev&theme=tokyonight&hide_border=true" alt="streak stats" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=DavidEscotoDev&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="top languages" />
</p>

---

### Contribution Activity

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=DavidEscotoDev&theme=tokyo-night&hide_border=true&area=true&color=8B5CF6&line=8B5CF6&point=FFFFFF" alt="activity graph" />
</p>

---

### Contribution Snake

<p align="center">
  <img src="https://raw.githubusercontent.com/DavidEscotoDev/DavidEscotoDev/output/github-contribution-grid-snake-dark.svg" alt="snake animation" />
</p>

---

### Current Focus

```yaml
learning:
  - "Reinforcement learning for trading strategy optimisation"
  - "Kubernetes and container orchestration for ML workloads"
  - "Advanced MLOps: MLflow, DVC, model registry, A/B testing"
  - "CUDA programming and GPU-accelerated inference"
building:
  - "RL-based position sizing engine for kalshi_bot v3"
  - "Multi-modal document parser combining OCR + vision transformer"
  - "Self-hosted agent orchestration platform with web UI"
exploring:
  - "Contributing to PyTorch and HuggingFace open-source"
  - "Building a small-scale GPU cluster for distributed inference"
  - "Technical writing on trading systems and AI infrastructure"
open_to:
  - "Mentorship from senior engineers in ML/systems/trading"
  - "Part-time internship or apprenticeship -- will ship real code"
  - "Collaborative open-source projects in AI infrastructure"
```

---

### Connect

<p align="center">
  <a href="mailto:real.david.escoto@gmail.com" target="_blank"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="gmail" /></a>
  <a href="https://github.com/DavidEscotoDev" target="_blank"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="github" /></a>
</p>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" alt="footer" />
</p>

<p align="center">
  <i>"Built from scratch since age 9. Always shipping."</i>
</p>