<img width="1440" height="3602" alt="image" src="https://github.com/user-attachments/assets/bdc5ddbb-7576-4900-9760-8d62c6ab4a87" />

## Hi, I'm [Alexander Tsai](https://linkedin.com/in/alexander-tsai-tw-eu) 👋
### 🛠️ Data Engineer · Fresh Graduate · Side Project Builder

Passionate about building end-to-end data pipelines and turning raw market data into actionable insights.
I enjoy working across the modern data stack — from ingestion and orchestration to storage and visualization.

---

### 🚀 Project Highlights

#### ⭐ Stock Analyzer US — Batch Pipeline
**Achievement**: Automated technical signal generation across 100+ US stock tickers with a fully reproducible batch pipeline.  
**Metric**: Reduced manual analysis time to near-zero, producing structured multi-period Parquet outputs (RSI, MACD, Bollinger Bands) per run.  
**Action**: Engineered with Python, Apache Airflow, DuckDB, and Docker — resolving production-edge issues such as pandas 2.2+ offset deprecation and NaN/inf serialization in Parquet export.  
[🔗 View Repo](https://github.com/alexandertsaidev/stock_analyzer_us_batch_pipeline)

---

#### ⭐ Stock US — Realtime Pipeline
**Achievement**: Achieved sub-second data ingestion from live US stock market feeds into a persistent object store.  
**Metric**: Demonstrated end-to-end streaming latency under 1 second with a multi-service architecture handling concurrent ticker streams.  
**Action**: Built with Python Kafka producers/consumers, Docker Compose, and MinIO — mirroring production-grade data lake patterns for real-time ingestion.  
[🔗 View Repo](https://github.com/alexandertsaidev/stock_us_realtime_pipeline)

---

#### ⭐ Airflow Workspace
**Achievement**: Established a fully operational Apache Airflow 3.x orchestration environment from scratch, enabling reliable DAG scheduling across all pipeline projects.  
**Metric**: Reduced pipeline setup time to under 30 minutes via a single `docker-compose up` command, covering 5+ services (Airflow, PostgreSQL, Redis, Kafka, MinIO).  
**Action**: Resolved real-world compatibility challenges including Airflow 3.x FAB auth manager deprecation and cross-platform (Windows/Mac) deployment — documented as reusable infrastructure code.  
[🔗 View Repo](https://github.com/alexandertsaidev/airflow_workspace)

---

#### ⭐ Stock Analyzer Dashboard
**Achievement**: Delivered an interactive visualization layer that surfaces stock technical signals for non-technical users without any backend server.  
**Metric**: Condensed multi-period indicator outputs (from 100+ tickers) into an explorable dashboard with instant filtering and chart rendering.  
**Action**: Connected directly to DuckDB-generated Parquet files, eliminating the need for a separate database layer and keeping the stack lightweight and self-contained.  
[🔗 View Repo](https://github.com/alexandertsaidev/stock_analyzer_dashboard)

---

### 🧰 Tech Stack

```
Languages      Python · SQL
Pipeline       Apache Airflow · Kafka · flink · Docker 
Storage        DuckDB · Parquet · MinIO · PostgreSQL
Visualization  (Dashboard project)
```

---

### 📬 Connect with Me

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=flat&logo=gmail&logoColor=white)](mailto:caiyuexun.hcd520201@hotmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)]([https://linkedin.com/in/YOUR_LINKEDIN](https://linkedin.com/in/alexander-tsai-tw-eu))
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/alexandertsaidev)



<!--
**alexandertsaidev/alexandertsaidev** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:


- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
