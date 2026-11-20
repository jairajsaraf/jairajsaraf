# Hey, I'm Jairaj 👋

**MS in Management Information Systems @ Texas A&M University (May 2026)**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/jairajsaraf/)
[![Email](https://img.shields.io/badge/Email-EA4335?logo=gmail&logoColor=white)](mailto:jairaj.saraf01@gmail.com)
[![AWS Certified Solutions Architect – Associate](https://img.shields.io/badge/AWS_Certified-Solutions_Architect_Associate-FF9900?logo=amazonwebservices&logoColor=white)](https://www.credly.com/badges/c726335c-0a03-4a30-9b7a-b51b017d486c/public_url)

I build data pipelines, search systems, ML models, and apps on top of LLMs. The part I care about is getting them out of the notebook and into something production-grade.

Most recently I was a **Data Analytics Engineer (Research Assistant)** at a university research center. I did entity resolution across 18M+ property records with vector search (FAISS + sentence embeddings), built automated ETL workflows in FME, and rewrote legacy SQL as faster set-based queries.

Before that I was a **Software Development Engineer at Hitachi Vantara**. I owned ETL pipelines moving 1TB/day across Oracle, Snowflake and AWS with Pentaho PDI, hooked up Kafka ingestion at 35K events/sec, and got 20+ PRs merged across 5 open-source Pentaho repos.

---

### What I work with

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

### Projects

The first three have live demos you can click around in.

⚙️ **[Real-Time Agentic Data Platform](https://github.com/jairajsaraf/realtime-agentic-data-platform)** · [demo](https://jairajsaraf-rtdp-demo.hf.space/)
A catalog-backed Apache Iceberg lakehouse (pyiceberg + DuckDB over S3 or LocalStack) with schema and partition evolution, snapshot time travel, and Pandera data-quality gates on scheduled micro-batch ingestion. A read-only FastAPI layer serves it. On top of that, a human-in-the-loop agent answers data questions by calling the API as OpenAPI-derived tools; it has caps on turns and tool calls, and its answers cite the snapshot they came from. CI on GitHub Actions runs the agent against a scripted fake LLM, so the tests are deterministic, and it reports coverage.
`Apache Iceberg · pyiceberg · DuckDB · FastAPI · Pandera · Docker · GitHub Actions`

🔍 **[Hybrid Product Search Ranker](https://github.com/jairajsaraf/heb-product-search)** · [demo](https://heb-search-246501698420.us-central1.run.app/)
Product search built for the TAMU-25 H-E-B Datathon. It blends BM25 keyword scores with `all-MiniLM-L6-v2` embedding similarity over 3,287 products, and FastAPI serves it with a React frontend, all in one Docker container on Cloud Run. On 58 locked queries scored once, the official composite went from 0.6273 (BM25 alone) to 0.6998, with a 95% CI on the gain of [+0.0404, +0.1068]. RRF fusion and cross-encoder reranking were tested too; neither passed the keep rule, so neither ships.
`Python · Sentence Transformers · BM25 · FastAPI · React · Docker · Cloud Run`

💬 **[PropTalk: Conversational Analytics](https://github.com/jairajsaraf/proptalk)** · [demo](https://proptalk.streamlit.app/)
Ask questions about property data in plain English. An LLM writes SQL or pandas code, and a SELECT-only guard with a table allowlist checks it before anything runs. The demo's data is all synthetic.
`Python · Streamlit · SQLite · pandas · Plotly · Gemini (OpenAI-compatible API)`

🚰 **[Rentals Data Pipeline](https://github.com/jairajsaraf/rentals-data-pipeline)**
A production-style PySpark ETL pipeline over Zillow ZORI rental data. Window functions work out month-over-month rent change and state-level rankings, a configurable data-quality layer marks each check as warn or fail, and the output lands as Parquet partitioned by geography and year. Airflow (TaskFlow DAG) runs it, dbt models over DuckDB build the staging and mart layers, and GitHub Actions runs lint and pytest in parallel. There's no live demo for this one.
`PySpark · Airflow · dbt · DuckDB · AWS S3 · pytest · GitHub Actions`

---

### Open source

At Hitachi Vantara I got 20+ PRs merged across 5 **Pentaho** repos. They covered plugin stability, chart-type features, and accessibility work in the Analyzer web UI (keyboard navigation, focus management).

---

### Get in touch

📧 [jairaj.saraf01@gmail.com](mailto:jairaj.saraf01@gmail.com) · 💼 [LinkedIn](https://linkedin.com/in/jairajsaraf/) · 🐙 [GitHub](https://github.com/jairajsaraf)
