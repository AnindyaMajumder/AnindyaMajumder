```
╔══════════════════════════════════════════════════════════════════╗
║  anindya@systems:~$  whoami                                      ║
╚══════════════════════════════════════════════════════════════════╝
```

**AI Software Engineer** — I build intelligent systems that actually ship.

My stack lives at the intersection of **Agentic AI**, **RAG pipelines**, **backend architecture**, and **automated deployment**. I don't just build models — I build the infrastructure around them.

→ &nbsp;`Agentic AI` &nbsp;`RAG Pipelines` &nbsp;`Backend Engineering` &nbsp;`CI/CD Automation` &nbsp;`Workflow Orchestration`

<br>

<div align="center">

[![Portfolio](https://img.shields.io/badge/anindya.pro-0d1117?style=for-the-badge&logo=firefox&logoColor=79c0ff&labelColor=161b22)](https://anindya.pro)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0d1117?style=for-the-badge&logo=linkedin&logoColor=79c0ff&labelColor=161b22)](https://linkedin.com/in/anindya-majumder)
&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-0d1117?style=for-the-badge&logo=github&logoColor=79c0ff&labelColor=161b22)](https://github.com/AnindyaMajumder)
&nbsp;
![Visitors](https://komarev.com/ghpvc/?username=AnindyaMajumder&style=for-the-badge&color=161b22&labelColor=161b22&label=VISITORS&abbreviated=true)

</div>

---

## ⬡ &nbsp;system architecture

```
                    ┌──────────────────────────────────────────────────────────┐
                    │           ANINDYA MAJUMDER  //  AI ENGINEER              │
                    └───────────────────────────┬──────────────────────────────┘
                                                │
             ┌──────────────────────────────────┼─────────────────────────────────┐
             │                                  │                                 │
             ▼                                  ▼                                 ▼
  ┌───────────────────────┐       ┌─────────────────────────┐       ┌──────────────────────────┐
  │      DATA LAYER       │       │      AGENT LAYER        │       │   ORCHESTRATION LAYER    │
  │                       │       │                         │       │                          │
  │  PostgreSQL           │──────▶│  LangGraph              │──────▶│  n8n  ·  GitHub Actions  │
  │  MongoDB  ·  Neo4j    │       │  LangChain  ·  ADK      │       │  Docker  ·  Kubernetes   │
  │  ChromaDB  ·  FAISS   │       │  Graph-RAG  ·  RAG      │       │  AWS  ·  VPS             │
  │  PineCone             │       │  Custom MCP Servers     │       │  Playwright  ·  Scrapy   │
  └───────────────────────┘       └─────────────────────────┘       └──────────────────────────┘
             │                                  │                                 │
             └──────────────────────────────────┼─────────────────────────────────┘
                                                │
                                                ▼
                                  ┌─────────────────────────┐
                                  │      SERVING LAYER      │
                                  │                         │
                                  │  FastAPI  ·  REST APIs  │
                                  │  Spring Boot            │
                                  │  Microservices  ·  JWT  │
                                  └─────────────────────────┘
```

---

## ⬡ &nbsp;core.config

```yaml
# anindya.yaml — v2026

name:       Anindya Majumder
role:       AI Software Engineer
location:   Dhaka, Bangladesh
status:     active
currently:  RiseUp Labs Ltd.  →  AI Workflow Automation Engineer

specialisations:
  - agentic_systems        # multi-agent architectures, MCP servers, tool-use
  - rag_pipelines          # graph-RAG, re-rankers, semantic search, VectorDBs
  - backend_engineering    # FastAPI, Spring Boot, REST, microservices
  - workflow_automation    # n8n, Playwright, Scrapy, LLM-powered pipelines
  - devops                 # Docker, Kubernetes, GitHub Actions, AWS, CI/CD

open_to:
  - research_collaboration
  - backend_and_ai_roles
  - open_source_projects
```

---

## ⬡ &nbsp;deployed.services

```
  ┌──────────────────────────────────────────────────────────────────────────────┐
  │  SERVICES //  PRODUCTION                                                     │
  └──────────────────────────────────────────────────────────────────────────────┘

  ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  SERVICE  :  AI Lawyer  —  Personal Legal Assistant
  DESC     :  Graph-RAG legal assistant with Neo4j knowledge graph
              and Ragas QA validation pipeline
  STACK    :  Python  ·  Graph RAG  ·  Neo4j  ·  Ragas
  STATUS   :  ● RUNNING

  ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  SERVICE  :  Online Journal Publishing Platform
  DESC     :  Full-stack publishing platform — JWT auth via Spring Security 6,
              BART-powered auto-summaries, push notifications & admin moderation
  STACK    :  Spring Boot  ·  React  ·  MongoDB  ·  BART
  REPO     :  github.com/AnindyaMajumder/Online-Journal-Publishing-Platform
  STATUS   :  ● RUNNING

  ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  SERVICE  :  WatchDog  —  AI Surveillance Bot
  DESC     :  Remote surveillance robot with 2.4GHz wireless comms,
              live video streaming, real-time face & object detection,
              smoke / temperature / humidity environmental sensors
  STACK    :  Raspberry Pi  ·  Python  ·  OpenCV  ·  Haar Cascade
  DEMO     :  youtu.be/vp3VAwmdAKc
  STATUS   :  ● RUNNING
```

---

## ⬡ &nbsp;research.pipeline

```
  ┌──────────────────────────────────────────────────────────────────────────────┐
  │  RESEARCH //  STATUS BOARD                                                   │
  └──────────────────────────────────────────────────────────────────────────────┘

  [INGEST]────▶[DESIGN]────▶[TRAIN]────▶[EVALUATE]────▶[PUBLISH]

  ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  PROJECT  :  Hierarchical Transformer — Intraoperative Organ Segmentation
  DATASET  :  Dresden Surgical Anatomy Dataset
  METHOD   :  DINOv2 backbone  ·  Multi-scale Cross-Attention Decoder
              Hybrid Loss Function  ·  Advanced ROI Extraction
  RESULT   :  Dice Score ↑ 27% on pancreas & colon  (new benchmark)
  STAGE    :  ████████████████████░░░░  IN PROGRESS
  WITH     :  Dr. Md. Golam Rabiul Alam  ·  Md. Saiful Islam

  ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  PROJECT  :  Diffusion-based NIR Colorization — Night Vision Enhancement
  DATASET  :  NIR2RGB VCIP Dataset
  METHOD   :  Modified Diffusion Model  ·  ILVR-style Refinement
  RESULT   :  PSNR 22.7 dB  ·  SSIM 0.67  (outperforms GAN & U-Net baselines)
  STAGE    :  ████████████░░░░░░░░░░░░  ON HOLD
  WITH     :  Dr. Md. Ashraful Alam
```

---

## ⬡ &nbsp;production.impact

Things I've shipped that moved the needle:

```
✦  Reduced LLM token costs in production
   → prompt caching  +  semantic re-ranking  +  dynamic model routing

✦  Built custom MCP servers
   → secure AI-to-database and AI-to-API connectivity for agentic systems

✦  Engineered Graph-RAG + re-ranker pipelines
   → deployed in legal chatbot applications

✦  Multi-agent NLQ system
   → natural language queries over PostgreSQL; real-time user progress tracking

✦  Distilled & fine-tuned large generative models
   → niche-specific variants with reduced latency and lower resource footprint

✦  End-to-end CI/CD pipelines
   → GitHub Actions  ·  containerised builds  ·  automated test & deploy
```

---

## ⬡ &nbsp;github.telemetry

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=AnindyaMajumder&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&title_color=79c0ff&icon_color=79c0ff&text_color=8b949e" height="160"/>
&nbsp;&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AnindyaMajumder&layout=compact&theme=dark&hide_border=true&bg_color=0d1117&title_color=79c0ff&text_color=8b949e" height="160"/>

</div>

---

<details>
<summary>⬡ &nbsp;<strong>credentials.log</strong> &nbsp;— certifications · awards · achievements · extracurriculars</summary>

<br>

```
  ┌──────────────────────────────────────────────────────────────────────────────┐
  │  CERTIFICATIONS & SPECIALISATIONS                                            │
  └──────────────────────────────────────────────────────────────────────────────┘

  ✦  LangChain for LLM Application Development              [VERIFIED]
     Build production-ready RAG pipelines and agentic systems
     using the LangChain framework

  ✦  Machine Learning Specialization                        [VERIFIED]
     Stanford University  ·  Coursera  ·  April 2024
     Supervised learning, neural networks, decision trees,
     unsupervised learning, recommender systems, deep RL

  ✦  Containerization & Virtualization Skill Track          [VERIFIED]
     Docker & Kubernetes  ·  DataCamp
     Container management, Kubernetes orchestration,
     scalable and resilient application deployment
     [ 4 courses completed ]


  ┌──────────────────────────────────────────────────────────────────────────────┐
  │  COMPETITIONS & AWARDS                                                       │
  └──────────────────────────────────────────────────────────────────────────────┘

  ✦  Rank #39  —  Machine Learning Olympiad 2024
     Google Developer Group (GDG) Bangladesh
     Top 39 out of hundreds of participants nationwide

  ✦  Finalist  —  IEEE CS Spectrum: Code Crash 2023
     Top 9 of 100+ competing teams
     DSA problem-solving under time pressure

  ✦  Regional Participant  —  Bangladesh Mathematical Olympiad (BdMO) 2020

  ✦  Regional Participant  —  Bangladesh Physics Olympiad (BdPhO) 2019


  ┌──────────────────────────────────────────────────────────────────────────────┐
  │  ACADEMIC HONOURS  —  BRAC University                                        │
  └──────────────────────────────────────────────────────────────────────────────┘

  ✦  Vice Chancellor's List  ×2     →  top academic distinction
  ✦  Dean's List              ×5     →  consistent semester excellence
  ✦  Academic Merit Scholarship          →  result-based award


  ┌──────────────────────────────────────────────────────────────────────────────┐
  │  EXTRACURRICULARS                                                            │
  └──────────────────────────────────────────────────────────────────────────────┘

  ✦  Core Team Member  —  BRACU Mongol-Tori  (Mars Rover Team)
  ✦  Assistant Director  —  BRACU Computer Club
  ✦  Executive, Content Planning  —  Hult Prize at BRACU
```

</details>

---

<br>

```
anindya@systems:~$ echo "Let's build something worth deploying."
```
