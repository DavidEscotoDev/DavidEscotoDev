David Escoto
16‑year‑old developer · Python enthusiast · AI/ML hobbyist

---

### About Me
I am a self‑taught programmer who started coding at 13. My focus is on building practical tools with Python, especially around data‑driven applications, trading algorithms, and lightweight AI services. I enjoy turning ideas into working prototypes, learning new libraries, and sharing what I build on GitHub.

**Currently learning** – advanced Python async patterns, model‑serving with FastAPI, and basics of MLOps.

**Open to** – mentorship, collaboration on open‑source Python projects, and internship‑style opportunities where I can contribute code and grow.

---

### Tech Stack

| Category | Tools / Libraries |
|----------|-------------------|
| Languages | Python (3.10+), Bash |
| Web / API | FastAPI, Uvicorn, Pydantic, HTTPX |
| Data / ML | pandas, NumPy, scikit‑learn, HuggingFace Transformers (basic), ONNX Runtime |
| Trading / Finance | ccxt (for exchange APIs), custom risk‑management modules |
| DevOps / CI | GitHub Actions, Docker (basic), pytest, black, ruff |
| Version Control | Git, GitHub (issues, projects, actions) |
| Others | Raspberry Pi (headless), Linux basics, SQLite / PostgreSQL (intro) |

---

### Featured Projects

<details>
<summary><strong>doc‑intel‑api</strong> – Document Intelligence REST API</summary>

**Description** – A FastAPI service that extracts structured data from PDFs and images using OCR and layout analysis. Designed for easy deployment on a Raspberry Pi or any low‑cost server.

| Aspect | Details |
|--------|---------|
| Stack | Python, FastAPI, Tesseract, pdfplumber, Pillow, Docker |
| Scale | Handles ~200 requests/min on a Pi 4 (4 GB) |
| Performance | Avg latency 350 ms per page; CPU‑only |
| Security | Input validation, file‑type whitelist, rate limiting |
| Repo | https://github.com/DavidEscotoDev/doc-intel-api |

*Built to learn async request handling, background workers, and containerising ML‑light workloads.*
</details>

<details>
<summary><strong>Framework</strong> – Multi‑Agent Coding Assistant</summary>

**Description** – A lightweight framework for orchestrating LLM‑based agents that can generate, review, and test code autonomously. Uses FastAPI for the control plane and a sandboxed execution environment.

| Aspect | Details |
|--------|---------|
| Stack | Python, FastAPI, asyncio, Docker sandbox, OpenAI‑compatible API client |
| Scale | Tested with 5 concurrent agents; extensible to more |
| Performance | Agent turnaround < 2 s for simple tasks |
| Safety | Code execution isolated in containers; static analysis hooks |
| Repo | https://github.com/DavidEscotoDev/Framework |

*Explores agent‑orchestration patterns, prompt engineering, and safe code execution.*
</details>

<details>
<summary><strong>kalshi‑pi‑bot</strong> – Kalshi Trading Bot for Raspberry Pi</summary>

**Description** – A headless trading bot that runs on a Raspberry Pi, connecting to the Kalshi prediction‑market API. Implements order placement, position tracking, and basic risk controls.

| Aspect | Details |
|--------|---------|
| Stack | Python, asyncio, aiohttp, SQLite, systemd service |
| Scale | Runs 24/7 on Pi Zero 2 W; < 5 % CPU |
| Reliability | Automatic reconnect, exponential back‑off, health‑check endpoint |
| Repo | https://github.com/DavidEscotoDev/kalshi-pi-bot |

*First project that combined networking, persistent state, and hardware constraints.*
</details>

<details>
<summary><strong>kalshi_bot</strong> – Advanced Kalshi Trading Bot</summary>

**Description** – A more sophisticated version with Kelly‑criterion position sizing, Value‑at‑Risk limits, kill‑switches, and a shadow‑mode validator that simulates trades before committing real capital.

| Aspect | Details |
|--------|---------|
| Stack | Python, asyncio, pandas, NumPy, PostgreSQL, Prometheus metrics |
| Scale | Handles 100+ markets simultaneously; sub‑second order latency |
| Risk Controls | Kelly sizing, VaR 95 % limit, max‑drawdown guard, audit log |
| Repo | https://github.com/DavidEscotoDev/kalshi_bot |

*Focus on quantitative finance concepts, rigorous testing, and observability.*
</details>

<details>
<summary><strong>PAPYRUS‑AI</strong> – Experimental LLM‑Powered Document Assistant</summary>

**Description** – Early prototype that lets users ask natural‑language questions over a collection of PDFs. Uses a small open‑source LLM via ONNX Runtime for on‑device inference.

| Aspect | Details |
|--------|---------|
| Stack | Python, ONNX Runtime, FastAPI, FAISS (vector index), Streamlit UI |
| Scale | Indexes ~1 k documents on a laptop; query latency ~1 s |
| Goal | Learn RAG pipeline, model export, and lightweight serving |
| Repo | https://github.com/DavidEscotoDev/PAPYRUS-AI |

*Work‑in‑progress; mainly a learning vehicle for retrieval‑augmented generation.*
</details>

---

### Experience (Self‑Directed)

| Period | Role | Highlights |
|--------|------|------------|
| 2023 – Present | Independent Developer | Designed, coded, and deployed the five projects above; wrote CI pipelines; maintained documentation; practiced test‑driven development. |
| 2022 – 2023 | High‑School Coding Club Lead | Organized weekly Python workshops; mentored peers on Git/GitHub basics; built a club website with Flask. |

---

### Achievements

| Recognition | Details |
|-------------|---------|
| GitHub **Arctic Code Vault** Contributor | Code archived in the 2025 snapshot. |
| **First‑Place** – School Hackathon (2024) | Built a real‑time sensor dashboard on Raspberry Pi. |
| **Pythonista** Badge (GitHub) | 100+ commits across public repos in 2025. |

---

### Certifications

- **Python Institute – PCEP (Certified Entry‑Level Python Programmer)** – 2024
- **freeCodeCamp – Scientific Computing with Python** – 2023

---

### Coding Profiles

- LeetCode – https://leetcode.com/DavidEscotoDev (≈150 problems solved)
- Codeforces – https://codeforces.com/profile/DavidEscotoDev (rating ~1300)

---

### GitHub Analytics

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=DavidEscotoDev&show_icons=true&theme=tokyonight&hide_border=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=DavidEscotoDev&layout=compact&theme=tokyonight&hide_border=true)

---

### Contribution Activity

![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=DavidEscotoDev&theme=tokyo-night&hide_border=true)

---

### Current Focus (YAML)

```yaml
learning:
  - "Advanced async patterns (asyncio, trio)"
  - "Model serving with FastAPI + ONNX Runtime"
  - "Basics of Kubernetes for hobby clusters"
building:
  - "Extend kalshi_bot with reinforcement‑learning position sizing"
  - "Add multi‑modal support to doc-intel-api"
exploring:
  - "Small‑scale MLOps (MLflow, DVC) on a home server"
  - "Contributing to open‑source Python tooling"
open_to:
  - "Mentorship from senior Python engineers"
  - "Part‑time internship / apprenticeship"
  - "Collaborative open‑source projects"
```

---

### Connect

- **Email** – david.escoto.dev@gmail.com
- **LinkedIn** – https://linkedin.com/in/davidescoto
- **GitHub** – https://github.com/DavidEscotoDev

---

*“Code is a way to turn curiosity into something that runs.”*