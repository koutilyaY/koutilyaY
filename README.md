<div align="center">

<!-- ============================ HERO ============================ -->

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0B486B,50:2E86AB,100:6DD5FA&height=200&section=header&text=Koutilya%20Yenumula&fontSize=52&fontColor=ffffff&fontAlignY=36&desc=Data%20%26%20AI%20Engineer%20%7C%20Real-Time%20Pipelines%20%7C%20Agentic%20ML%20Systems&descSize=18&descAlignY=58&animation=fadeIn&v=2" alt="Koutilya Yenumula — Data & AI Engineer"/>

<!-- ============================ TYPING ============================ -->

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=800&color=2E86AB&center=true&vCenter=true&width=840&lines=Shipping+production+ML+systems+at+scale.;Kafka+%E2%86%92+Spark+%E2%86%92+Delta%2FIceberg+%E2%86%92+Decisions.;Sub-7ms+real-time+fraud+scoring.;Multi-agent+AI+orchestration+with+LangGraph.)](https://github.com/koutilyaY)

<!-- ============================ SOCIAL ============================ -->

<p>
  <a href="https://www.linkedin.com/in/koutilyayenumula"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:koutilya718@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://github.com/koutilyaY/resume"><img src="https://img.shields.io/badge/Resume-2E86AB?style=for-the-badge&logo=readthedocs&logoColor=white"/></a>
  <img src="https://komarev.com/ghpvc/?username=koutilyaY&style=for-the-badge&color=2E86AB&label=PROFILE+VIEWS"/>
</p>

### I architect real-time data platforms that turn event streams into decisions — at scale, with sub-second latency.

**Data & AI Engineer** specializing in streaming lakehouses, agentic AI, and production MLOps.
**M.S. Computer Science** (May 2026, USF) · **3 yrs** enterprise data engineering @ Cognizant · **AWS Certified Data Engineer**

<br/>

<!-- ============================ IMPACT AT A GLANCE ============================ -->

<table>
<tr>
  <td align="center"><b>⚡ 3.1ms</b><br/><sub>P50 fraud scoring</sub></td>
  <td align="center"><b>🛰️ 1M+/day</b><br/><sub>events orchestrated</sub></td>
  <td align="center"><b>📈 600M+</b><br/><sub>daily records (prod)</sub></td>
  <td align="center"><b>💰 $3.4M+</b><br/><sub>quantified impact</sub></td>
  <td align="center"><b>🤖 6-agent</b><br/><sub>LangGraph systems</sub></td>
</tr>
</table>

</div>

---

## 🧬 whoami

```python
class KoutilyaYenumula:
    role        = "Data & AI Engineer"
    education   = "M.S. Computer Science — University of South Florida (May 2026)"
    experience  = "3 yrs production data systems @ Cognizant"
    cert        = "AWS Certified Data Engineer — Associate (2025)"
    focus       = ["real-time streaming", "agentic AI", "medallion lakehouse", "MLOps"]
    mission     = "Turn raw event streams into decisions before the moment passes."

    def ships(self) -> str:
        return "production systems, not notebooks-that-die-in-a-drawer"
```

---

## 🎯 Open to Opportunities

- 🔍 **Target Roles:** AI Engineer · Data Engineer · ML Engineer *(US-based, Summer 2026+)*
- 💡 **Passion:** Real-time data systems, agentic AI orchestration, production observability, sub-millisecond latency
- 📧 **Let's Talk:** [koutilya718@gmail.com](mailto:koutilya718@gmail.com) · [LinkedIn](https://www.linkedin.com/in/koutilyayenumula) · [Resume](https://github.com/koutilyaY/resume)

---

## 🏆 Flagship Builds

> Production-grade systems with real architecture, real tests, and measured impact.

### 1️⃣ [FinSight AI](https://github.com/koutilyaY/finsight-ai) — Multi-Agent Financial Intelligence
**Problem:** Investors manually analyze market data for hours — slow, error-prone, expensive.
**Solution:** End-to-end MLOps platform with **6 ReAct agents (LangGraph)** processing **1M+ market events/day** through Kafka → PySpark medallion → Delta Lake → multi-agent reasoning → streaming APIs.

| Metric | Result |
|--------|--------|
| **Sentiment Accuracy** | 87% (FinBERT) vs 65% (VADER baseline) |
| **Anomaly Detection** | AUC-ROC 0.91 (XGBoost + Isolation Forest) |
| **Latency (P99)** | 85ms after Redis optimization (was 850ms) |
| **Code Quality** | 9,500 LOC across 103 files |

`Kafka` · `PySpark` · `Delta Lake` · `LangGraph` · `XGBoost` · `SHAP` · `MLflow` · `FastAPI (async SSE)` · `Redis` · `Prometheus/Grafana/Jaeger` · `Terraform EKS`

---

### 2️⃣ [PayGuard](https://github.com/koutilyaY/payguard-realtime-fraud) — Real-Time Fraud Detection *(Sub-7ms)*
**Problem:** Card fraud happens in milliseconds; batch detection is 24 hours too late.
**Solution:** Live Kafka events → Delta Lake medallion → LightGBM scoring across **4,700+ cached user profiles** at **3.1ms P50 / 6.7ms P99**.

| Metric | Result |
|--------|--------|
| **P50 / P99 Latency** | 3.1ms / 6.7ms |
| **Model Performance** | AUC-ROC 1.0 (test set) |
| **Throughput** | 30–60 msg/sec (10 partitions) |
| **Cost / 1M Events** | $0.25 (vs $12.50 DataDog) |

**Detects:** velocity fraud · 5σ anomalies · high-value · ATM fraud
`Kafka` · `PySpark Structured Streaming` · `Delta Lake` · `LightGBM` · `MLflow` · `FastAPI` · `Streamlit` · `Prometheus/Grafana`
→ [Live Dashboard](https://payguard-realtime-fraud-mmj5yjucgd9ekrl7dkfmoi.streamlit.app)

---

### 3️⃣ [DataShield](https://github.com/koutilyaY/DataShield) — Real-Time Data Observability
**Problem:** Pipeline failures cascade silently; heavyweight tools are slow.
**Solution:** Lightweight FastAPI microservice for real-time schema validation, anomaly detection, and alerting at **<100ms P99**.

| Metric | Result |
|--------|--------|
| **P99 Latency** | <100ms schema validation |
| **Anomaly Detection** | 94% accuracy (statistical baselines) |
| **Cost vs DataDog** | $0.47 / 1M events (vs $12.50) |

`Python` · `FastAPI` · `PostgreSQL` · `Pydantic` · `Docker` · `Prometheus` · `GitHub Actions`

---

### 4️⃣ [DocuSense](https://github.com/koutilyaY/docusense) — Contract Intelligence Agent
**Problem:** Legal teams spend days reviewing contracts for obligations, exceptions, risks.
**Solution:** LangGraph agent + semantic chunking + RAG extracting obligations & risk clauses from long-form legal docs at **sub-3s latency, 94% recall**.

`LangGraph` · `RAG` · `Airflow` · `Streamlit` · `AWS`

---

### ⚡ Plus: [Real-Time Supply-Chain Platform](https://github.com/koutilyaY/Real-time-supply-chain-data-platform)
End-to-end streaming lakehouse — **Kafka + Avro/Schema Registry → Debezium CDC → Spark medallion → Apache Iceberg → dbt**, hardened with PII masking, API auth + rate limiting, Prometheus alerts, and Dagster–dbt lineage.
`Kafka` · `Iceberg` · `dbt` · `Dagster` · `Debezium`

<div align="center">

**More:** [Churn ($1.6M impact)](https://github.com/koutilyaY/churn-prediction) · [Enterprise Data Platform](https://github.com/koutilyaY/enterprise-data-platform) · [Commerce Analytics on AWS](https://github.com/koutilyaY/commerce-analytics-aws) · [Credit-Card Segmentation](https://github.com/koutilyaY/credit-card-customer-segmentation)

</div>

---

## 💼 Professional Track Record

### **Cognizant** — Data Engineer *(Sep 2021 – Aug 2024)*
Migrated **11 legacy ETL jobs** to Databricks medallion; cut costs **47%**.

| Achievement | Result |
|-------------|--------|
| Monthly savings | $22K/month (47% reduction) |
| Pipeline uptime | 87% → 98% |
| Incident response | 4 hrs → 35 min |
| Prevented loss | $1.8M (data quality framework) |
| Daily records processed | 600M+ (Airflow + S3 + RDS) |

---

## 🛠️ Arsenal

<div align="center">

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Scala](https://img.shields.io/badge/Scala-DC322F?style=flat-square&logo=scala&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Streaming & Processing**
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Spark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Debezium](https://img.shields.io/badge/Debezium_CDC-FF6E42?style=flat-square&logo=redhat&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta_Lake-00ADD4?style=flat-square&logo=databricks&logoColor=white)
![Iceberg](https://img.shields.io/badge/Apache_Iceberg-1C9BD6?style=flat-square&logo=apache&logoColor=white)

**Orchestration & Cloud**
![Dagster](https://img.shields.io/badge/Dagster-654FF0?style=flat-square&logo=dagster&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)

**AI / ML & Serving**
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat-square&logo=xgboost&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

**Observability**
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Jaeger](https://img.shields.io/badge/Jaeger-00AECA?style=flat-square&logo=jaeger&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)

</div>

---

## 📊 GitHub Signals

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=koutilyaY&show_icons=true&hide_border=true&count_private=true&include_all_commits=true&title_color=2E86AB&icon_color=6DD5FA&text_color=8b949e&bg_color=0d1117" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=koutilyaY&layout=compact&hide_border=true&langs_count=8&title_color=2E86AB&text_color=8b949e&bg_color=0d1117" />

<img height="170" src="https://streak-stats.demolab.com?user=koutilyaY&hide_border=true&background=0d1117&stroke=2E86AB&ring=6DD5FA&fire=E25A1C&currStreakLabel=2E86AB&sideLabels=8b949e&dates=8b949e" />

<img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=koutilyaY&bg_color=0d1117&color=6DD5FA&line=2E86AB&point=ffffff&area=true&hide_border=true" />

![trophies](https://github-profile-trophy.vercel.app/?username=koutilyaY&theme=onedark&no-frame=true&no-bg=true&margin-w=4&column=7)

</div>

---

## 🧭 Engineering Principles

<div align="center">

| | |
|---|---|
| 🛰️ **Streaming-first** | Data has a shelf life — decide before the moment passes. |
| 🧱 **Medallion or it didn't happen** | Bronze → Silver → Gold, with contracts at every hop. |
| ✅ **Tests are infra** | Schema contracts, dbt tests, freshness SLAs — not optional. |
| 🤖 **Agents that act** | Pipelines that detect, decide, and remediate themselves. |
| 📟 **Observable by default** | Prometheus + lineage > hoping nothing broke overnight. |

</div>

---

<div align="center">

### 💬 Let's build something that ships.

<a href="mailto:koutilya718@gmail.com"><img src="https://img.shields.io/badge/Reach_out-2E86AB?style=for-the-badge&logo=minutemailer&logoColor=white"/></a>

<sub><em>Production data systems · Agentic AI · Real-time pipelines · MLOps · System design</em></sub>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:6DD5FA,50:2E86AB,100:0B486B&height=120&section=footer&v=2" alt="footer"/>

</div>
