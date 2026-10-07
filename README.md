<div align="center">

# HAPPY SAINI

### I build AI-powered web apps — from raw data to a working product ⚡

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=1200&color=22D3EE&center=true&vCenter=true&width=700&lines=Machine+Learning+Intern;Full-Stack+%7C+Flask+%2B+FastAPI+%2B+Next.js;NLP+%7C+Cybersecurity+%7C+Blockchain+Integrity;Web+Developer+%40+Editkaro.in" alt="typing" />

![Status](https://img.shields.io/badge/STATUS-OPEN_TO_WORK-22c55e?style=for-the-badge)
![Role](https://img.shields.io/badge/ROLE-ML_ENGINEER-7c3aed?style=for-the-badge)
![Role](https://img.shields.io/badge/ROLE-WEB_DEVELOPER-0ea5e9?style=for-the-badge)

[![Email](https://img.shields.io/badge/EMAIL-happyhsaini990@gmail.com-ef4444?style=for-the-badge&logo=gmail&logoColor=white)](mailto:happyhsaini990@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-CONNECT-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white)](YOUR_LINKEDIN_URL)
[![LeetCode](https://img.shields.io/badge/LEETCODE-60%2B_SOLVED-f59e0b?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/u/happyhsaini/)
[![Portfolio](https://img.shields.io/badge/PORTFOLIO-VISIT-111827?style=for-the-badge&logo=githubpages&logoColor=white)](https://happyhsaini.github.io)

</div>

---

## ⚡ 30-SECOND RECRUITER SCAN

| 🎯 Target roles | 🧠 Core strengths | 🛠️ Stack |
|---|---|---|
| ML Engineer · Data Analyst · Full-Stack Developer | NLP (TF-IDF) · Secure backends & RBAC · Flask / FastAPI APIs · Responsive web design | Python · Flask · FastAPI · Next.js · JavaScript · SQL |

<div align="center">

| **90%** | **5** | **3** | **SIH 2025** | **60+** |
|:---:|:---:|:---:|:---:|:---:|
| accuracy on spam / phishing detection | role-based access tiers in Tathya | featured projects below | Qualified for Round 2 | DSA problems on LeetCode |

</div>

---

## 🧪 Experience

| Role | Company | When | What I did |
|---|---|---|---|
| **Machine Learning Intern** | Pratinik Infotech (Remote) | May 2026 – Present | Data preprocessing, feature engineering and model development; handling missing values and outliers; validation techniques and performance metrics for model evaluation; collaborating on real-world data-driven problems |
| **Web Development · Python · Java · AI Intern** | VaultofCodes.in (Remote) | May – Jul 2026 | Built responsive web pages with HTML, CSS and JavaScript; hands-on exposure to Python, Java and AI concepts; improved debugging and problem-solving through project tasks |

---

## 🏆 Achievements

| 🏅 | Milestone |
|---|---|
| 🇮🇳 | **Smart India Hackathon 2025:** qualified for the 2nd round |
| ⚖️ | **Smart India Hackathon 2026:** built the Tathya prototype (PS ID SIH26190 · NCRB / MHA · Blockchain & Cybersecurity) |
| 🧩 | **LeetCode:** 60+ DSA problems solved |
| ☁️ | **AWS Certified Cloud Practitioner** |
| 🎓 | Oracle SQL Database · Red Hat Linux & Open Source Fundamentals · Tally Certificate · Infosys Springboard (Programming & CS Foundations) |

---

## 🚀 Featured Projects

<div align="center">

[![Tathya](https://img.shields.io/badge/TATHYA_·_SIH_2026-7c3aed?style=for-the-badge)](#️-tathya--sih-2026)
[![ShieldScan AI](https://img.shields.io/badge/SHIELDSCAN_AI-ef4444?style=for-the-badge)](#️-shieldscan-ai--fake-message-detection-platform)
[![Editkaro.in](https://img.shields.io/badge/EDITKARO.IN-0ea5e9?style=for-the-badge)](#-editkaroin--agency-website)

</div>

### ⚖️ Tathya · SIH 2026

> Secure case, evidence and legal document management system: tamper-evident storage with SHA-256 verification, blockchain hash anchoring, audit trails and a permission-aware AI assistant. Smart India Hackathon 2026 prototype · PS ID **SIH26190** · NCRB / Ministry of Home Affairs · Blockchain & Cybersecurity.

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL_+_pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO-C72E49?style=flat-square&logo=minio&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity_·_Hardhat-363636?style=flat-square&logo=solidity&logoColor=white)
![Docker](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white)

**System architecture**

```mermaid
flowchart LR
    U[5 Roles<br/>Admin · Officer · Supervisor<br/>Forensic · Prosecutor] --> N[Next.js Frontend]
    N -->|JWT| F[FastAPI Backend]
    F --> P[(PostgreSQL + pgvector<br/>metadata · audit log · embeddings)]
    F --> M[(MinIO<br/>private file storage)]
    F --> O[OCR · Search · RAG]
    F --> E[Hardhat / Ethereum<br/>hash anchoring only]
```

**Evidence verification flow**

```mermaid
flowchart LR
    D[Document upload] --> H[SHA-256 hash]
    H --> S[(MinIO storage)]
    H --> DB[(PostgreSQL record)]
    H --> BC[Blockchain anchor<br/>documentId · hash · timestamp]
    V[Later verification] --> R[Re-hash current file]
    R --> C{Match stored<br/>and anchored hash?}
    C -->|Yes| OK[✅ VERIFIED]
    C -->|No| BAD[🚨 INTEGRITY FAILURE]
```

| Highlight | Detail |
|---|---|
| 🔐 Access control | JWT + bcrypt, 5 roles, case-level RBAC enforced on the backend; unauthorized access returns 404 so document existence never leaks |
| ⛓️ Integrity | SHA-256 per document version, hashes anchored on a local Ethereum node (the document itself is never on-chain) |
| 🧠 AI / RAG | OCR with Tesseract + PyMuPDF, full-text search, permission-aware retrieval with source citations |
| 🧾 Traceability | Immutable document versions and an append-only audit trail |

[![GitHub Repo](https://img.shields.io/badge/GITHUB-REPO-181717?style=flat-square&logo=github)](https://github.com/happyhsaini/TATHYA--sih26-)

---

### 🛡️ ShieldScan AI — Fake Message Detection Platform

> AI-based web platform that classifies messages as **Real**, **Suspicious** or **Fake**, scans text and images (OCR), and checks emails automatically.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![NLP](https://img.shields.io/badge/NLP_TF--IDF-7c3aed?style=flat-square)
![Logistic Regression](https://img.shields.io/badge/Logistic_Regression-f59e0b?style=flat-square)
![Tesseract](https://img.shields.io/badge/Tesseract_OCR-5b21b6?style=flat-square)
![Gmail API](https://img.shields.io/badge/Gmail_API_/_IMAP-ea4335?style=flat-square&logo=gmail&logoColor=white)

```mermaid
flowchart LR
    T[Text input] --> PRE[Text cleaning]
    I[Image upload] --> OCR[Tesseract OCR] --> PRE
    G[Gmail API / IMAP] --> PRE
    PRE --> TF[TF-IDF features]
    TF --> LR[Logistic Regression]
    LR --> P{Fake probability}
    P -->|under 40%| R[✅ Real]
    P -->|40 to 60%| S[⚠️ Suspicious]
    P -->|over 60%| F[🚫 Fake]
```

| Metric | Value |
|---|---|
| Accuracy | ~90% |
| Model | TF-IDF + Logistic Regression, trained from a CSV dataset |
| Inputs | Text, images (OCR) and email scanning via Gmail API / IMAP |
| Output | Real / Suspicious / Fake label with confidence score and human-readable explanation, plus batch filtering |
| Config | Prediction thresholds adjustable in `src/config.py` |

[![Live](https://img.shields.io/badge/LIVE-DEMO-22c55e?style=flat-square)](YOUR_SHIELDSCAN_LIVE_URL)
[![GitHub Repo](https://img.shields.io/badge/GITHUB-REPO-181717?style=flat-square&logo=github)](https://github.com/happyhsaini/Fake-message-detection)

---

### 🎬 Editkaro.in — Agency Website

> Complete, responsive website for a video editing and social media marketing agency, with a filterable video portfolio and forms that save leads to Google Sheets.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript_ES6+-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Google Sheets](https://img.shields.io/badge/Google_Sheets_+_Apps_Script-34A853?style=flat-square&logo=googlesheets&logoColor=white)

```mermaid
flowchart LR
    V[Visitor] --> P[4 pages<br/>Home · Portfolio · About · Contact]
    P --> F[Portfolio filters<br/>9 categories · 18 videos]
    F --> Y[YouTube modal player]
    P --> FM[Subscribe and Contact forms]
    FM -->|fetch| GS[Google Apps Script]
    GS --> SH[(Google Sheets)]
    FM -.->|fallback| LS[(localStorage)]
```

| Highlight | Detail |
|---|---|
| 📱 Responsive | Mobile, tablet, laptop and desktop layouts with Flexbox, Grid and a hamburger menu |
| 🎞️ Portfolio | 18 video cards across 9 categories with live filter buttons and a YouTube embed modal |
| 📬 Lead capture | Email subscription and contact form saved to Google Sheets through Apps Script, with a localStorage fallback for local testing |
| 🔎 SEO | Meta tags, semantic HTML, alt text and lazy-loaded images |

[![Live](https://img.shields.io/badge/LIVE-SITE-22c55e?style=flat-square)](YOUR_EDITKARO_LIVE_URL)
[![GitHub Repo](https://img.shields.io/badge/GITHUB-REPO-181717?style=flat-square&logo=github)](https://github.com/happyhsaini/EditKaro.in)

---

## 🧠 Skills Map

```mermaid
mindmap
  root((Happy Saini))
    Languages
      C++
      Java
      Python
      C
      JavaScript
    Frontend
      HTML
      CSS
      JavaScript
      React
      Next.js
    Backend
      Flask
      FastAPI
      REST APIs
      JWT and RBAC
    AI / ML & Data
      NLP TF-IDF
      Feature Engineering
      Model Development
      Tableau
      Power BI
    Databases
      SQL
      DBMS
      PostgreSQL
    Core CS
      DSA
      OOP
      Operating Systems
    Tools
      Git
      GitHub
      Linux
      Docker
```

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![React](https://img.shields.io/badge/React-20232a?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)

</div>

---

## 📊 GitHub Analytics

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=happyhsaini&show_icons=true&theme=tokyonight&hide_border=true" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=happyhsaini&layout=compact&theme=tokyonight&hide_border=true" />

<img src="https://streak-stats.demolab.com?user=happyhsaini&theme=tokyonight&hide_border=true" />

</div>

---

## 📬 Let's talk

<div align="center">

### `I learn it, build it, and ship it.`

[![Email Me](https://img.shields.io/badge/EMAIL_ME-ef4444?style=for-the-badge&logo=gmail&logoColor=white)](mailto:happyhsaini990@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white)](YOUR_LINKEDIN_URL)

![Profile Views](https://komarev.com/ghpvc/?username=happyhsaini&label=Profile%20Views&color=7c3aed&style=flat)

</div>
