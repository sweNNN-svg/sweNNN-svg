# Hi, I'm Emre 👋

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=sweNNN-svg&label=Profile%20Views&color=blue&style=flat" alt="profile views" />
</p>

## About Me

I'm a **Data & AI Engineer** based in Trabzon, Turkey. I build production-grade LLM systems, RAG pipelines, and data infrastructure — with a focus on observability, security, and systems that are defensible at every layer.

- 🔭 **Current Focus:** LLM integration, RAG pipelines, on-premise AI infrastructure with DLP layers
- 🛠️ **Core Stack:** Python, FastAPI, Apache Airflow, dbt, Snowflake, PostgreSQL, Docker
- 🤖 **AI/LLM:** Anthropic API, LangChain, Qdrant, sentence-transformers, RAG, prompt engineering
- 📊 **Observability:** Grafana, Zabbix, OpenTelemetry — applied to both data pipelines and LLM systems
- 🎓 **Education:** M.Sc. Entrepreneurship & Innovation Management, Karadeniz Technical University *(ongoing)*

---

## Featured Projects

### [SAP Ticket Router](https://github.com/sweNNN-svg/sap-ticket-router)
*Hybrid classification system: Rule Engine → TF-IDF → LLM fallback*

- Three-layer architecture: rule engine handles known TCODEs at 100% confidence with zero API cost, TF-IDF covers familiar patterns offline, LLM fallback handles only ambiguous tickets
- Prompt engineered for deterministic JSON output with `temperature=0.1`
- Built from real experience managing 250+ SAP BW/4HANA process chains at enterprise scale

### [Secure On-Premise LLM Gateway](https://github.com/sweNNN-svg/secure-llm-gateway-onprem)
*100% on-premise LLM usage with DLP layer*

- Intercepts and masks sensitive data (PII, credit card info) before it leaves the local network
- KVKK/GDPR compliant, runs in isolated Docker environments
- Designed for enterprises that need LLM capabilities without cloud data exposure

### [LLM RAG Pipeline](https://github.com/sweNNN-svg/llm-rag-demo)
*Production-grade retrieval-augmented generation*

- `RecursiveCharacterTextSplitter` with chunk_size=500, overlap=50 — tuned for document structure
- Qdrant vector store (self-hosted, persistent-ready) with cosine similarity, top_k=3
- System/user prompt separation: role definition in system, query in user
- `temperature=0.1` for consistent, grounded responses

### [Event Tracking & Analytics Platform](https://github.com/sweNNN-svg/E-Ticaret_Veri_Ambari_Projesi)
*End-to-end telemetry platform — 1M+ events/day*

- High-throughput ingestion API with FastAPI → PostgreSQL
- Airflow-based ETL with dbt quality checks, retry logic, dependency management
- Full observability via Grafana dashboards

---

## Tech Stack

**AI / LLM**
![Anthropic](https://img.shields.io/badge/Anthropic_API-191919?style=for-the-badge&logo=anthropic&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

**Data Engineering**
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apache-airflow&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

**Infrastructure & Observability**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=for-the-badge&logo=opentelemetry&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

## Certifications

- 📜 Snowflake Data Engineering — Snowflake *(2026)*
- 📜 Apache Airflow 3 Fundamentals — Astronomer *(2026)*
- 📜 dbt Fundamentals — dbt Labs *(2026)*
- 📜 IBM Data Engineering Professional (v2) — IBM *(2024)*
- 📜 PostgreSQL for Everybody Specialization — University of Michigan

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/emre-hacimustafaoglu)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:emre_hacimustafaoglu@outlook.com)
