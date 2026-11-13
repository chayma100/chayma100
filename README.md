# Hi, I'm Chaima Zoghlami

I'm a final-year software engineering student at ENSI in Tunisia. I work on LLM-based systems (RAG, agents), NLP and machine learning, and I like taking a project all the way from model evaluation to deployment.

This summer I built a multi-agent platform at Talan, and last year I worked on energy forecasting at the LARODEC lab. I also co-founded Orbyx, ENSI's first AI club, and I'm its secretary general.

I'm looking for a 6-month end-of-studies internship (PFE) in generative AI and agentic systems.

---

## 🛠️ Tech Stack

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=databricks&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

**Generative AI & Agents**
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logo=langchain&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-BGE--M3%20%7C%20pgvector%20%7C%20BM25-6E40C9?style=flat)
![MCP](https://img.shields.io/badge/MCP-Model%20Context%20Protocol-000000?style=flat)
![LangSmith](https://img.shields.io/badge/LangSmith-1C3C3C?style=flat&logo=langchain&logoColor=white)

**AI & ML**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)

**Web & Backend**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)

**Data, MLOps & DevOps**
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat&logo=databricks&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=mlflow&logoColor=white)
![DVC](https://img.shields.io/badge/DVC-945DD6?style=flat&logo=dvc&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat&logo=jenkins&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat&logo=ansible&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

## 💼 Experience

- **Talan Tunisia — SummerCamp 2026** (Jul – Aug 2026): *Wink*, a generative-AI platform supporting startups
- **ENSI / LARODEC lab — Summer internship 2025** (industrial supervision: Capgemini France): time-series forecasting in the energy domain

---

## 🚀 Featured Projects

### 🧠 [Wink — Multi-Agent AI Platform for Startups](https://github.com/ghayaammari/wink)
> LangGraph · ReAct agents · RAG · BGE-M3 · pgvector · LangSmith

Summer internship project at Talan. A multi-agent platform where an orchestrator copilot delegates each question to specialized ReAct agents. RAG over verified legal sources (**Recall@8 of 98.3%**, **MRR of 0.75** on a 59-question golden set), a compliance-diagnosis workflow that generates risk-assessment reports, and agent evaluation with LangSmith, human-in-the-loop and guardrails.

---

### 🛒 [Text-to-SQL Agent on E-commerce Data (Olist)](https://github.com/chayma100/olist-lakehouse)
> Python · Databricks (Unity Catalog) · MCP · LangSmith · BM25 · FastAPI · Streamlit · GitHub Actions

ETL pipeline in a medallion architecture (bronze, silver, gold) on Databricks, plus a ReAct LLM agent that queries the gold layer through an MCP SQL server, with guardrails. Compared GPT-OSS 20B and Gemini Flash on 64 questions: GPT-OSS 20B selected (**89.3% Execution Accuracy**, 19.4 s median latency). FastAPI backend and Streamlit interface.

---

### 🌿 [AuraSkin — AI-Powered Cosmetic Ingredient Analyzer](https://github.com/chayma100/AuraSkin)
> Python · SciBERT · ResNet50 · TF-IDF · Grad-CAM · LIME · FastAPI · React · Supabase

Full-stack platform combining NLP and Computer Vision: OCR + NER pipeline (Tesseract v5, fine-tuned SciBERT, **F1 of 0.95**) to extract INCI ingredients from labels and barcodes, a multi-label toxicity classifier (**macro-F1 of 0.71**), and a fine-tuned ResNet50 for skin-type detection (**92.8% accuracy**) explained with Grad-CAM, LIME and Occlusion Sensitivity.

---

### ⚡ [Short-Term Electricity Load Forecasting with XAI](https://github.com/chayma100/energy-forecasting-with-xai-feature-selection)
> XGBoost · Random Forest · LSTM · GRU · SHAP · Optuna · Python

Summer internship at the LARODEC lab. Compared ML and DL models on 110,000+ hourly observations; best model **XGBoost (RMSE 53.27 MWh, MAPE 3.56%)**, with SHAP-guided feature selection and Optuna hyperparameter tuning.

---

### 🔁 [CI/CD DevOps Pipeline for a Spring Boot Microservice](https://github.com/asmamh1/country-service)
> Spring Boot · Jenkins · Maven · SonarQube · Docker · Ansible · Kubernetes · Prometheus · Grafana

Academic project at ENSI. Jenkins pipeline with Maven build, JUnit tests and SonarQube quality analysis, continuous delivery with Ansible, Docker and Kubernetes, and monitoring with Prometheus and Grafana.

---

### 📰 [Fake News Detection — End-to-End MLOps](https://github.com/chayma100/fake-news-detection-mlops)
> Python · scikit-learn · DVC · MLflow · FastAPI · Docker · GitHub Actions · React · Render

Reproducible 5-stage DVC pipeline on WELFake (62k articles) with experiment tracking in MLflow (**F1 of 0.92** on the fake class). FastAPI service tested with pytest, containerized with Docker, GitHub Actions CI on every push, and deployed on Render with a React frontend.

---

### 📚 [Library Management System](https://github.com/chayma100/Bibliotheque-Numerique-Systeme-de-gestion-en-C)
> C · Linked Lists · File I/O

Command-line library system with book inventory, multi-user sessions, borrow/return tracking, and an automatic penalty system.

---

### 🔧 [Mini Compiler](https://github.com/chayma100/mini-compiler-c)
> C

Mini compiler with lexical, syntactic and semantic analyzers and a code generator.

---

### ✈️ [GoMondo — Travel Agency Web App](https://github.com/chayma100/travel-agency-web-app)
> HTML · CSS · JavaScript · PHP

Responsive travel agency website with destination browsing, online reservations, and server-side logic for dynamic content.

---

## 🏆 Community & Competitions

- 🌱 Co-founder & Secretary General — **Orbyx**, ENSI's first AI club (2025 – 2026)
- 🤝 Active member — IEEE ENSI Student Branch and ENSI Robotics Association
- 🥉 3rd place — **Data Leaders 1.0** (2025) · Participant — **GODS** (2026), **IEEEXtreme** (2025)

---

## 🏅 Certifications

- 🎓 **Fundamentals of Deep Learning** — NVIDIA
- 🎓 **Computer Vision for Industrial Inspection** — NVIDIA
- 🎓 **Git Foundations** — DataCamp

---

## 🌐 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/Chaima-Zoghlami)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:chaima.zoghlami@ensi-uma.tn)
