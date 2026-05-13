# Hey, I'm Jairaj 👋

**MS in Management Information Systems @ Texas A&M University (May 2026)**

I build data pipelines, search systems, and ML models — and I care about making them production-grade, not just notebook-grade.

Currently a **Graduate Research Assistant** at the [Texas Real Estate Research Center](https://www.recenter.tamu.edu/), where I work on entity resolution across 18M+ property records using vector search (FAISS + sentence embeddings), build automated ETL workflows in FME, and refactor legacy SQL into performant set-based operations.

Previously a **Software Development Engineer at Hitachi Vantara**, where I owned ETL pipelines (1TB/day) across Oracle/Snowflake/AWS using Pentaho PDI, integrated Kafka ingestion at 35K events/sec, and contributed 40 merged PRs across 5 open-source Pentaho repositories.

---

### What I Work With

|  |  |
| --- | --- |
| **Languages** | Python, Java, SQL, Bash |
| **Data Engineering** | PySpark, Pentaho PDI, FME, SSIS, dbt, Airflow, Kafka |
| **Cloud & Infra** | AWS (S3, Redshift, Glue, EC2), Snowflake, Docker, Jenkins CI/CD, GitHub Actions |
| **ML & Search** | scikit-learn, TensorFlow, FAISS, Sentence Transformers, BM25, XGBoost, SHAP |
| **BI & Analytics** | Power BI (DAX, RLS), Tableau, SSRS, Advanced Excel |
| **Databases** | Oracle, SQL Server, Snowflake, Redshift, DuckDB, MongoDB, MariaDB |

**Certifications:** AWS Certified Solutions Architect – Associate

---

### Featured Projects

🚰 **[Rentals Data Pipeline](https://github.com/jairajsaraf/rentals-data-pipeline)**
Production-style PySpark ETL pipeline processing Zillow ZORI rental data. Window functions for MoM rent change and state-level ranking, configurable data quality framework (warn/fail severity), partitioned Parquet output by geography and year. Orchestrated with Airflow TaskFlow DAG, dbt models over DuckDB for staging and mart layers, tested with pytest, CI via parallel GitHub Actions (lint + test).
`PySpark · Airflow · dbt · DuckDB · AWS S3 · pytest · GitHub Actions`

💬 **[PropTalk — Conversational Analytics](https://github.com/jairajsaraf/proptalk)**
Natural language to SQL interface over a CoreLogic/MLS SQL Server DataMart. Multi-model backend (Claude Sonnet, GPT-4.1, Gemini 2.5 Flash) with SELECT-only query enforcement and table whitelisting for safe, ad-hoc analytics. Built with Streamlit and pyodbc; production-deployed at TRERC.
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

Contributed to the **Pentaho** ecosystem during my time at Hitachi Vantara — 40 merged PRs across 5 repositories focused on plugin stability, chart type features, and WCAG compliance across the Analyzer platform.

---

### Let's Connect

📧 [jairaj.saraf@tamu.edu](mailto:jairaj.saraf@tamu.edu) · 💼 [LinkedIn](https://linkedin.com/in/jairajsaraf/) · 🐙 [GitHub](https://github.com/jairajsaraf)
