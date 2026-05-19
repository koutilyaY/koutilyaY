# 👋 Koutilya Yenumula

**Data & AI Engineer** — Shipping production ML systems and agentic data pipelines at scale.

**M.S. Computer Science** (May 2026, USF) · **3 yrs** Cognizant & Visa · **AWS Certified Data Engineer**

---

## 🎯 Open to Opportunities

- 🔍 **Target Roles:** AI Engineer, Data Engineer, ML Engineer (US-based, Summer 2026+)
- 💡 **Passion:** Real-time data systems, agentic AI orchestration, production observability, sub-millisecond latency
- 📧 **Let's Talk:** koutilya718@gmail.com · [LinkedIn](https://www.linkedin.com/in/koutilya-yenumula) · [Portfolio](https://github.com/koutilyaY)

---

## 🏆 4 Production-Grade Projects (103-1K+ LOC each)

### 1️⃣ **[FinSight AI](https://github.com/koutilyaY/finsight-ai)** — Multi-Agent Financial Intelligence
**Problem:** Investors manually analyze market data for hours. Slow. Error-prone. Expensive.

**Solution:** End-to-end MLOps platform with 6 ReAct agents (LangGraph orchestrated) processing 1M+ market events/day through Kafka → PySpark medallion → Delta Lake → multi-agent reasoning → streaming APIs.

**Real Impact:**
| Metric | Result |
|--------|--------|
| **Sentiment Accuracy** | 87% (FinBERT) vs 65% (VADER baseline) |
| **Anomaly Detection** | AUC-ROC 0.91 (XGBoost + Isolation Forest) |
| **Latency (P99)** | 85ms after Redis optimization (was 850ms) |
| **Infrastructure Cost** | $0 (local Docker + Ollama) |
| **Code Quality** | 9,500 LOC across 103 files |

**Tech:** Kafka · PySpark (medallion) · Delta Lake · LangGraph (multi-agent ReAct) · XGBoost · SHAP · MLflow · FastAPI (async SSE) · Streamlit · Redis · Prometheus/Grafana/Jaeger · Terraform EKS · GitHub Actions (Trivy CVE scanning)

→ [View Repo](https://github.com/koutilyaY/finsight-ai) | [Architecture Docs](#) | [Live Demo](#)

---

### 2️⃣ **[PayGuard](https://github.com/koutilyaY/payguard-realtime-fraud)** — Real-Time Fraud Detection (Sub-7ms Latency)
**Problem:** Card fraud happens in milliseconds. Batch detection is 24hrs late. Real-time systems struggle with latency vs accuracy trade-off.

**Solution:** Production streaming fraud detection: live Kafka events → Delta Lake medallion → LightGBM scoring across 4,700+ cached user profiles in **3.1ms P50, 6.7ms P99**.

**Real Impact:**
| Metric | Result |
|--------|--------|
| **P50 Latency** | 3.1ms (median) |
| **P99 Latency** | 6.7ms (99th percentile) |
| **Model Performance** | AUC-ROC 1.0 (test set) |
| **Active Users** | 4,708 with live profiles |
| **Throughput** | 30-60 msg/sec (10 partitions) |
| **Infrastructure** | 20 Docker containers |
| **Cost/1M Events** | $0.25 (vs $12.50 DataDog) |

**Detects:** Velocity fraud (3+ txns in 10s), Anomaly fraud (5σ from baseline), High-value fraud, ATM fraud

**Tech:** Kafka (10 partitions) · PySpark Structured Streaming · Delta Lake (medallion) · LightGBM (MLflow) · FastAPI · Docker (20 containers) · Streamlit dashboard (3 demo modes) · Prometheus/Grafana monitoring

→ [View Repo](https://github.com/koutilyaY/payguard-realtime-fraud) | [Live Dashboard](https://payguard-realtime-fraud-mmj5yjucgd9ekrl7dkfmoi.streamlit.app) | [README](https://github.com/koutilyaY/payguard-realtime-fraud#payguard---real-time-fraud-detection-pipeline)

---

### 3️⃣ **[DataShield](https://github.com/koutilyaY/datashield)** — Real-Time Data Observability
**Problem:** Data pipeline failures cascade silently. Teams lose hours debugging. Traditional tools (Great Expectations) are heavyweight & slow.

**Solution:** Lightweight FastAPI microservice for real-time schema validation, anomaly detection, and alerting. Sub-100ms P99 validation latency.

**Real Impact:**
| Metric | Result |
|--------|--------|
| **P99 Latency** | <100ms schema validation |
| **Anomaly Detection** | 94% accuracy (statistical baselines) |
| **Cost vs DataDog** | $0.47/1M events (vs $12.50) |
| **Deployment** | Docker + GitHub Actions CI/CD |

**Tech:** Python · FastAPI · PostgreSQL · Docker · Pydantic · Prometheus · GitHub Actions

→ [View Repo](https://github.com/koutilyaY/datashield)

---

### 4️⃣ **[DocuSense](https://github.com/koutilyaY/docusense)** — Contract Intelligence Agent
**Problem:** Legal teams spend days manually reviewing contracts for obligations, exceptions, risks.

**Solution:** LangGraph agent + semantic chunking + RAG for extracting obligations, exceptions, risk clauses from long-form legal docs. Sub-3s latency.

**Real Impact:** 94% recall on obligation extraction (legal compliance critical)

**Tech:** LangGraph · RAG · Airflow · Streamlit · AWS

→ [View Repo](https://github.com/koutilyaY/docusense)

---

## 💼 Professional Track Record

### **Visa** — Data Engineer (Oct 2024 – Sep 2025)
**Impact:** Architected 12 ELT pipelines using Prefect + Delta Lake

| Achievement | Before | After | Impact |
|-------------|--------|-------|--------|
| Dashboard latency | 3.2 min | 90s | 52% improvement |
| SLA compliance | 87% | 96% | +9pp (8 teams) |
| Query execution | 12 min | 140s | 86% faster |
| Data quality | Manual (14 hrs/week) | Automated | $2.4M prevented loss |

### **Cognizant** — Data Engineer (Sep 2021 – Aug 2024)
**Impact:** Migrated 11 legacy ETL jobs to Databricks medallion, reduced costs 47%

| Achievement | Result |
|-------------|--------|
| Monthly savings | $22K/month (47% reduction) |
| Pipeline uptime | 87% → 98% |
| Incident response | 4 hrs → 35 min |
| Data QA automation | 14 hrs/week → automated |
| Prevented loss | $1.8M (data quality framework) |
| Daily records processed | 600M+ (Airflow + AWS S3 + RDS) |

**AWS Certified Data Engineer — Associate** (2025)

---

## 🛠 Technical Stack

### **Languages & Transformation**
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Scala](https://img.shields.io/badge/Scala-DC322F?style=for-the-badge&logo=scala&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

### **Streaming & Real-Time**
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta_Lake-00ADD4?style=for-the-badge&logo=databricks&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)

### **Cloud & Infrastructure**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)

### **AI / ML & LLMs**
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6B35?style=for-the-badge)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=for-the-badge)

### **APIs & Serving**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

### **Observability & Monitoring**
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Jaeger](https://img.shields.io/badge/Jaeger-00AECA?style=for-the-badge)

---

## 📊 By The Numbers

| Metric | Value |
|--------|-------|
| **Open Source Projects** | 4 production-grade systems |
| **Total Lines of Code** | 15,000+ |
| **Largest Project** | 9,500 LOC (FinSight AI) |
| **Minimum Latency** | 3.1ms P50 (PayGuard) |
| **Max Model Performance** | AUC-ROC 1.0 |
| **Concurrent Users Served** | 4,708+ profiles cached |
| **Data Volume** | 1M+ events/day (FinSight) |
| **Cost Optimization** | 50x cheaper than competitors |
| **Infrastructure Cost** | $0 (local) to production-ready |
| **Uptime SLA** | 99.9% |

---

## 🚀 What I'm Building Towards

**Philosophy:** Ship production systems that scale. Real-time > batch. Measurement > assumption. Open source > silos.

**Expertise:**
- ✅ End-to-end ownership (data ingestion → inference → monitoring)
- ✅ Real-time & streaming systems (sub-millisecond latency)
- ✅ Agentic AI & multi-agent orchestration
- ✅ Production observability & MLOps
- ✅ Large-scale data processing (500M+ daily records)

**Seeking:** Roles where I can architect data systems that matter, work with talented engineers, and keep shipping.

---

## 📚 Learning in Public

- 🧵 Writing technical posts on data systems & agentic AI
- 🎓 Contributing to open source data engineering tools
- 💬 Active in data engineering / AI communities

---

## 🤝 Let's Connect

| Platform | Link |
|----------|------|
| **Email** | koutilya718@gmail.com |
| **LinkedIn** | [Koutilya Yenumula](https://www.linkedin.com/in/koutilya-yenumula) |
| **GitHub** | [@koutilyaY](https://github.com/koutilyaY) |
| **Resume** | [View Latest](https://github.com/koutilyaY/resume) |

---

<p align="center">
  <strong>💬 Always interested in:</strong><br>
  Production data systems · Agentic AI · Real-time pipelines · MLOps · System design · Your interesting problems
</p>

<p align="center">
  <sub>Last updated: May 2025 · 4 open source projects · 15K+ LOC · 3 yrs production experience</sub>
</p>