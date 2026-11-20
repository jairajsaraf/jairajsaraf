# Hey, I'm Jairaj 👋

**MS in Management Information Systems @ Texas A&M University (May 2026)**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/jairajsaraf/)
[![Email](https://img.shields.io/badge/Email-EA4335?logo=gmail&logoColor=white)](mailto:jairaj.saraf01@gmail.com)
[![AWS Certified Solutions Architect – Associate](https://img.shields.io/badge/AWS_Certified-Solutions_Architect_Associate-FF9900?logo=amazonwebservices&logoColor=white)](https://www.credly.com/badges/c726335c-0a03-4a30-9b7a-b51b017d486c/public_url)

I build data pipelines, search systems, ML models, and LLM-powered applications — and I care about making them production-grade, not just notebook-grade.

In my previous role as a **Data Analytics Engineer (Research Assistant)** at a university research center, I worked on entity resolution across 18M+ property records using vector search (FAISS + sentence embeddings), built automated ETL workflows in FME, and refactored legacy SQL into performant set-based operations.

Before that, I worked as a **Software Development Engineer at Hitachi Vantara**, where I owned ETL pipelines (1TB/day) across Oracle/Snowflake/AWS using Pentaho PDI, integrated Kafka ingestion at 35K events/sec, and contributed 20+ merged PRs across 5 open-source Pentaho repositories.

---

### What I Work With

|  |  |
| --- | --- |
| **Languages** | Python, Java, SQL, Bash |
| **Data Engineering** | Databricks, PySpark, SSIS, dbt, Airflow, Kafka, Apache Iceberg |
| **Cloud & Infra** | AWS (S3, Redshift, Glue, EC2), Snowflake, Docker, Jenkins CI/CD, GitHub Actions |
| **LLM & AI** | Claude, GPT-4, Gemini, FastAPI, OpenAPI tool-calling agents, prompt engineering |
| **ML & Search** | scikit-learn, TensorFlow, FAISS, Sentence Transformers, BM25, XGBoost, SHAP |
| **BI & Analytics** | Power BI (DAX, RLS), Tableau, SSRS, Advanced Excel |
| **Databases** | Oracle, SQL Server, Snowflake, Redshift, DuckDB, MongoDB, MariaDB |

**Certifications:** AWS Certified Solutions Architect – Associate · DataCamp Certified Data Engineer · Databricks Fundamentals · Professional Scrum Product Owner I (PSPO-I)

---

### Featured Projects

⚙️ **[Real-Time Agentic Data Platform](https://github.com/jairajsaraf/realtime-agentic-data-platform)**
Catalog-backed Apache Iceberg lakehouse (pyiceberg + DuckDB over S3 / LocalStack) with schema and partition evolution, snapshot time-travel, and Pandera data-quality gates over scheduled micro-batch ingestion. A read-only FastAPI serving layer exposes the lakehouse, and a human-in-the-loop NL agent answers data questions by calling that API as OpenAPI-derived tools — with bounded turn/tool budgets and snapshot-cited provenance. Deterministic CI via a `FakeLLMClient`, with GitHub Actions and coverage reporting.
`Apache Iceberg · pyiceberg · DuckDB · FastAPI · Pandera · Docker · GitHub Actions`

🔍 **[Hybrid Product Search Ranker](https://github.com/jairajsaraf/heb-product-search)**
Product search built for the TAMU-25 H-E-B Datathon: a linear hybrid of BM25 and `all-MiniLM-L6-v2` embedding similarity over 3,287 products, served by FastAPI with a React frontend in one Docker container on Cloud Run. On 58 locked queries scored once, the official composite rose from 0.6273 (BM25 alone) to 0.6998, 95% CI on the gain [+0.0404, +0.1068]. RRF fusion and cross-encoder reranking were tested and not kept.
`Python · Sentence Transformers · BM25 · FastAPI · React · Docker · Cloud Run`

💬 **[PropTalk — Conversational Analytics](https://github.com/jairajsaraf/proptalk)**
Ask questions about property data in plain English. An LLM writes SQL or pandas code, and a SELECT-only guard with a table allowlist checks it before it runs. The demo runs on synthetic data.
`Python · Streamlit · SQLite · pandas · Plotly · Gemini (OpenAI-compatible API)`

🚰 **[Rentals Data Pipeline](https://github.com/jairajsaraf/rentals-data-pipeline)**
Production-style PySpark ETL pipeline processing Zillow ZORI rental data. Window functions for MoM rent change and state-level ranking, configurable data quality framework (warn/fail severity), partitioned Parquet output by geography and year. Orchestrated with Airflow TaskFlow DAG, dbt models over DuckDB for staging and mart layers, tested with pytest, CI via parallel GitHub Actions (lint + test).
`PySpark · Airflow · dbt · DuckDB · AWS S3 · pytest · GitHub Actions`

---

### Open Source

Contributed to the **Pentaho** ecosystem during my time at Hitachi Vantara — 20+ merged PRs across 5 repositories focused on plugin stability, chart-type features, and accessibility improvements (keyboard navigation, focus management) in the Analyzer web UI.

---

### Let's Connect

📧 [jairaj.saraf01@gmail.com](mailto:jairaj.saraf01@gmail.com) · 💼 [LinkedIn](https://linkedin.com/in/jairajsaraf/) · 🐙 [GitHub](https://github.com/jairajsaraf)
