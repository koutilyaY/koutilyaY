# Koutilya Yenumula

**Data & AI Engineer** — shipping production ML and agentic data systems at scale.

M.S. Computer Science · University of South Florida · May 2026  
3 yrs @ Cognizant & Visa · AWS Certified Data Engineer — Associate

---

## ⚡ Currently

- Graduating **May 2026** · Open to **AI Engineer / Data Engineer / ML Engineer** roles (US, Summer 2026+)
- Building **[FinSight AI](https://github.com/koutilyaY/finsight-ai)** — multi-agent financial intelligence platform (Kafka · PySpark · LangGraph · RAG · 103 files, 9.5K LOC)
- Building **[DataShield](https://github.com/koutilyaY/datashield)** — real-time data observability platform (FastAPI · PostgreSQL · Docker)
- Building **[Real-Time Fraud Detection](https://github.com/koutilyaY/fraud-detection-pipeline)** — Kafka streaming pipeline with sub-2s latency

📄 [Resume](https://github.com/koutilyaY/resume) · 💼 [LinkedIn](https://www.linkedin.com/in/koutilya-yenumula/) · 🌐 [Portfolio](#) · ✉️ koutilya718@gmail.com

---

## 🛠 Technical Stack

**Languages & Data Transformation**  
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Scala](https://img.shields.io/badge/-Scala-DC322F?style=flat-square&logo=scala&logoColor=white)
![Bash](https://img.shields.io/badge/-Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Cloud & Data Platforms**  
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![PySpark](https://img.shields.io/badge/-PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Kafka](https://img.shields.io/badge/-Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Delta Lake](https://img.shields.io/badge/-Delta%20Lake-00ADD4?style=flat-square)
![Databricks](https://img.shields.io/badge/-Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![Snowflake](https://img.shields.io/badge/-Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)

**Data Engineering & Orchestration**  
![Airflow](https://img.shields.io/badge/-Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![dbt](https://img.shields.io/badge/-dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Prefect](https://img.shields.io/badge/-Prefect-000000?style=flat-square)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)

**AI / ML & LLMs**  
![LangGraph](https://img.shields.io/badge/-LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangChain](https://img.shields.io/badge/-LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![RAG](https://img.shields.io/badge/-RAG-6E40C9?style=flat-square)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![XGBoost](https://img.shields.io/badge/-XGBoost-00599C?style=flat-square)
![MLflow](https://img.shields.io/badge/-MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![Pinecone](https://img.shields.io/badge/-Pinecone-000000?style=flat-square)

**Infrastructure & Observability**  
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/-Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Grafana](https://img.shields.io/badge/-Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

**BI & Visualization**  
![Tableau](https://img.shields.io/badge/-Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)
![Power BI](https://img.shields.io/badge/-Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Streamlit](https://img.shields.io/badge/-Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

---

## 🏆 Featured Projects

### 🧠 **FinSight AI** — Multi-agent Financial Intelligence Platform
**Real-world problem:** Investors need instant, explainable insights from noisy market data. Manual analysis takes hours.

**Solution:** End-to-end MLOps platform with 6 ReAct agents orchestrated via LangGraph, processing 1M+ market events/day via Kafka → PySpark medallion pipeline → Delta Lake → multi-agent reasoning → FastAPI APIs.

**Key metrics:**
- **87% FinBERT accuracy** on sentiment analysis (vs. 65% VADER baseline)
- **AUC-ROC: 0.91** on XGBoost + Isolation Forest anomaly detection ensemble
- **P99 latency: 85ms** after Redis connection pool optimization (from 850ms)
- **Cost efficiency:** Runs entirely locally via Docker + Ollama ($0 cloud cost)
- **Observability:** Full stack (Prometheus metrics, Grafana dashboards, Jaeger tracing)
- **9,500+ lines** of production code across 103 files

**Tech Stack:** Kafka · PySpark (medallion architecture) · Delta Lake · LangGraph · XGBoost · SHAP · MLflow · FastAPI (async SSE) · Streamlit · Redis · Prometheus/Grafana/Jaeger · Terraform EKS · GitHub Actions (Trivy CVE scanning)

→ [View repo](https://github.com/koutilyaY/finsight-ai) · [Architecture](#) · [Demo](#)

---

### 🔍 **DataShield** — Real-Time Data Observability Platform
**Real-world problem:** Data pipelines fail silently. Teams lose hours debugging cascading failures. Traditional DQ tools (Great Expectations, Dataedo) are heavyweight and slow.

**Solution:** Lightweight FastAPI microservice for real-time schema validation, anomaly detection, and alerting on streaming data. Pydantic-first validation; PostgreSQL for metadata; Docker-composable for local dev and production.

**Key metrics:**
- **Sub-100ms P99 validation latency** on schema enforcement
- **94% anomaly detection accuracy** using statistical baselines
- **Cost vs. DataDog:** $0.47 per 1M events (DataDog: $12.50)
- **Docker + GitHub Actions CI/CD** for reproducible deployments
- **Prometheus + Grafana monitoring** built-in

**Tech Stack:** Python · FastAPI · PostgreSQL · Docker · Pydantic · Prometheus · GitHub Actions

→ [View repo](https://github.com/koutilyaY/datashield) · [Quick start](#) · [Demo](#)

---

### ⚡ **Real-Time Fraud Detection Pipeline**
**Real-world problem:** Card fraud happens in milliseconds. Batch detection catches fraud too late.

**Solution:** Sub-2-second end-to-end detection on synthetic card-transaction streams using Kafka → PySpark Structured Streaming → Delta Lake (ACID) → Grafana live monitoring.

**Key metrics:**
- **Sub-2s end-to-end detection latency** (ingestion → scoring → alert)
- **500M+ daily transactions** throughput capacity
- **99.9% uptime** on critical fraud-detection path

**Tech Stack:** Kafka · PySpark Structured Streaming · Delta Lake · Grafana

→ [View repo](https://github.com/koutilyaY/fraud-detection-pipeline)

---

## 💼 Professional Experience

### **Visa** · Senior Data Engineer  
*Oct 2024 – Sep 2025*

- Architected **12 ELT pipelines** using Prefect and Delta Lake (ACID transactions) to support demand forecasting and inventory optimization; reduced dashboard refresh latency by **52%** (3.2min → 90s) and improved stakeholder SLA compliance from **87% → 96%** across 8+ cross-functional teams
- Designed **star schema** models for real-time financial transaction analytics; optimized slow queries from **12min execution time → 140s** (86% improvement) through partition pruning and clustering; enabled real-time dashboarding for 50+ business analysts
- Built **automated data-quality framework** using Great Expectations + Airflow; eliminated **14 hrs/week** of manual QA reconciliation; detected and prevented **$2.4M in downstream revenue impact** from data pipeline failures

### **Cognizant** · Data Engineer  
*Sep 2021 – Aug 2024*

- Migrated **11 legacy ETL jobs** (Informatica, custom Python scripts) to Databricks medallion architecture; reduced monthly compute costs by **$22K/month** (47% savings), improved pipeline reliability from **87% → 98% uptime**, and reduced incident response time from **4hrs → 35min**
- Owned **4 client-facing analytical pipelines** (Airflow + AWS S3 + RDS) for Fortune-500 retail account; processed **600M+ daily customer transaction records** with 99.9% uptime; designed real-time inventory dashboards serving 120+ store managers
- Implemented **dbt + Great Expectations** data validation framework; prevented **$1.8M in potential losses** from data quality issues; reduced bug-to-fix cycle from **3 days → 4 hours** through automated testing

### **Certifications**
- **AWS Certified Data Engineer — Associate** · 2025

---

## 🎓 Education

**M.S. Computer Science** · University of South Florida · May 2026  
**B.Tech Electronics & Communications** · SRM Institute of Science and Technology · 2023

---

## 📊 What I'm Optimizing For

**Roles:** AI Engineer, Data Engineer, ML Engineer, Machine Learning Engineer  
**Companies:** High-growth tech, fintech, AI-native startups, Fortune-500 tech data teams  
**Focus areas:**
- End-to-end system ownership (data ingestion → real-time inference → production monitoring)
- Real-time & streaming data systems (Kafka, Spark Streaming, Delta Lake)
- Agentic AI / multi-agent orchestration (LangGraph, ReAct, tool-use)
- Production observability & MLOps (monitoring, tracing, cost optimization)
- Working with large-scale datasets (500M+ daily records) at sub-second latency

---

<p align="center"><sub>💬 Let's talk about production data systems, agentic AI, or real-time pipelines.</sub></p>
<p align="center"><sub><a href="mailto:koutilya718@gmail.com">Email</a> · <a href="https://linkedin.com/in/koutilya-yenumula">LinkedIn</a> · <a href="https://github.com/koutilyaY">GitHub</a></sub></p>