<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:6D28D9,45:4F46E5,75:2563EB,100:06B6D4&height=230&section=header&text=Hi%20there,%20I'm%20Chhavi%20Verma%20%F0%9F%91%8B&fontSize=44&fontColor=ffffff&fontAlignY=34&desc=Full%20Stack%20Developer%20%E2%80%A2%20AI%20%26%20LLM%20Enthusiast&descAlignY=58&descSize=19&fontFamily=Segoe%20UI&animation=twinkling&stroke=ffffff&strokeWidth=0" width="100%" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&duration=2800&pause=900&color=8B5CF6&center=true&vCenter=true&width=720&lines=Building+production-ready+full-stack+applications;Engineering+multilingual+AI+%26+RAG+systems;Backend+%7C+Cloud+%7C+LLM+%7C+Distributed+Systems" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://www.coursera.org/">
    <img src="https://img.shields.io/badge/IBM%20Data%20Science-Coursera-6D28D9?style=flat-square&logo=coursera&logoColor=white" />
  </a>
  <a href="https://nptel.ac.in/">
    <img src="https://img.shields.io/badge/NPTEL-Competitive%20Programming-4F46E5?style=flat-square&logoColor=white" />
  </a>
  <a href="https://www.google.com/maps/search/?api=1&query=India">
    <img src="https://img.shields.io/badge/Location-India-2563EB?style=flat-square&logo=googlemaps&logoColor=white" />
  </a>
</p>

<p align="center">
  <a href="https://clarity-ai-puce.vercel.app/">
    <img src="https://img.shields.io/badge/Portfolio-6D28D9?style=for-the-badge&logo=vercel&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/chhavi555111/">
    <img src="https://img.shields.io/badge/LinkedIn-4F46E5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://github.com/Kgotta-contribute">
    <img src="https://img.shields.io/badge/GitHub-111827?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Kgotta-contribute&label=PROFILE%20VIEWS&color=6D28D9&style=for-the-badge" />
  <img src="https://img.shields.io/github/followers/Kgotta-contribute?label=FOLLOWERS&style=for-the-badge&color=4F46E5&logo=github" />
  <img src="https://img.shields.io/github/stars/Kgotta-contribute?label=TOTAL%20STARS&style=for-the-badge&color=7C3AED&logo=github" />
</p>

---

## About

Full Stack Developer focused on building scalable, maintainable, production-oriented software with a strong interest in **AI engineering, LLM applications, conversational systems, and backend architecture**.

My work spans the full product lifecycle — from **React/Angular interfaces and API design** to **Spring Boot/FastAPI services, databases, cloud infrastructure, retrieval systems, and LLM orchestration**.

I enjoy solving engineering problems where application development intersects with AI, particularly **multilingual RAG, semantic retrieval, reranking, transcription intelligence, model routing, and production reliability**.

I approach software with a product-engineering mindset: understand the problem, design the system, measure the result, and optimize for reliability, maintainability, and user experience.

### Open To

`Full-Stack Engineering` `AI Engineering` `Backend Engineering` `RAG & LLM Applications` `Open Source Collaboration`

---

## Tech Stack

### Languages

<p>
  <img src="https://skillicons.dev/icons?i=java,python,cpp,javascript,typescript,html,css&theme=dark" />
</p>

### Frontend

<p>
  <img src="https://skillicons.dev/icons?i=react,angular,vite,javascript,html,css&theme=dark" />
</p>

### Backend & Databases

<p>
  <img src="https://skillicons.dev/icons?i=spring,fastapi,nodejs,mysql,postgres,mongodb,firebase,oracle&theme=dark" />
</p>

### Cloud, DevOps & Tooling

<p>
  <img src="https://skillicons.dev/icons?i=aws,docker,kubernetes,git,github,vercel,linux&theme=dark" />
</p>

---

## AI / ML Expertise

| Domain | Proficiency | Details |
|---|---|---|
| **LLM Application Engineering** | Advanced | Multi-model orchestration, multilingual reasoning, model routing, fallback strategies |
| **Retrieval-Augmented Generation** | Advanced | Dense retrieval, semantic search, embedding pipelines, cross-encoder reranking |
| **NLP & Multilingual AI** | Advanced | Multilingual transcription, query understanding, speaker-aware conversational intelligence |
| **Speech AI** | Advanced | Whisper Large-v3, long-form audio processing, timestamped transcript generation |
| **Speaker Intelligence** | Advanced | Structured speaker diarization using LLaMA-based reasoning workflows |
| **Embeddings & Reranking** | Advanced | BGE-M3 embeddings and BGE reranker-based retrieval optimization |
| **AI Backend Engineering** | Advanced | FastAPI services, request interception, rate limiting, model-memory profiling |
| **AI Product Engineering** | Advanced | End-to-end AI applications combining UI, APIs, retrieval, inference and persistence |

---

## Featured Projects

<details>
<summary><strong>ClarityAI — Multilingual Audio Intelligence & Conversational RAG Platform</strong></summary>

<br>

Production-oriented multilingual AI platform that converts long-form audio/video into **speaker-aware, timestamped transcripts** and provides grounded conversational intelligence through a **two-stage RAG pipeline**.

| Metric | Implementation |
|---|---|
| **Stack** | React, Vite, FastAPI, Whisper Large-v3, LLaMA 3.3 70B, BGE-M3, BGE Reranker, Qwen 3.6, GPT-OSS, Groq |
| **Scale** | 50-question domain benchmark; long-form audio/video processing |
| **Performance** | Final answer accuracy improved **55% → 100% (+45 pp)** |
| **Security / Reliability** | Thread-safe sliding-window limiter, **2 requests/60s/IP**, proxy-aware IP resolution, HTTP 429 + Retry-After synchronization |
| **Impact** | Zero hallucinations on the benchmark with precise `[mm:ss]` transcript grounding |
| **Repository** | [ClarityAI](https://github.com/Kgotta-contribute/ClarityAI) |
| **Live Product** | [clarity-ai-puce.vercel.app](https://clarity-ai-puce.vercel.app/) |

**Engineering Highlights**

- Designed a two-stage dense retrieval + reranking architecture using **1,024-dimensional BGE-M3 embeddings**.
- Implemented **Top-20 → Top-10 cross-encoder reranking** with `bge-reranker-v2-m3`.
- Integrated Qwen 3.6 for multilingual reasoning with GPT-OSS model failover.
- Built structured speaker diarization using LLaMA 3.3 70B.
- Implemented 16 kHz audio normalization and adaptive **35–80 second chunking**.
- Built a React audio-transcript interface with timecode synchronization and speaker highlighting.

</details>

<details>
<summary><strong>Chef Llama — AI Recipe Generator</strong></summary>

<br>

AI-powered recipe assistant combining structured LLM generation with nutrition calculations, dynamic portion scaling, speech narration and print-ready recipe output.

| Metric | Implementation |
|---|---|
| **Stack** | React 19, FastAPI, LangChain, Llama-3, Hugging Face, Vercel Serverless |
| **Scale** | Full-stack AI web application |
| **Performance** | Serverless API-proxy architecture with structured JSON handling |
| **Security / Reliability** | API proxying, custom JSON parsing and schema validation |
| **Impact** | Automated recipe generation, nutrition tracking and dynamic serving adjustment |
| **Repository** | [Chef Llama](https://github.com/Kgotta-contribute/PROJECTS_On_RESUME) |
| **Live Product** | [Chef Llama](https://chhavi-verma-llm-chef.vercel.app/) |

**Engineering Highlights**

- Built an AI culinary assistant using React 19 and FastAPI.
- Orchestrated LLM workflows through LangChain and Llama-3.
- Implemented schema validation for reliable nutrition and portion calculations.
- Integrated Web Speech API for step-by-step recipe narration.

</details>

<details>
<summary><strong>Enterprise AI Audio Transcription & Diarization Platform</strong></summary>

<br>

End-to-end AI transcription workflow designed for long-form media ingestion, asynchronous processing and speaker-aware transcript delivery.

| Metric | Implementation |
|---|---|
| **Stack** | React, Python, Whisper, AWS S3, MongoDB, Amazon SQS |
| **Scale** | 5K+ files/month and long-form recordings |
| **Performance** | Asynchronous queue-based processing with dedicated Python worker |
| **Security / Reliability** | Isolated object storage, queue-driven processing and persistent transcript storage |
| **Impact** | **97.5% transcription/diarization accuracy** in company validation tests |
| **Repository** | [PROJECTS_On_RESUME](https://github.com/Kgotta-contribute/PROJECTS_On_RESUME) |

**Engineering Highlights**

- Designed a decoupled upload → queue → worker → persistence workflow.
- Integrated cloud object storage with asynchronous processing.
- Built React-based transcript interfaces for speaker-aware audio intelligence.
- Supported long-form audio processing and persistent searchable transcript data.

</details>

<details>
<summary><strong>CVS Data Lake — Full-Stack Data Exploration Platform</strong></summary>

<br>

Enterprise full-stack data exploration application built around structured backend APIs, relational database access and reactive frontend workflows.

| Metric | Implementation |
|---|---|
| **Stack** | Angular, Spring Boot, Oracle, JDBC, RxJS |
| **Scale** | Enterprise application |
| **Performance** | Reactive UI flows with optimized backend data access |
| **Security / Reliability** | Layered API and database architecture |
| **Impact** | Simplified exploration and retrieval of enterprise datasets |
| **Repository** | [PROJECTS_On_RESUME](https://github.com/Kgotta-contribute/PROJECTS_On_RESUME) |

</details>

<details>
<summary><strong>EDP Sales — Dynamic Enterprise Search Tool</strong></summary>

<br>

Enterprise search application focused on dynamic metadata-driven discovery and efficient retrieval of business data.

| Metric | Implementation |
|---|---|
| **Stack** | Angular, Spring Boot, SQL |
| **Scale** | Enterprise application |
| **Performance** | Dynamic filtering and backend-driven query workflows |
| **Security / Reliability** | Structured service-layer architecture |
| **Impact** | Improved discoverability of enterprise sales information |
| **Repository** | [PROJECTS_On_RESUME](https://github.com/Kgotta-contribute/PROJECTS_On_RESUME) |

</details>

<details>
<summary><strong>Spider Contract Republish — Batch Operations Tool</strong></summary>

<br>

Enterprise batch-processing application for streamlining contract republish workflows and operational data handling.

| Metric | Implementation |
|---|---|
| **Stack** | Angular, Spring Boot, SQL |
| **Scale** | Enterprise batch workflow |
| **Performance** | Batch-oriented processing |
| **Security / Reliability** | Backend-controlled operation flow |
| **Impact** | Simplified repetitive contract republishing operations |
| **Repository** | [PROJECTS_On_RESUME](https://github.com/Kgotta-contribute/PROJECTS_On_RESUME) |

</details>

---

## Experience

### Full Stack & AI Engineering

**Enterprise Software Engineering**

**Engineering Focus:** Full-Stack Development • Backend Engineering • AI Applications • Data & Search Systems

- Developed enterprise applications using **Angular, React, Spring Boot, FastAPI and Python**.
- Built REST APIs, reactive user interfaces and database-driven workflows.
- Worked across **Oracle, PostgreSQL, MySQL and MongoDB** data platforms.
- Engineered AI workflows involving transcription, multilingual reasoning, semantic retrieval and conversational RAG.
- Designed asynchronous processing architectures using queues, workers and persistent storage.
- Applied production engineering practices around **reliability, observability, rate limiting, validation and maintainability**.

`Java` `Spring Boot` `Angular` `React` `Python` `FastAPI` `SQL` `MongoDB` `AWS` `Docker` `AI/ML`

---

## Achievements

<p align="center">

| Recognition | Details |
|---|---|
| 🏆 **100% RAG Benchmark** | Achieved **50/50** on a domain benchmark with grounded answers and precise `[mm:ss]` timecode references |
| 🚀 **+45 pp Accuracy Improvement** | Improved final-answer accuracy from **55% → 100%** through retrieval and reranking optimization |
| 🤖 **AI Validation** | Achieved **97.5% transcription/diarization accuracy** in company validation tests |
| ⚙️ **Production AI Engineering** | Built thread-safe rate limiting, model failover and pre-computation interception for AI APIs |

</p>

---

## Certifications

### IBM / Coursera

<p>
  <a href="https://www.coursera.org/">
    <img src="https://img.shields.io/badge/IBM%20Data%20Science%20Professional-Coursera-6D28D9?style=for-the-badge&logo=coursera&logoColor=white" />
  </a>
</p>

### NPTEL

<p>
  <a href="https://nptel.ac.in/">
    <img src="https://img.shields.io/badge/Getting%20Started%20with%20Competitive%20Programming-NPTEL-4F46E5?style=for-the-badge&logoColor=white" />
  </a>
</p>

### IIT Roorkee & iHUB

<p>
  <a href="https://www.iitr.ac.in/">
    <img src="https://img.shields.io/badge/Ethical%20Hacking%20%26%20Cybersecurity-IIT%20Roorkee%20%26%20iHUB-4338CA?style=for-the-badge&logoColor=white" />
  </a>
</p>

### CodeClause

<p>
  <a href="https://github.com/Kgotta-contribute/PROJECTS_On_RESUME/blob/main/signal-new-clone/">
    <img src="https://img.shields.io/badge/Web%20Development%20Internship-CodeClause-6D28D9?style=for-the-badge&logoColor=white" />
  </a>
</p>

### Udemy

<p>
  <a href="https://www.udemy.com/">
    <img src="https://img.shields.io/badge/Ethical%20Hacking%20%26%20Pen%20Testing-Udemy-4F46E5?style=for-the-badge&logo=udemy&logoColor=white" />
  </a>
</p>

---

## Coding Profiles

<p align="center">
  <a href="https://leetcode.com/u/DidYouCode5/">
    <img src="https://img.shields.io/badge/LeetCode-DidYouCode5-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" />
  </a>
  <a href="https://github.com/Kgotta-contribute/Leetcode">
    <img src="https://img.shields.io/badge/LeetCode%20Solutions-GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://www.hackerrank.com/">
    <img src="https://img.shields.io/badge/HackerRank-Profile-00EA64?style=for-the-badge&logo=hackerrank&logoColor=black" />
  </a>
  <a href="https://www.codechef.com/">
    <img src="https://img.shields.io/badge/CodeChef-Profile-5B4638?style=for-the-badge&logo=codechef&logoColor=white" />
  </a>
</p>

---

## GitHub Analytics

<p align="center">
  <img src="https://github-stats-extended.vercel.app/api?username=Kgotta-contribute&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github" width="49%" />
  <img src="https://streak-stats.demolab.com/?user=Kgotta-contribute&theme=tokyonight&hide_border=true" width="49%" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Kgotta-contribute&layout=compact&theme=tokyonight&hide_border=true&langs_count=10" width="48%" />
</p>

---

## GitHub Trophies

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Kgotta-contribute&theme=algolia&no-frame=true&no-bg=true&margin-w=10&row=1&column=7" width="100%" />
</p>

---

## Contribution Activity

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Kgotta-contribute&bg_color=0D1117&color=8B5CF6&line=4F46E5&point=22D3EE&area=true&hide_border=true" width="100%" />
</p>

---

## Contribution Snake

<p align="center">
  <img src="https://raw.githubusercontent.com/Kgotta-contribute/Kgotta-contribute/output/github-contribution-grid-snake-dark.svg" alt="GitHub Contribution Snake" width="100%" />
</p>

---

## Current Focus

```yaml
learning:
  - System Design
  - Backend Architecture
  - Distributed Systems
  - Advanced RAG
  - LLM Engineering

building:
  - Multilingual AI Applications
  - Conversational RAG Systems
  - Production Full-Stack Applications
  - AI Developer Tools

exploring:
  - Model Routing
  - Retrieval Optimization
  - Cross-Encoder Reranking
  - Multimodal AI
  - Cloud-Native AI Infrastructure

open_to:
  - Full-Stack Engineering
  - AI / LLM Engineering
  - Backend Engineering
  - Open Source Collaboration
  - Interesting Technical Problems
