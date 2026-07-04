<div align="center">

<!-- ============================ HERO ============================ -->

<img width="100%" src="./header.svg" alt="Koutilya Yenumula — Data & AI Engineer"/>

<!-- ============================ TYPING ============================ -->

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=800&color=C724B1&center=true&vCenter=true&width=840&lines=Shipping+production+ML+systems+at+scale.;Kafka+%E2%86%92+Spark+%E2%86%92+Delta%2FIceberg+%E2%86%92+Decisions.;Real-time+fraud+scoring+on+streaming+data.;Multi-agent+AI+orchestration+with+LangGraph.)](https://github.com/koutilyaY)

<!-- ============================ SOCIAL ============================ -->

<p>
  <a href="https://portfolio-rosy-tau-67.vercel.app"><img src="https://img.shields.io/badge/%F0%9F%8C%90_Live_Portfolio-6E1FB8?style=for-the-badge&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/koutilyayenumula"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:koutilya718@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://github.com/koutilyaY/resume"><img src="https://img.shields.io/badge/Resume-C724B1?style=for-the-badge&logo=readthedocs&logoColor=white"/></a>
</p>

<!-- Verifiable certification — replace CREDLY_URL with your Credly badge link -->
<p>
  <a href="https://www.credly.com/users/koutilyayenumula"><img src="https://img.shields.io/badge/AWS_Certified-Data_Engineer_Associate-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/></a>
</p>

### 🌐 [Explore my work, live → **portfolio-rosy-tau-67.vercel.app**](https://portfolio-rosy-tau-67.vercel.app)

### I architect real-time data platforms that turn event streams into decisions — at scale, with sub-second latency.

**Data & AI Engineer** specializing in streaming lakehouses, agentic AI, and production MLOps.
**M.S. Computer Science** (May 2026, USF) · **3 yrs** enterprise data engineering @ Cognizant · **AWS Certified Data Engineer**

<br/>

<!-- ============================ IMPACT AT A GLANCE ============================ -->

<table>
<tr>
  <td align="center"><b>⚡ Real-time</b><br/><sub>Kafka → Flink streaming</sub></td>
  <td align="center"><b>🤖 6-agent</b><br/><sub>LangGraph (FinSight)</sub></td>
  <td align="center"><b>📈 600M+</b><br/><sub>daily records (prod)</sub></td>
  <td align="center"><b>💰 $3.4M+</b><br/><sub>quantified impact</sub></td>
  <td align="center"><b>🛠️ 6</b><br/><sub>production-grade builds</sub></td>
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

- 🔭 **Currently:** Shipping **real-data analyses** (NYC 311, e-commerce conversion) and a **HIPAA-aware clinical data platform** (FHIR/HL7); building real-time lakehouses with Flink + Iceberg + dbt.
- 🔍 **Target Roles:** AI Engineer · Data Engineer · ML Engineer *(US-based · available now)*
- 💡 **Passion:** Real-time data systems, agentic AI orchestration, production observability, sub-millisecond latency
- 📧 **Let's Talk:** [koutilya718@gmail.com](mailto:koutilya718@gmail.com) · [LinkedIn](https://www.linkedin.com/in/koutilyayenumula) · [Resume](https://github.com/koutilyaY/resume)

---

## 🏆 Flagship Builds

> Production-grade systems with real architecture, real tests, and measured impact.

### 1️⃣ [Real-Time Supply-Chain Data Platform](https://github.com/koutilyaY/Real-time-supply-chain-data-platform) — Event-Driven Lakehouse
**Problem:** Supply chains run on batch data — ERP, WMS, TMS, and IoT signals arrive hours late and siloed, so stockouts and cold-chain excursions are noticed only after the damage is done.
**Solution:** A fully open-source, event-driven **lakehouse** delivering up-to-the-second visibility across inventory, orders, shipments, and IoT — with streaming ML, RAG assistant, and a what-if digital twin. **No managed or paid services.**

```text
  ERP · WMS · TMS · IoT
          │ events
          ▼
 ┌─────────────────┐   ┌──────────────┐   ┌──────────────────────────┐
 │  Kafka          │──►│ Apache Flink │──►│  Apache Iceberg (MinIO)  │
 │  + Debezium CDC │   │  4 stream    │   │  Bronze → Silver → Gold  │
 │  + Schema Reg.  │   │  jobs · 1min │   └────────────┬─────────────┘
 └─────────────────┘   └──────────────┘                │
                                          ┌────────────┼──────────────┐
                                          ▼            ▼              ▼
                                    ┌──────────┐ ┌────────────┐ ┌───────────┐
                                    │   dbt    │ │ Trino +    │ │  ML / RAG │
                                    │  Gold DQ │ │ FastAPI    │ │  + Digital│
                                    │ +lineage │ │  serving   │ │   Twin    │
                                    └──────────┘ └────────────┘ └───────────┘
       Orchestrated by Dagster · Observed by Prometheus · Hardened: PII masking + API auth
```

| Capability | Detail |
|------------|--------|
| **Streaming core** | Kafka + **Apache Flink** (4 real-time jobs, 1-min windows) |
| **Open lakehouse** | **Apache Iceberg** on MinIO — Bronze → Silver → Gold |
| **CDC + governance** | Debezium CDC · Avro/Schema Registry · PII masking · API auth |
| **Serving & ops** | Trino + FastAPI · Dagster–dbt lineage · Prometheus alerts |

`Kafka` · `Flink` · `Iceberg` · `Trino` · `dbt` · `Dagster` · `Debezium` · `MLflow` · `MinIO` · `FastAPI`

---

<details>
<summary><b>2️⃣ &nbsp;ReadmitGuard</b> — 30-Day Readmission Prevention (Healthcare) &nbsp;·&nbsp; <code>FHIR/HL7 · HIPAA · Iceberg</code></summary>

<br/>

🔗 **[github.com/koutilyaY/readmitguard](https://github.com/koutilyaY/readmitguard)**

**Problem:** Medicare penalizes hospitals up to 3% of reimbursement for excess 30-day readmissions (HRRP) — but the signal is buried in siloed, standards-heavy clinical data.
**Solution:** A real-time clinical platform that ingests **HL7 v2 ADT + FHIR R4**, lands it in a **HIPAA-aware medallion lakehouse** (Safe Harbor de-identification), and scores readmission risk at discharge — returning a FHIR **RiskAssessment**.

| Aspect | Detail |
|--------|--------|
| **Standards** | FHIR R4 · HL7 v2 ADT · ICD-10 / LOINC / RxNorm |
| **Clinical methods** | LACE index · Charlson comorbidity · CMS-HRRP cohorts |
| **Compliance** | HIPAA Safe Harbor de-id · MRN tokenization · audit log |
| **Stack** | Kafka → Spark → Iceberg → dbt → Dagster · XGBoost · FastAPI |

`FHIR` · `HL7` · `Kafka` · `Spark` · `Iceberg` · `dbt` · `Dagster` · `XGBoost` · `FastAPI`

</details>

---

<details>
<summary><b>3️⃣ &nbsp;FinSight AI</b> — Multi-Agent Financial Intelligence &nbsp;·&nbsp; <code>LangGraph · Kafka · Spark</code></summary>

<br/>

🔗 **[github.com/koutilyaY/finsight-ai](https://github.com/koutilyaY/finsight-ai)**

**Problem:** Investors manually analyze market data for hours — slow, error-prone, expensive.
**Solution:** End-to-end MLOps platform with **6 ReAct agents (LangGraph)** over a Kafka → PySpark medallion → Delta Lake pipeline, with Feast/Redis features and streaming FastAPI/Streamlit serving.

| Aspect | Detail |
|--------|--------|
| **Agents** | 6 ReAct agents orchestrated with LangGraph |
| **Pipeline** | Kafka/Avro → Spark medallion → Delta Lake → Feast/Redis |
| **ML** | XGBoost + Isolation Forest anomaly detection · FinBERT sentiment |
| **Serving & Ops** | FastAPI (async SSE) · Streamlit · Prometheus/Grafana/Jaeger · Terraform/EKS |

`Kafka` · `PySpark` · `Delta Lake` · `LangGraph` · `XGBoost` · `SHAP` · `MLflow` · `FastAPI (async SSE)` · `Redis` · `Prometheus/Grafana/Jaeger` · `Terraform EKS`

</details>

---

<details>
<summary><b>4️⃣ &nbsp;PayGuard</b> — Real-Time Fraud Detection &nbsp;·&nbsp; <code>Kafka · Spark · LightGBM</code></summary>

<br/>

🔗 **[github.com/koutilyaY/payguard-realtime-fraud](https://github.com/koutilyaY/payguard-realtime-fraud)**

**Problem:** Card fraud happens in milliseconds; batch detection is 24 hours too late.
**Solution:** Live Kafka events → Spark Structured Streaming → Delta Lake medallion → LightGBM scoring with real-time decisions and an analyst feedback loop.

| Aspect | Detail |
|--------|--------|
| **Streaming** | Kafka → Spark Structured Streaming → Delta medallion |
| **Model** | LightGBM scorer (synthetic data, MLflow-tracked) |
| **Signals** | velocity · high-value · account-takeover |
| **Serving** | FastAPI decision API · Streamlit dashboard |

`Kafka` · `PySpark Structured Streaming` · `Delta Lake` · `LightGBM` · `MLflow` · `FastAPI` · `Streamlit` · `Prometheus/Grafana`
→ [Live Dashboard](https://payguard-realtime-fraud-mmj5yjucgd9ekrl7dkfmoi.streamlit.app)

</details>

---

<details>
<summary><b>5️⃣ &nbsp;DataShield</b> — Real-Time Data Observability &nbsp;·&nbsp; <code>FastAPI · Anomaly ML · Lineage</code></summary>

<br/>

🔗 **[github.com/koutilyaY/DataShield](https://github.com/koutilyaY/DataShield)**

**Problem:** Pipeline failures cascade silently; heavyweight tools are slow.
**Solution:** Lightweight FastAPI service for real-time schema validation, anomaly detection, and lineage/blast-radius tracking — with a zero-infra demo mode.

| Aspect | Detail |
|--------|--------|
| **Tests** | 22 / 38 pass with no infra |
| **Detection** | anomaly ML on statistical baselines (synthetic) |
| **Validation** | real-time schema checks + lineage / blast-radius |

`Python` · `FastAPI` · `PostgreSQL` · `Pydantic` · `Docker` · `Prometheus` · `GitHub Actions`

</details>

---

<details>
<summary><b>6️⃣ &nbsp;DocuSense</b> — Contract Intelligence Agent &nbsp;·&nbsp; <code>Local-first RAG · Ollama · FAISS</code></summary>

<br/>

🔗 **[github.com/koutilyaY/docusense](https://github.com/koutilyaY/docusense)**

**Problem:** Legal teams spend days reviewing contracts for obligations, exceptions, risks.
**Solution:** Local-first RAG (FAISS + Ollama) over legal contracts — cited Q&A plus a risk-classification agent that flags obligations & risk clauses. 100% local, privacy-first.

`LangChain` · `RAG` · `FAISS` · `Ollama` · `FastAPI` · `Streamlit`

</details>

---

<details>
<summary><b>7️⃣ &nbsp;CreatorPulse</b> — Creator-Economy Burnout Prediction &nbsp;·&nbsp; <code>Causal Inference · Survival Analysis</code></summary>

<br/>

🔗 **[github.com/koutilyaY/creatorpulse](https://github.com/koutilyaY/creatorpulse)**

**Problem:** Creator churn quietly erodes platform revenue, but standard models can't separate correlation from causation or predict *when* burnout hits.
**Solution:** End-to-end DS system on **synthetic behavioral data** combining **XGBoost** prediction with **Causal Inference (DiD)**, **Survival Analysis**, and **A/B testing** to quantify retention levers.

`XGBoost` · `Causal Inference (DiD)` · `Survival Analysis` · `A/B Testing` · `Python`

</details>

---

## 🔬 Real-Data Analysis

> Public, real-world datasets — the messy-data rigor and honest reporting behind the platforms above.

<details>
<summary><b>📊 &nbsp;NYC 311 Response-Time Analysis</b> — 3.46M real requests &nbsp;·&nbsp; <code>DuckDB · dbt · SQL</code></summary>

<br/>

🔗 **[github.com/koutilyaY/nyc-311-analysis](https://github.com/koutilyaY/nyc-311-analysis)**

Every NYC 311 request filed in 2024 (**3.46M rows**, live NYC Open Data) analyzed for how fast the city actually responds. Shows the citywide "average" is a statistical trap — NYPD's ~1-hour closes hide housing's 4-day and taxi's 74-day tails — normalizes complaints per capita, and *measures* the heat-vs-temperature effect (r = −0.80) instead of asserting it. dbt medallion, data contracts, tests, and a right-censoring fix that changed the headline numbers.

`DuckDB` · `dbt` · `SQL` · `Dagster` · `Streamlit` · multi-source join · right-censoring

</details>

<details>
<summary><b>🧪 &nbsp;E-Commerce Conversion — is the model worth shipping?</b> &nbsp;·&nbsp; <code>XGBoost · SHAP · MLflow</code></summary>

<br/>

🔗 **[github.com/koutilyaY/online-shopper-conversion](https://github.com/koutilyaY/online-shopper-conversion)**

Real UCI session data (12,330 sessions) predicting purchase intent — validated **forward in time**, not with a flattering random split. Catches a near-leakage feature, benchmarks the model against a one-line business rule, and honestly recommends *against* shipping when the rule wins. Pandera contracts, MLflow tracking, FastAPI serving, model card.

`XGBoost` · `SHAP` · `MLflow` · `FastAPI` · `pandera` · temporal validation · PR-AUC

</details>

<div align="center">

**More:** [Churn Prediction](https://github.com/koutilyaY/churn-prediction) · [E-commerce Data Platform](https://github.com/koutilyaY/ecommerce-data-engineering-platform) · [Supply-Chain Analytics](https://github.com/koutilyaY/supply-chain-analytics)

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

<br/>

**Where I go deep**

```text
Streaming & Real-Time   Kafka · Flink · Spark        ▰▰▰▰▰▰▰▰▰▱
Lakehouse & Modeling    Iceberg · Delta · dbt        ▰▰▰▰▰▰▰▰▰▱
Cloud & Infra           AWS · Docker · K8s · TF      ▰▰▰▰▰▰▰▰▱▱
ML / MLOps              XGBoost · MLflow · SHAP      ▰▰▰▰▰▰▰▰▱▱
Agentic AI / LLM        LangGraph · RAG              ▰▰▰▰▰▰▰▱▱▱
```

---

## 📊 GitHub Signals

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=koutilyaY&show_icons=true&hide_border=true&count_private=true&include_all_commits=true&title_color=C724B1&icon_color=00E5FF&text_color=8b949e&bg_color=0d1117" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=koutilyaY&layout=compact&hide_border=true&langs_count=8&title_color=C724B1&text_color=8b949e&bg_color=0d1117" />

<img height="170" src="https://streak-stats.demolab.com?user=koutilyaY&hide_border=true&background=0d1117&stroke=C724B1&ring=00E5FF&fire=E25A1C&currStreakLabel=C724B1&sideLabels=8b949e&dates=8b949e" />

<img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=koutilyaY&bg_color=0d1117&color=00E5FF&line=C724B1&point=ffffff&area=true&hide_border=true" />

<!-- Contribution snake — generated by .github/workflows/snake.yml into the 'output' branch -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/koutilyaY/koutilyaY/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/koutilyaY/koutilyaY/output/github-contribution-grid-snake.svg" />
  <img width="95%" alt="Contribution snake animation" src="https://raw.githubusercontent.com/koutilyaY/koutilyaY/output/github-contribution-grid-snake.svg" />
</picture>

![trophies](https://github-profile-trophy.vercel.app/?username=koutilyaY&theme=radical&no-frame=true&no-bg=true&margin-w=4&column=7)

<!-- Full metrics dashboard — generated by .github/workflows/metrics.yml (needs METRICS_TOKEN secret) -->
<img width="95%" alt="GitHub metrics dashboard" src="./github-metrics.svg" />

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

<a href="mailto:koutilya718@gmail.com"><img src="https://img.shields.io/badge/Reach_out-C724B1?style=for-the-badge&logo=minutemailer&logoColor=white"/></a>

<sub><em>Production data systems · Agentic AI · Real-time pipelines · MLOps · System design</em></sub>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:00E5FF,50:C724B1,100:6E1FB8&height=120&section=footer&v=2" alt="footer"/>

</div>
