<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0A0A0F&height=180&section=header&text=Ashmit%20Chatterjee&fontSize=42&fontColor=E8A020&animation=fadeIn" width="100%" alt="Ashmit Chatterjee Header" />
</p>

<p align="center">
  <a href="https://github.com/ash-myth">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&pause=1000&color=F0ECC4&center=true&vCenter=true&width=750&lines=NLP+Intern+%40+Miimansa+AI+(ABDM+Health+Stack);IEEE+Published+Researcher+(ICAICCIT+2025);National-Level+Shooter+%7C+Khelo+India+Gold+Medalist;Sub-Second+Retrieval+%C2%B7+Adaptive+ML+%C2%B7+Distributed+Pipelines" alt="Typing Subtitle" />
  </a>
</p>

<p align="center">
  <a href="https://linkedin.com/in/ashmit-chatterjee">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://ashmit-chatterjee.netlify.app">
    <img src="https://img.shields.io/badge/Portfolio-E8A020?style=for-the-badge&logo=googlechrome&logoColor=black" alt="Portfolio" />
  </a>
  <a href="https://leetcode.com/u/ash-myth/">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode" />
  </a>
  <a href="mailto:ashmit.chatterjee@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://drive.google.com/file/d/1EoN5iK2W9LIhbxiA475SmR4dkvYoP_Na/view?usp=sharing">
    <img src="https://img.shields.io/badge/Resume-4AE54A?style=for-the-badge&logo=googledrive&logoColor=black" alt="Resume" />
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=ash-myth&label=Profile%20Views&color=e8a020&style=flat-square" alt="Profile Views" />
</p>

---

### ⚡ Executive Overview

- **Current Engineering Focus:** Productionizing ABDM (Ayushman Bharat Digital Mission) compliance infrastructure at **Miimansa AI Systems** — handling high-throughput FHIR R4 clinical payloads, Redis event streaming, and cryptographic key exchange.
- **Academic Foundation:** B.Tech in Computer Science (Data Science) @ **Manav Rachna International Institute of Research and Studies** (CGPA: **8.95** | 2023–2027).
- **Core Philosophy:** *"In 10m Air Rifle, a 0.5mm variance turns a 10.9 into an 8. In Machine Learning, uncalibrated embeddings turn precision retrieval into noise. I build systems with the same discipline: deterministic, benchmarked, and tuned for extreme accuracy."*

---

### 🏢 Enterprise & Applied NLP Experience

#### **NLP Intern** · *Miimansa AI Systems Pvt. Ltd.* `(Jun 2026 — Present)`
- **ABDM Connector Infrastructure:** Engineered multi-tenant FastAPI webhook platform for NHA’s HIP/HIU national health stack; cleared Sandbox Exit on Milestones M1–M3 with live ABHA accounts across discovery, care-context linking, SMS notify, and consent lifecycle.
- **FHIR R4 & Cryptography:** Designed clinical document compiler, ABDM-compliant bundle attribution, Redis pub/sub event bus, demultiplexed consent workers, ephemeral ECDH key vault, and crypto-shredding sweepers for post-expiry purges.
- **Inpatient OCR Pipeline:** Built `pdfplumber` + `PyMuPDF` parser handling 455+ billing layouts; built schema classifiers and custom font-stack de-duplication (`de_quadruple()` / `de_double()`) mapped to unified NHCX schemas with confidence scoring.

#### **Data Science Intern** · *ShadowFox* `(Jun 2025 — Jul 2025)`
- **Time-Series Regression:** Engineered forecasting pipeline over 2,081 daily records with lag features, rolling averages, and log transforms; achieved **$R^2 = 0.87$** and **MAE = 22.14** with XGBoost via GridSearchCV & 5-fold TimeSeriesSplit.
- **AQI Analysis:** Surfaced 96% of Delhi readings exceeding hazardous PM2.5 thresholds; 6-class AQI categorization achieved **83% accuracy** on held-out test data.

#### **Data Analytics Intern** · *IBM SkillsBuild / CSRBOX* `(Jun 2024 — Aug 2024)`
- Geospatial & spatial risk analysis over 100,000+ UK road accident records in Power BI; cut reporting inconsistencies by 30% through multi-year pivot consolidations.

---

### 🔬 Star Repositories & Benchmarked AI Systems

| System | Architecture & Engineering Highlights | Key Benchmarks | Stack | Links |
|:---|:---|:---|:---|:---:|
| **[AdaptLearn AI](https://github.com/ash-myth/adaptive-learning-ai)** | Multi-stage adaptive course recommendation engine across 6 major platforms. SBERT + BM25 dual candidate retrieval, continuous 5-step α-ramp NMF collaborative filtering, and topological prerequisite DAG gating. | **64.6% CV Acc** (Difficulty)<br>**71.8% Acc** (Dropout Risk)<br>**0.5761** CF RMSE<br>**13,618** Courses Indexed | `Python` `FastAPI` `SBERT` `NMF` `HistGBM` `MLP` `PyTorch` | [Repo](https://github.com/ash-myth/adaptive-learning-ai) |
| **[Hindi ML Course Assistant](https://github.com/ash-myth/ml-course-assistant)** | Cross-lingual spoken RAG over 38 Hindi ML lectures. Transcribed into 17,619 timestamped chunks via Whisper. Two-stage FAISS (384D) + CrossEncoder reranking with ±30s context expansion. | **80% Hit@3**<br>**p95 839ms** Latency<br>**17,619** Timestamped Chunks<br>CI Quality Gate on Hit@3 | `FastAPI` `FAISS` `Whisper` `LangSmith` `Docker` `HF Spaces` | [Repo](https://github.com/ash-myth/ml-course-assistant) · [Live](https://ash-myth.github.io/ml-course-assistant) |
| **[AutoEDA Pro](https://github.com/ash-myth/autoeda-pro)** | Automated EDA & AutoML platform benchmarking 6 sklearn models with auto task routing. Pre-computed correlation suspect pairs ground a Groq Llama 3.3-70B analyst layer with zero column hallucinations. | **73.7% Acc** on Titanic<br>**0–100** Quality Score<br>**30MB+** Dataset Support<br>ReportLab PDF Export | `Streamlit` `Scikit-learn` `Groq API` `ReportLab` | [Repo](https://github.com/ash-myth/autoeda-pro) · [Live](https://autoeda-pro-ashmitchatterjee.streamlit.app/) |
| **[SCATT Analyser](https://github.com/ash-myth/scatt_analyser)** | Shooting session intelligence tool solving proprietary format lock-in. Reverse-engineered zlib-compressed `.scatt-expert` SQLite blobs; OpenCV 4× upscale + Tesseract 5.5 OCR across 35+ sessions. | **35+ Sessions** Parsed<br>Shot Archetype Detection<br>Fatigue-Delta Tracking<br>ReportLab PDF Export | `OpenCV` `Tesseract` `Streamlit` `SQLite` `ReportLab` | [Repo](https://github.com/ash-myth/scatt_analyser) · [Live](https://scattanalyser-ashmit.streamlit.app/) |
| **[AI Resume Matcher](https://github.com/ash-myth/AI_Resume_Ranker)** | Semantic candidate-to-job matching pipeline using BERT embeddings and NER to extract 100+ distinct skills per document. Scores similarity with sub-second inference across 50+ concurrent docs. | **100+** Skills Extracted<br>**50+** Concurrent Docs<br>Sub-second Inference | `BERT` `Sentence-Transformers` `Streamlit` `NLP` | [Repo](https://github.com/ash-myth/AI_Resume_Ranker) · [Live](https://resume-ranker-ashmitchatterjee.streamlit.app/) |
| **[Air Quality Prediction](https://github.com/ash-myth/AQI_Analysis)** | End-to-end time-series regression pipeline over 2,081 daily AQI records with lag features and 5-fold TimeSeriesSplit benchmarking. | **$R^2 = 0.87$**<br>**MAE = 22.14** (XGBoost)<br>**83%** 6-Class AQI Acc | `XGBoost` `Scikit-learn` `Pandas` `Seaborn` | [Repo](https://github.com/ash-myth/AQI_Analysis/blob/main/AQI_Prediction.ipynb) |

---

### 🛠️ Technical Arsenal

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,cpp,fastapi,docker,pytorch,tensorflow,scikitlearn,azure,gcp,postgres,sqlite,git,githubactions,linux&theme=dark" alt="Technical Stack" />
</p>

| Category | Tools, Libraries & Frameworks |
|:---|:---|
| **Languages & Core** | Python, C++, SQL, Bash, Data Structures & Algorithms (200+ LeetCode), OOP, DBMS, Computer Networks |
| **AI, NLP & Retrieval** | Sentence-Transformers (SBERT), FAISS, CrossEncoders, PyTorch, Scikit-learn, XGBoost, LangChain, Hugging Face, Whisper, RAG, BERT |
| **Backend & MLOps** | FastAPI, Docker, Redis (Pub/Sub), LangSmith (Tracing), GitHub Actions (CI/CD Quality Gates), Streamlit, OpenCV, Tesseract OCR |
| **Data & Cloud Infrastructure** | Microsoft Azure (DP-100 & AI-900), Google Cloud (GDG Cloud Kochi), Pandas, NumPy, Power BI, ReportLab |

---

### 📜 Research & Certifications

- 📄 **IEEE Publication:** *"Bridging Drug Discovery and Public Health: AI-Driven Web Platform with Symptom-Aware Chatbot"* — **ICAICCIT 2025** ([IEEE Xplore #11434437](https://ieeexplore.ieee.org/document/11434437)).
- ☁️ **Microsoft Certified:** Azure Data Scientist Associate (**DP-100**)
- ☁️ **Microsoft Certified:** Azure AI Fundamentals (**AI-900**)
- 🔮 **Oracle Certified:** OCI 2024 Certified AI Foundations Associate
- 🔮 **Oracle Certified:** Oracle AI Vector Search Certified Professional
- 🏆 **GDG Cloud Kochi:** Code Vipassana S14 Top 100 & S15 Exceptional (Serverless Data Agents & Agentic Cloud)
- 🎓 **DataCamp Certified:** AI Engineer for Data Scientists Associate

---

### 🎯 Competitive Sports: 10m Air Rifle Shooting

Dual-career athlete competing at the national and international levels in Olympic 10m Air Rifle:

| Competition | Stage / Event | Year | Medals / Result |
|:---|:---|:---:|:---|
| **6th Khelo India Youth Games** | Chennai, Tamil Nadu | 2024 | 🥇 **Gold Medal (First Place)** |
| **FISU World University Trials** | India Selection Trials | 2024 | 🏅 **4th Rank Nationally** |
| **National Shooting Championships** | National Governing Body | 2023–2025 | 🥇 **3 Gold**, 🥉 **4 Bronze Medals** |
| **SportsForAll Sponsorship Program** | New Delhi | 2024 | 🥇 **Winner (Champion of Champions ISSF Men)** · 🥇 1st Junior · 🥉 3rd Senior |
| **Indonesian Open Championship** | International Championship | 2020 | 🥉 **Bronze Medal** |
| **All India University Games** | Haryana | 2024 | 🥉 **Bronze Medal (Team)** · 5th Individual |
| **All India KSS Memorial Championships** | Bhopal, MP | 2024 & 2026 | 🥇 **2 Gold**, 🥈 **3 Silver Medals** |
| **54th West Bengal State Championship** | Asansol, WB | 2022 | 🏆 **Highest Medal Winner (11 Medals)** |

---

### 📈 Activity & Engineering Pulse

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ash-myth&show_icons=true&bg_color=0D1117&title_color=E8A020&text_color=C9D1D9&icon_color=E8A020&border_color=30363D&hide_border=false" height="165" alt="GitHub Stats" />
  <img src="https://streak-stats.demolab.com?user=ash-myth&theme=dark&background=0D1117&border=30363D&stroke=30363D&ring=E8A020&fire=E8A020&currStreakLabel=E8A020" height="165" alt="GitHub Streak" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ash-myth&layout=compact&bg_color=0D1117&title_color=E8A020&text_color=C9D1D9&border_color=30363D&hide_border=false" height="135" alt="Top Languages" />
</p>

---

<p align="center">
  <i>"Precision is everything — whether on the range or in the data."</i>
</p>
