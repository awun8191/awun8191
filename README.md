<div align="center">
  <h1>Dauda Nasir</h1>
  <p><b>Electrical &amp; Electronics Engineer · Full-Stack Systems Architect</b></p>
  <p>
    <i>Bridging low-power embedded hardware &amp; telemetry with high-concurrency cloud services, vector RAG pipelines, and cross-platform mobile apps.</i>
  </p>
  <p>
    <a href="https://raregazzetto.me"><img src="https://img.shields.io/badge/Portfolio-raregazzetto.me-0284c7?style=flat-square&logo=safari&logoColor=white" alt="Portfolio" /></a>
    <a href="https://play.google.com/store/apps/details?id=com.engineeringhub.engineeringhub"><img src="https://img.shields.io/badge/Google_Play-Engineering_Hub-34d399?style=flat-square&logo=googleplay&logoColor=white" alt="Google Play" /></a>
    <a href="https://linkedin.com/in/dauda-nasir-729357361"><img src="https://img.shields.io/badge/LinkedIn-Nasir_Dauda-0077b5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
    <a href="mailto:nasirdaud2015@gmail.com"><img src="https://img.shields.io/badge/Email-nasirdaud2015%40gmail.com-ea4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
    <img src="https://img.shields.io/badge/Location-Lagos%2C_Nigeria-334155?style=flat-square&logo=googlemaps&logoColor=white" alt="Location" />
  </p>
</div>

---

### ⚡ Verified Impact & Scale

| Metric | System | Architectural Context |
| :--- | :--- | :--- |
| **800–1,200 MAU** | **NUESA Academia** | Active monthly engineering students across 9 faculties at ABUAD |
| **99.98% Accuracy** | **Embedded Solar ML (FYP)** | Dual-layer edge inference (`RP2040` CUSUM + `Pi Zero 2W` XGBoost) @ ~3 mW idle |
| **2,000+ PDFs** | **CourseGen AI Pipeline** | Academic textbooks parsed, OCR-processed, and indexed via BGE-M3 embeddings |
| **273 Tests** | **AWUN Field Engine** | Automated unit & integration tests safeguarding escrow workflows and reporting |
| **Google Play** | **Engineering Hub** | Production cross-platform mobile application deployed on Android |

---

### 🛠️ Technical Stack & Tooling

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,fastapi,flutter,dart,typescript,react,c,cpp,postgres,cloudflare,gcp,aws,docker,linux,git" alt="Core Technologies: Python, FastAPI, Flutter, Dart, TypeScript, React, C, C++, PostgreSQL, Cloudflare, Google Cloud, AWS, Docker, Linux, Git" />
  </a>
</p>

| Category | Primary Technologies & Logos |
| :--- | :--- |
| **Languages & Systems** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white) ![C/C++](https://img.shields.io/badge/C%2FC%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white) |
| **Cloud & Distributed Infra** | ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white) ![Google Cloud Platform](https://img.shields.io/badge/Google_Cloud_Platform-4285F4?style=flat-square&logo=googlecloud&logoColor=white) ![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black) |
| **AI, ML, Agents & Vector Space** | ![Vector Databases](https://img.shields.io/badge/Vector_Databases-ChromaDB-FF6F00?style=flat-square) ![Vector Search](https://img.shields.io/badge/Vector_Search-Cloudflare_Vectorize-F38020?style=flat-square&logo=cloudflare&logoColor=white) ![RAG](https://img.shields.io/badge/RAG-Retrieval_Augmented_Gen-0284C7?style=flat-square) ![ML](https://img.shields.io/badge/ML-XGBoost-111111?style=flat-square) ![AI Integration](https://img.shields.io/badge/AI_Integration-Gemini_API-8E75C2?style=flat-square&logo=google&logoColor=white) ![AI Agents](https://img.shields.io/badge/AI_Agents-Tool_Use_%26_Workflows-6E40C4?style=flat-square&logo=openai&logoColor=white) |
| **Embedded & Telemetry** | ![Raspberry Pi Pico](https://img.shields.io/badge/RP2040_Pico_3mW-C51A4A?style=flat-square&logo=raspberrypi&logoColor=white) ![Pi Zero 2W](https://img.shields.io/badge/Pi_Zero_2W-C51A4A?style=flat-square&logo=raspberrypi&logoColor=white) ![CUSUM](https://img.shields.io/badge/CUSUM_Change_Point-334155?style=flat-square) ![Hardware Actuation](https://img.shields.io/badge/Stepper_Actuation-0284C7?style=flat-square) |
| **Client Platforms** | ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) |

---

### 🏛️ System Architecture & Vertical Slice

```
[ Layer 0: Physical & Embedded ML ]
  Raspberry Pi Pico (RP2040, ~3 mW) ── CUSUM statistical change-point filter
  Raspberry Pi Zero 2W             ── Triggered XGBoost classification (99.98% acc)
  Hardware Actuation               ── Lead-screw stepper motor & rotating brush
          │
          ▼ (Telemetry & Ingestion)
[ Layer 1: Distributed Cloud & Edge Compute ]
  Google Cloud Platform            ── Asynchronous FastAPI microservices
  Cloudflare                       ── Edge routing, signed uploads, S3-compatible R2 storage
  Data & Persistence               ── PostgreSQL, Cloudflare D1, Firestore
          │
          ▼ (Semantic Retrieval & Embeddings)
[ Layer 2: Applied AI & Client Surfaces ]
  Document AI Pipeline             ── Gemini Vision + BGE-M3 embeddings + ChromaDB (2K+ PDFs)
  Mobile & Web Surfaces            ── Flutter (Google Play) & React Admin Portal
```

---

### 🚀 Featured Engineering Systems

#### 🎓 [NUESA Academia](https://github.com/awun8191/NuesaWebsite) — Digital Learning Resource & AI Study Engine
> **Role:** Lead Systems Architect & Developer · **Impact:** 800–1,200 Monthly Active Users · **Status:** Production  
> **Links:** [raregazzetto.me](https://raregazzetto.me) · [GitHub Repository](https://github.com/awun8191/NuesaWebsite)

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F00?style=flat-square)
![Gemini](https://img.shields.io/badge/Gemini_API-8E75C2?style=flat-square&logo=google&logoColor=white)

- **Decoupled 3-Tier Architecture:** Built a high-throughput academic platform serving 9 engineering faculties at ABUAD. Uses an asynchronous FastAPI backend deployed to Google Cloud Platform with optimized search queries, Cloudflare managing direct streaming and signed uploads to Cloudflare R2 object storage, and a React administrative console with real-time analytics.
- **Document AI Pipeline:** Ingests 2,000+ technical engineering documents through a two-pass OCR pipeline (Tesseract for text, Gemini Vision for technical diagrams and schematics), generates dense 1024-dimensional embeddings via Cloudflare BGE-M3 into ChromaDB, and auto-generates departmental syllabi and question banks.
- **Stack:** FastAPI, React, TypeScript, Cloudflare, Firestore, Docker, Gemini API, ChromaDB.

---

#### ☀️ [AI Soiling Detection & Autonomous Cleaning System](https://raregazzetto.me) — Final Year Project (FYP)
> **Domain:** Embedded Systems & Edge Machine Learning · **Metric:** 99.98% Accuracy @ ~3 mW Idle · **Status:** B.Eng Thesis Defense  
> **Hardware:** Raspberry Pi Pico (RP2040) · Raspberry Pi Zero 2W · Irradiance & Dust Sensors · Stepper Actuator

![RP2040](https://img.shields.io/badge/RP2040_Pico-C51A4A?style=flat-square&logo=raspberrypi&logoColor=white)
![Pi Zero 2W](https://img.shields.io/badge/Pi_Zero_2W-C51A4A?style=flat-square&logo=raspberrypi&logoColor=white)
![C/C++](https://img.shields.io/badge/C%2FC%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost_99.98%25-111111?style=flat-square)
![CUSUM](https://img.shields.io/badge/CUSUM_Control_Chart-334155?style=flat-square)

- **Dual-Layer Energy-Constrained Architecture:** Engineered an autonomous cyber-physical system designed for off-grid photovoltaic arrays in high-dust regions without draining battery reserves:
  - **Layer 1 (Continuous Telemetry):** Ultra-low-power Raspberry Pi Pico (RP2040, ~3 mW) continuously samples environmental sensor inputs (irradiance, dust accumulation, temperature) and computes a Composite Soiling Index using a Cumulative Sum (CUSUM) statistical change-detection algorithm.
  - **Layer 2 (Triggered Classification):** Only upon sustained statistical drift does the RP2040 assert a hardware interrupt to wake a Raspberry Pi Zero 2W. The Pi Zero runs an XGBoost classifier (trained on HKUST photovoltaic datasets, achieving 99.98% accuracy) to verify soiling before actuating a bi-directional lead-screw stepper motor and cylindrical brush cleaning cycle.

---

#### 📱 [Engineering Hub](https://play.google.com/store/apps/details?id=com.engineeringhub.engineeringhub) — Cross-Platform Collaborative Academic Suite
> **Platform:** Mobile Application · **Distribution:** [Available on Google Play Store](https://play.google.com/store/apps/details?id=com.engineeringhub.engineeringhub) · **Status:** Production

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Google Play](https://img.shields.io/badge/Google_Play-Production-34D399?style=flat-square&logo=googleplay&logoColor=white)

- Cross-platform collaborative environment built for engineering students.
- Features biometric authentication, real-time academic resource synchronization, and an adaptive testing engine with domain-bounded RAG-lite query answering.
- Backed by automated document summarization and real-time cloud data pipelines.

---

#### 📑 [Textbook Parser & CourseGen](https://github.com/awun8191/CourseGen) — Document AI Ingestion Engine
> **Domain:** Applied AI & Vector Search · **Scale:** 2,000+ Technical Documents Ingested  
> **Links:** [GitHub Repository](https://github.com/awun8191/CourseGen)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F00?style=flat-square)
![Gemini Vision](https://img.shields.io/badge/Gemini_Vision-8E75C2?style=flat-square&logo=google&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

- High-throughput batch processing pipeline that converts unstructured, scanned engineering documents into semantic knowledge stores.
- Executes two-pass OCR, generates 1024-dimensional embeddings via Cloudflare BGE-M3, and indexes chunks inside ChromaDB.
- Automatically produces structured course outlines, modular examination question banks, and flashcards.

---

#### 🛡️ [AWUN](https://raregazzetto.me) — Subcontractor Field Operations Engine
> **Domain:** Field Automation & Billing Telemetry · **Quality:** 273 Automated Tests Passing

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Paystack](https://img.shields.io/badge/Paystack_Escrow-00C3F7?style=flat-square&logoColor=white)

- Checkout-first field operations platform engineered for engineering subcontractors and field operators.
- Features standardized milestone closeout checklists, photographic site reports stored in Cloudflare R2, automated discrepancy detection, and milestone-gated payment disbursement using Paystack.
- Backed by 273 automated unit and integration tests.

---

#### 🚨 [TRAKS](https://github.com/awun8191/TraksApi) — Incident Dispatch & Geospatial SOS Platform
> **Domain:** Emergency Telemetry & Semantic Search  
> **Links:** [API Repository](https://github.com/awun8191/TraksApi)

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Reverse Geocoding](https://img.shields.io/badge/Reverse_Geocoding-34A853?style=flat-square&logo=googlemaps&logoColor=white)

- Real-time emergency incident alert and community corroboration network.
- Implements reverse-geocoded spatial lookups, tamper-evident incident logging, and crowd-consensus verification (confirm/refute logic).
- Powers semantic similarity search across historical incident reports utilizing Cloudflare Vectorize.

---

#### 🔬 [RAST (ResearchDoi)](https://github.com/awun8191/ResearchDoi) — Autonomous Academic Research Assistant
> **Domain:** Academic Synthesis & RAG  
> **Links:** [GitHub Repository](https://github.com/awun8191/ResearchDoi)

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Google ADK](https://img.shields.io/badge/Google_ADK-4285F4?style=flat-square&logo=google&logoColor=white)
![DOI APIs](https://img.shields.io/badge/DOI_Resolution-334155?style=flat-square)

- Academic research workbench delivering deterministic citation linking, cross-reference mapping, and literature review synthesis.
- Parses DOI metadata, cross-verifies citations against academic indexing repositories, and structures draft thesis sections with verifiable academic citations.

---

### 📊 GitHub Telemetry & Engineering Activity

<div align="center">
  <img src="https://github-readme-stats-fast.vercel.app/api?username=awun8191&custom_title=Engineering%20Activity&show_icons=true&hide_rank=true&include_all_commits=true&hide=stars&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&icon_color=3fb950&border_color=30363d" alt="Engineering Activity" height="170" />
  &nbsp;&nbsp;
  <img src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=awun8191&layout=compact&hide=html,Go%20Template&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&border_color=30363d" alt="Most Used Languages" height="170" />
</div>

<p align="center">
  <a href="https://github.com/awun8191?tab=achievements">
    <img src="https://img.shields.io/badge/GitHub_Pro-000000?style=flat-square&logo=github&logoColor=white" alt="GitHub Pro" />
    <img src="https://img.shields.io/badge/Pull_Shark-x2-6e40c4?style=flat-square&logo=github&logoColor=white" alt="Pull Shark x2" />
    <img src="https://img.shields.io/badge/Pair_Extraordinaire-6e40c4?style=flat-square&logo=github&logoColor=white" alt="Pair Extraordinaire" />
    <img src="https://img.shields.io/badge/Quickdraw-6e40c4?style=flat-square&logo=github&logoColor=white" alt="Quickdraw" />
    <img src="https://img.shields.io/badge/YOLO-6e40c4?style=flat-square&logo=github&logoColor=white" alt="YOLO" />
  </a>
</p>

---

### 🏅 Certifications & Accreditations

- **NVIDIA Deep Learning Institute:** Deep Learning Practitioner
- **RAG Systems Development:** Advanced Vector Search & Chunking Architectures
- **AI Agent Engineering:** Autonomous Agent Orchestration & Tool-Calling Systems
- **B.Eng in Electrical and Electronics Engineering:** Afe Babalola University (ABUAD)

---

### 🤝 Connect & Collaborate

<div align="center">
  <a href="https://raregazzetto.me">
    <img src="https://img.shields.io/badge/Website-raregazzetto.me-0284c7?style=for-the-badge&logo=safari&logoColor=white" alt="Website" />
  </a>
  &nbsp;
  <a href="https://linkedin.com/in/dauda-nasir-729357361">
    <img src="https://img.shields.io/badge/LinkedIn-Nasir_Dauda-0077b5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  &nbsp;
  <a href="https://play.google.com/store/apps/details?id=com.engineeringhub.engineeringhub">
    <img src="https://img.shields.io/badge/Play_Store-Engineering_Hub-34d399?style=for-the-badge&logo=googleplay&logoColor=white" alt="Google Play" />
  </a>
  &nbsp;
  <a href="mailto:nasirdaud2015@gmail.com">
    <img src="https://img.shields.io/badge/Email-nasirdaud2015%40gmail.com-ea4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</div>

<div align="center">
  <sub>Lagos, Nigeria · © 2026 Dauda Nasir</sub>
</div>
