<!-- Neric Joel · GitHub profile README · last reviewed 2026-09-16 -->

<h1 align="center">Neric Joel</h1>

<p align="center">
  <strong>AI/ML engineer · M.S. Computer Science at Arizona State University, graduating May 2027</strong><br/>
  I build RAG pipelines, LLM agents, and computer-vision models, plus the APIs and UIs around them, and I test what I ship.
</p>

<p align="center">
  Open to <strong>Summer 2027 AI/ML and software engineering internships</strong> (May – Aug 2027 · on-site, hybrid, or remote · Tempe, AZ, willing to relocate)
</p>

<p align="center">
  <a href="mailto:nericjoel07@gmail.com"><img src="https://img.shields.io/badge/Email-nericjoel07%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email nericjoel07@gmail.com" /></a>&nbsp;
  <a href="https://linkedin.com/in/neric-joel"><img src="https://img.shields.io/badge/LinkedIn-neric--joel-0A66C2?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHJlY3Qgd2lkdGg9IjI0IiBoZWlnaHQ9IjI0IiByeD0iMyIgZmlsbD0iI2ZmZmZmZiIvPjx0ZXh0IHg9IjEyIiB5PSIxNy41IiBmb250LWZhbWlseT0iQXJpYWwsSGVsdmV0aWNhLHNhbnMtc2VyaWYiIGZvbnQtd2VpZ2h0PSI3MDAiIGZvbnQtc2l6ZT0iMTQuNSIgdGV4dC1hbmNob3I9Im1pZGRsZSIgZmlsbD0iIzBBNjZDMiI%2BaW48L3RleHQ%2BPC9zdmc%2B" alt="LinkedIn" /></a>&nbsp;
  <a href="https://neric-portfolio.vercel.app/neric-resume.pdf"><img src="https://img.shields.io/badge/R%C3%A9sum%C3%A9-PDF-2ea043?style=for-the-badge&logo=readdotcv&logoColor=white" alt="Résumé PDF" /></a>&nbsp;
  <a href="https://neric-portfolio.vercel.app"><img src="https://img.shields.io/badge/Portfolio-neric--portfolio.vercel.app-111827?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
</p>

## Now

- **Building** the Career Faculty Association (CFA) Resource Chatbot at ASU: leading a 4-person team on a RAG system that answers faculty questions with a link to the source document (May 2026 – present).
- **Shipped** [AgentRoom v1.6](https://github.com/neric-joel/Whatsapp-Agents/releases/latest), a local multi-agent chat room for Claude Code, Codex, and Gemini CLIs (Jul 2026).
- **Studying** for the M.S.: machine learning, deep learning, distributed systems, and advanced algorithms. B.Tech. in Electrical & Electronics Engineering (Amrita Vishwa Vidyapeetham, 2025, First Class, Merit Scholarship), where I worked on signal processing and numerical optimization for solar PV systems.

## Experience

| When | Role | Highlights |
|:--|:--|:--|
| May 2026 – Present | **Lead Developer**, Career Faculty Association (CFA) Resource Chatbot · Arizona State University | Designed the docx/xlsx ingestion and hybrid-retrieval pipeline with cached embeddings. 23-question eval set: 23/23 correct retrievals, every answer grounded in a cited source, enforced by a pytest regression gate. Streamlit UI with out-of-scope guardrails. |
| May – Jul 2026 | **Teaching Assistant**, W. P. Carey School of Business · Arizona State University | Supported 106 graduate students building AI agents on n8n. Debugged tool-calling routines and REST integrations, reviewed student code, and wrote the reference solutions and debugging guides the cohort validated against. |
| Jan 2024 – May 2025 | **Research Assistant**, PV Systems Lab · Amrita Vishwa Vidyapeetham | Built predictive models over 100k+ telemetry records (18% lower degradation-forecast error vs. baseline), automated ETL with validation checks (40% less manual prep), and fit single-diode PV models with least-squares and particle-swarm optimization. |

Education: **M.S. Computer Science**, Arizona State University, Aug 2025 – May 2027 (expected), GPA 3.66 / 4.0 · **B.Tech. Electrical & Electronics Engineering**, Amrita Vishwa Vidyapeetham, Sep 2021 – May 2025.

## Projects

Ordered by what I would show a hiring manager first. Every repo has its own README.

| Project | What it does | What it shows | Stack · Links |
|:--|:--|:--|:--|
| **AgentRoom** | Local chat room that puts your installed agent CLIs (Claude Code, Codex, Gemini) into one conversation. `/discuss` splits a task across agents on a shared blackboard and converges on one attributed answer. | Shipped software: 6 tagged releases through v1.6.0, CI on every push, MIT licence, demo GIF in the README. | TypeScript · Node.js<br/>[Repo](https://github.com/neric-joel/Whatsapp-Agents) · [Releases](https://github.com/neric-joel/Whatsapp-Agents/releases) |
| **Path Forward** | College-readiness planner for foster youth aging out of care. Six questions in, a personalized funding match, school list, and semester roadmap out. HackASU 2026 team project. | LLM product work: structured Claude API outputs turned into a PDF plan a caseworker can use. Live and deployed. | React 18 · TypeScript · Claude API · Tailwind CSS<br/>[Live](https://pathforward-az.vercel.app) · [Video](https://www.youtube.com/watch?v=9Z9AgUIAbHk) · [Repo](https://github.com/neric-joel/path-forward) |
| **CareBase** | Open-source case-management platform with AI assistance for food banks and social-services nonprofits, built for ICM Food & Clothing Bank at WiCS × Opportunity Hack 2026. | Full-stack with auth, a Postgres schema, an audit trail, and agentic workflows for intake and routing. Live with a demo login. | Next.js 14 · Supabase · Claude API<br/>[Live](https://carebase-murex.vercel.app) · [Video](https://www.youtube.com/watch?v=YtwZh96U1F8) · [Repo](https://github.com/neric-joel/CareBase) |
| **Workflow Analyst** | n8n agent that lets an instructor ask plain-English questions about 700+ student workflow submissions and get cited, grounded answers. | Used in production as the TA tool for a 106-student ASU course; the repo is the sanitized architecture. | n8n · LLM tool-calling · Google Sheets<br/>[Repo](https://github.com/neric-joel/workflow-analyst) |
| **NotaryGuard** | Identity-verification pipeline for remote online notarization. Runs uploaded IDs through four progressive verification levels, from OCR and name matching to notary-commission validity. VillageHacks 2026. | Applied CV/OCR with a Python backend and a typed React frontend, open-source dependencies only. | Python · FastAPI · PaddleOCR · React<br/>[Repo](https://github.com/neric-joel/Village-Hacks) |
| **Hand Gesture Recognition** | Real-time two-hand tracking, finger counting, and A–Z ASL fingerspelling from a webcam using landmark geometry. | Computer-vision fundamentals without a trained model: landmark math, both hands at once, live UI. | Python · OpenCV · MediaPipe<br/>[Repo](https://github.com/neric-joel/hand-gesture-recognition) |
| **Hybrid Movie Recommender** | Combines collaborative filtering, content-based filtering, and Neural Collaborative Filtering (NeuMF) into one ranked recommender. Graduate course project, ASU. | Classical and deep recommender methods evaluated side by side on accuracy and ranking metrics. | Python · PyTorch · pandas<br/>[Repo](https://github.com/neric-joel/movie-recommender-system) |

## Publications

Co-author of two peer-reviewed IEEE conference papers (2025).

- **Design and Comparative Analysis of CMOS, FSGDI, and MGDI-Based Ripple Carry Adders for Low Power VLSI Applications.** 2025 13th International Conference on Smart Grid (icSmartGrid), Glasgow, UK. [IEEE Xplore](https://ieeexplore.ieee.org/document/11071839) · [DOI](https://doi.org/10.1109/icSmartGrid66138.2025.11071839)
- **Optimal Parameter Estimation Techniques for Enhanced Performance of Solar PV Cell.** 2025 International Conference on Recent Advances in Electrical, Electronics, Ubiquitous Communication, and Computational Intelligence (RAEEUCCI), Chennai, India. [IEEE Xplore](https://ieeexplore.ieee.org/document/11048280) · [DOI](https://doi.org/10.1109/RAEEUCCI63961.2025.11048280)

## Skills

<p align="center">
  <strong>Languages</strong><br/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/MATLAB-E16737?style=for-the-badge&logoColor=white" alt="MATLAB" />
</p>

<p align="center">
  <strong>AI/ML</strong><br/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn" />
  <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV" />
  <img src="https://img.shields.io/badge/Claude_API-191919?style=for-the-badge&logo=anthropic&logoColor=white" alt="Claude API" />
  <img src="https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge&logoColor=white" alt="OpenAI API" />
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" alt="n8n" />
</p>

<p align="center">
  <strong>Backend &amp; web</strong><br/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
</p>

<p align="center">
  <strong>Data &amp; testing</strong><br/>
  <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="pandas" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy" />
  <img src="https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" alt="pytest" />
</p>

## GitHub activity

<p align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://denvercoder1-github-readme-stats.vercel.app/api?username=neric-joel&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&rank_icon=github" />
  <img src="https://denvercoder1-github-readme-stats.vercel.app/api?username=neric-joel&show_icons=true&hide_border=true&include_all_commits=true&rank_icon=github" alt="Neric Joel's GitHub stats" height="170" />
</picture>
</p>

<p align="center">
  <a href="https://github.com/neric-joel?tab=overview"><img src="https://ghchart.rshah.org/2ea043/neric-joel" alt="Neric Joel's contribution calendar for the last 12 months" width="100%" /></a>
</p>

---

<p align="center">
  Open to <strong>Summer 2027 AI/ML and software engineering internships</strong>. If you work on retrieval, agents, or applied ML, email me: <a href="mailto:nericjoel07@gmail.com">nericjoel07@gmail.com</a>
</p>
