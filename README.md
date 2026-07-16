<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=David%20Escoto&fontSize=50&fontColor=fff&animation=fadeIn&fontAlignY=35&desc=16-year-old%20Developer%20%7C%20Python%20%7C%20AI%2FML%20%7C%20Trading%20Bots&descAlignY=55&descAlign=62" alt="header" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=22&duration=3000&pause=1000&color=8B5CF6&center=true&vCenter=true&width=700&lines=Self-taught+Python+developer;Building+trading+bots+and+AI+tools;Learning+distributed+systems+and+MLOps;Open+to+mentorship+and+collaboration" alt="typing animation" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/High%20School-Developer-8B5CF6?style=for-the-badge&logo=code&logoColor=white" alt="education" />
  <img src="https://img.shields.io/badge/Self--Taught-16%20years%20old-8B5CF6?style=for-the-badge&logo=lightbulb&logoColor=white" alt="age" />
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

Self-taught developer who started coding at 13. I build practical tools with Python, focused on trading algorithms, document intelligence, and lightweight AI services. I turn ideas into working prototypes, share everything on GitHub, and learn by building.

- **Python** – FastAPI, asyncio, pandas, NumPy, scikit-learn
- **Trading** – Kalshi API, risk management, Kelly sizing, VaR limits
- **AI / ML** – ONNX Runtime, HuggingFace Transformers, FAISS, RAG pipelines
- **DevOps** – Docker, GitHub Actions, Raspberry Pi deployments

**Currently learning** – advanced async patterns, Kubernetes basics, MLOps with MLflow.

**Open to** – mentorship, open-source collaboration, part-time internship opportunities.

---

### Tech Stack

| Category | Tools / Libraries |
|----------|-------------------|
| Languages | Python (3.10+), Bash |
| Web / API | FastAPI, Uvicorn, Pydantic, HTTPX |
| Data / ML | pandas, NumPy, scikit-learn, HuggingFace Transformers, ONNX Runtime |
| Trading / Finance | Kalshi API, ccxt, custom risk modules |
| DevOps / CI | Docker, GitHub Actions, pytest, black, ruff |
| Hardware | Raspberry Pi (Pi Zero 2 W, Pi 4), headless Linux |
| Databases | SQLite, PostgreSQL (intro) |

---

### AI / ML Expertise

| Domain | Level | Details |
|--------|-------|---------|
| Document Intelligence | Intermediate | OCR pipelines, layout analysis, pdfplumber, Tesseract |
| LLM Integration | Beginner–Intermediate | OpenAI API, RAG with FAISS, prompt engineering |
| Model Serving | Intermediate | FastAPI + ONNX Runtime, Dockerised inference |
| Trading Algorithms | Intermediate | Kelly criterion, VaR, backtesting, shadow-mode validation |
| Computer Vision | Beginner | Basic OCR, image preprocessing, Pillow |

---

### Featured Projects

<details>
<summary><strong>doc-intel-api</strong> – Document Intelligence REST API</summary>

**Description** – FastAPI service that extracts structured data from PDFs and images using OCR and layout analysis. Designed for deployment on a Raspberry Pi.

| Aspect | Details |
|--------|---------|
| Stack | Python, FastAPI, Tesseract, pdfplumber, Pillow, Docker |
| Scale | ~200 requests/min on Pi 4 (4 GB) |
| Performance | Avg 350ms per page, CPU-only |
| Security | Input validation, file-type whitelist, rate limiting |
| Repo | [github.com/DavidEscotoDev/doc-intel-api](https://github.com/DavidEscotoDev/doc-intel-api) |

Built to learn async request handling, background workers, and containerising ML-light workloads.
</details>

<details>
<summary><strong>Framework</strong> – Multi-Agent Coding Assistant</summary>

**Description** – Lightweight framework for orchestrating LLM-based agents that generate, review, and test code autonomously. FastAPI control plane with sandboxed execution.

| Aspect | Details |
|--------|---------|
| Stack | Python, FastAPI, asyncio, Docker sandbox, OpenAI-compatible API |
| Scale | 5 concurrent agents tested |
| Performance | Agent turnaround < 2s |
| Safety | Code execution isolated in containers, static analysis hooks |
| Repo | [github.com/DavidEscotoDev/Framework](https://github.com/DavidEscotoDev/Framework) |

Explores agent-orchestration patterns, prompt engineering, and safe code execution.
</details>

<details>
<summary><strong>kalshi-pi-bot</strong> – Trading Bot for Raspberry Pi</summary>

**Description** – Headless trading bot running on a Raspberry Pi, connecting to Kalshi prediction-market API. Order placement, position tracking, basic risk controls.

| Aspect | Details |
|--------|---------|
| Stack | Python, asyncio, aiohttp, SQLite, systemd |
| Scale | 24/7 on Pi Zero 2 W, < 5% CPU |
| Reliability | Auto-reconnect, exponential backoff, health-check endpoint |
| Repo | [github.com/DavidEscotoDev/kalshi-pi-bot](https://github.com/DavidEscotoDev/kalshi-pi-bot) |

First project combining networking, persistent state, and hardware constraints.
</details>

<details>
<summary><strong>kalshi_bot</strong> – Advanced Trading Bot</summary>

**Description** – Sophisticated version with Kelly-criterion sizing, Value-at-Risk limits, kill-switches, and shadow-mode validator that simulates trades before committing real capital.

| Aspect | Details |
|--------|---------|
| Stack | Python, asyncio, pandas, NumPy, PostgreSQL, Prometheus |
| Scale | 100+ markets simultaneously, sub-second order latency |
| Risk Controls | Kelly sizing, VaR 95%, max-drawdown guard, audit log |
| Repo | [github.com/DavidEscotoDev/kalshi_bot](https://github.com/DavidEscotoDev/kalshi_bot) |

Focus on quantitative finance, rigorous testing, and observability.
</details>

<details>
<summary><strong>PAPYRUS-AI</strong> – LLM-Powered Document Assistant</summary>

**Description** – Prototype for natural-language questions over PDF collections. Uses small open-source LLM via ONNX Runtime for on-device inference.

| Aspect | Details |
|--------|---------|
| Stack | Python, ONNX Runtime, FastAPI, FAISS, Streamlit |
| Scale | ~1k documents on laptop, ~1s query latency |
| Goal | Learn RAG pipeline, model export, lightweight serving |
| Repo | [github.com/DavidEscotoDev/PAPYRUS-AI](https://github.com/DavidEscotoDev/PAPYRUS-AI) |

Work-in-progress learning vehicle for retrieval-augmented generation.
</details>

---

### Experience

| Period | Role | Highlights |
|--------|------|------------|
| 2023 – Present | Independent Developer | Built and deployed 5+ projects; wrote CI pipelines; maintained docs; test-driven development. |
| 2022 – 2023 | High School Coding Club Lead | Weekly Python workshops; mentored peers on Git/GitHub; built club website with Flask. |

---

### Achievements

| Recognition | Details |
|-------------|---------|
| GitHub Arctic Code Vault Contributor | Code archived in 2025 snapshot. |
| First Place – School Hackathon (2024) | Real-time sensor dashboard on Raspberry Pi. |
| Pythonista Badge (GitHub) | 100+ commits across public repos in 2025. |

---

### Certifications

- **Python Institute – PCEP** (Certified Entry-Level Python Programmer) – 2024
- **freeCodeCamp – Scientific Computing with Python** – 2023

---

### Coding Profiles

- LeetCode – [leetcode.com/DavidEscotoDev](https://leetcode.com/DavidEscotoDev)
- Codeforces – [codeforces.com/profile/DavidEscotoDev](https://codeforces.com/profile/DavidEscotoDev)

---

### GitHub Analytics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=DavidEscotoDev&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" alt="github stats" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=DavidEscotoDev&theme=tokyonight&hide_border=true" alt="streak stats" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=DavidEscotoDev&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="top languages" />
</p>

---

### GitHub Trophies

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=DavidEscotoDev&theme=tokyonight&no-frame=true&no-bg=true&margin-w=4&column=7" alt="trophies" />
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
  - "Advanced async patterns (asyncio, trio)"
  - "Model serving with FastAPI + ONNX Runtime"
  - "Kubernetes basics for hobby clusters"
building:
  - "Extend kalshi_bot with reinforcement-learning position sizing"
  - "Add multi-modal support to doc-intel-api"
  - "Deploy Framework as a self-hosted service"
exploring:
  - "Small-scale MLOps (MLflow, DVC) on a home server"
  - "Contributing to open-source Python tooling"
open_to:
  - "Mentorship from senior engineers"
  - "Part-time internship / apprenticeship"
  - "Collaborative open-source projects"
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
  <i>"Code is a way to turn curiosity into something that runs."</i>
</p>

<p align="center">
  <sub>Built from scratch at 16. Always building.</sub>
</p>