# Hey, I'm Jairaj 👋

**MS in Management Information Systems @ Texas A&M University (May 2026)**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/jairajsaraf/)
[![Email](https://img.shields.io/badge/Email-EA4335?logo=gmail&logoColor=white)](mailto:jairaj.saraf01@gmail.com)
[![AWS Certified Solutions Architect – Associate](https://img.shields.io/badge/AWS_Certified-Solutions_Architect_Associate-FF9900?logo=amazonwebservices&logoColor=white)](https://www.credly.com/badges/c726335c-0a03-4a30-9b7a-b51b017d486c/public_url)

I build data pipelines, search systems, ML models, and LLM-powered applications — and I care about making them production-grade, not just notebook-grade.

In my previous role as a **Data Analytics Engineer (Research Assistant)** at the [Texas Real Estate Research Center](https://www.recenter.tamu.edu/), I worked on entity resolution across 18M+ property records using vector search (FAISS + sentence embeddings), built automated ETL workflows in FME, and refactored legacy SQL into performant set-based operations.

Before that, I worked as a **Software Development Engineer at Hitachi Vantara**, where I owned ETL pipelines (1TB/day) across Oracle/Snowflake/AWS using Pentaho PDI, integrated Kafka ingestion at 35K events/sec, and contributed 20+ merged PRs across 5 open-source Pentaho repositories.

---

### What I Work With

|  |  |
| --- | --- |
| **Languages** | Python, Java, SQL, Bash |
| **Data Engineering** | PySpark, Pentaho PDI, FME, SSIS, dbt, Airflow, Kafka, Apache Iceberg |
| **Cloud & Infra** | AWS (S3, Redshift, Glue, EC2), Snowflake, Docker, Jenkins CI/CD, GitHub Actions |
| **LLM & AI** | Claude, GPT-4, Gemini, FastAPI, OpenAPI tool-calling agents, prompt engineering |
| **ML & Search** | scikit-learn, TensorFlow, FAISS, Sentence Transformers, BM25, XGBoost, SHAP |
| **BI & Analytics** | Power BI (DAX, RLS), Tableau, SSRS, Advanced Excel |
| **Databases** | Oracle, SQL Server, Snowflake, Redshift, DuckDB, MongoDB, MariaDB |

**Certifications:** AWS Certified Solutions Architect – Associate · DataCamp Certified Data Engineer · Professional Scrum Product Owner I (PSPO-I)

---

### Featured Projects

⚙️ **[Real-Time Agentic Data Platform](https://github.com/jairajsaraf/realtime-agentic-data-platform)**
Catalog-backed Apache Iceberg lakehouse (pyiceberg + DuckDB over S3 / LocalStack) with schema and partition evolution, snapshot time-travel, and Pandera data-quality gates over scheduled micro-batch ingestion. A read-only FastAPI serving layer exposes the lakehouse, and a human-in-the-loop NL agent answers data questions by calling that API as OpenAPI-derived tools — with bounded turn/tool budgets and snapshot-cited provenance. Deterministic CI via a `FakeLLMClient`, with GitHub Actions and coverage reporting.
`Apache Iceberg · pyiceberg · DuckDB · FastAPI · Pandera · Docker · GitHub Actions`

🚰 **[Rentals Data Pipeline](https://github.com/jairajsaraf/rentals-data-pipeline)**
Production-style PySpark ETL pipeline processing Zillow ZORI rental data. Window functions for MoM rent change and state-level ranking, configurable data quality framework (warn/fail severity), partitioned Parquet output by geography and year. Orchestrated with Airflow TaskFlow DAG, dbt models over DuckDB for staging and mart layers, tested with pytest, CI via parallel GitHub Actions (lint + test).
`PySpark · Airflow · dbt · DuckDB · AWS S3 · pytest · GitHub Actions`

💬 **[PropTalk — Conversational Analytics](https://github.com/jairajsaraf/proptalk)**
Natural language to SQL interface over a CoreLogic/MLS SQL Server DataMart. Multi-model backend (Claude Sonnet, GPT-4.1, Gemini 2.5 Flash) with SELECT-only query enforcement and table whitelisting for safe, ad-hoc analytics. Built with Streamlit and pyodbc.
`Python · Streamlit · Claude · GPT-4.1 · Gemini · SQL Server · pyodbc`

🔍 **[Hybrid Product Search Ranker](https://github.com/jairajsaraf/heb-product-search)**
Hybrid BM25 + transformer embedding ranking system for e-commerce product search. Achieved 26% relative improvement over keyword-only baseline on 3,287 products. Built with Poetry, Pytest, and Fire CLI for reproducible evaluation across 12 configurations spanning 3 transformer models.
`Python · Sentence Transformers · BM25 · Pytest · Poetry`

📄 **[Regulatory Document Classifier API](https://github.com/jairajsaraf/document_classifier_AI)**
FastAPI service classifying multi-modal documents (PDF/images) into regulatory categories using dual-LLM verification (Claude 3 Haiku + GPT-3.5). Includes PII detection with Luhn validation, Tesseract OCR integration, and audit-compliant citation generation. Reduced manual review by 65%.
`FastAPI · Claude 3 Haiku · GPT-3.5 · Tesseract OCR · SQLite`

🎵 **[FeatureBeats — Hit Song Predictor](https://github.com/jairajsaraf/FeatureBeats)**
ML pipeline predicting commercial hits from Spotify audio features. Dual-model approach (Logistic Regression + XGBoost) with SHAP explainability, SMOTE variants for class imbalance, and a Streamlit UI for real-time predictions. 0.80–0.92 ROC-AUC.
`Python · XGBoost · SHAP · Streamlit · scikit-learn`

🍽️ **[Mai Shen Yun — Inventory Analytics Dashboard](https://github.com/jairajsaraf/mai-shen-yun)**
5-module Streamlit dashboard for restaurant inventory management. Multi-method demand forecasting (Prophet, exponential smoothing, ensemble) with MAE/MAPE metrics. EOQ optimization, ABC classification, and reorder point calculations.
`Python · Prophet · Streamlit · Plotly · Altair`

---

### Open Source

Contributed to the **Pentaho** ecosystem during my time at Hitachi Vantara — 20+ merged PRs across 5 repositories focused on plugin stability, chart-type features, and accessibility improvements (keyboard navigation, focus management) in the Analyzer web UI.

---

### Let's Connect

📧 [jairaj.saraf01@gmail.com](mailto:jairaj.saraf01@gmail.com) · 💼 [LinkedIn](https://linkedin.com/in/jairajsaraf/) · 🐙 [GitHub](https://github.com/jairajsaraf)
