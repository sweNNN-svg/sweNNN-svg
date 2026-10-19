# Emre Hacımustafaoğlu

Infrastructure and systems engineer in Trabzon, Turkey.

I work on the operational side of systems: keeping them running, making their behaviour measurable, and removing manual work around them. My background is in data engineering, and I bring that to operations: collect the signal, check it, store it, and act on evidence rather than on assumptions.

## Now

- **Corporate Infrastructure and Systems Specialist** at Turkcell Global Bilgi (since June 2026). I run endpoint management across several sites in a regulated sector: staged patch rollouts, health checks, root-cause analysis, and the documentation that keeps all of it repeatable.
- Building a daily health and early-warning pipeline for that environment: a read-only collector on each site, validated output (manifest and hashes), a time-series store, and a dashboard that flags problems before someone has to report them.
- Studying site reliability engineering (SLOs, toil, incident reviews) and how the same ideas apply to systems built on LLMs.

## How I work

- Measure first. A guess is labelled as a guess until there is evidence.
- Every change has a check before, a check after, and a written way back.
- One step at a time on production systems. No step depends on output I have not seen.
- Write it down: runbooks, handover notes, and short decision records with the context and the trade-offs.
- Collect only the data the task needs. Personal data stays out unless there is a clear reason and a clear owner.
- Keep it simple. A new component is added when a real requirement needs it, not before.

## Experience

**Turkcell Global Bilgi**, Corporate Infrastructure and Systems Specialist, 2026 to present
Endpoint management and patching across multiple sites; measured rollout planning; incident and root-cause analysis; health monitoring.

**Freelance**, Data and AI Engineering (Upwork)
Data pipelines and LLM integrations for clients.

**Atos**, System Administrator, 2024 to 2025
Monitored 250+ SAP BW/4HANA process chains daily, handled incidents and root-cause analysis under SLAs, and built a ticket classification tool on my own initiative.

## Projects

### [Turkish RAG with Evaluation](https://github.com/sweNNN-svg/turkish-rag-eval)
RAG pipeline for Turkish corporate documents where every answer is scored, not assumed.
- PDF/DOCX → chunking → Qdrant → LangChain → Claude → RAGAS → PostgreSQL → Grafana
- Faithfulness and answer relevancy are stored for each query, so quality can be followed over time and compared across model or chunking changes.
- Fixed and semantic chunking compared on the same documents: semantic chunking scored higher on faithfulness (0.42 vs 0.33) at about 2.5 times the latency. The numbers are modest; the point was to measure the trade-off.

### [SAP Ticket Router](https://github.com/sweNNN-svg/sap-ticket-router)
Three-layer ticket classifier: rule engine → TF-IDF → LLM fallback.
Known cases are resolved by rules at no API cost, familiar patterns by TF-IDF offline, and only ambiguous tickets reach the LLM. Based on what I saw while operating SAP BW/4HANA in production.

### [On-Premise LLM Gateway](https://github.com/sweNNN-svg/secure-llm-gateway-onprem)
Local LLM gateway with a masking layer that removes personal data (such as ID and card numbers) before a prompt leaves the network. Runs in Docker; designed with KVKK and GDPR constraints in mind.

### [Event Tracking and Analytics Platform](https://github.com/sweNNN-svg/data-ingestion-analytics-platform)
FastAPI ingestion → PostgreSQL (raw and analytics layers) → Python ETL worker → Next.js dashboard, on Docker Compose.
- Ingestion is decoupled from processing.
- Idempotent ETL (delete then insert per time window), safe to re-run after a failure.
- Service startup order handled with health checks and retries.

## Tools

**Operations:** Windows Server, Microsoft Configuration Manager, PowerShell, SQL Server, IIS, Linux
**Observability:** Grafana, Zabbix, OpenTelemetry
**Data:** Python, SQL, PostgreSQL, SQLite, Apache Airflow, dbt, Snowflake, Docker, FastAPI
**LLM:** Anthropic API, LangChain, Qdrant, RAGAS, MCP

## Certifications

- Snowflake Data Engineering, Snowflake (2026)
- Apache Airflow 3 Fundamentals, Astronomer (2026)
- dbt Fundamentals, dbt Labs (2026)
- IBM Data Engineering Professional (v2), IBM (2024)
- PostgreSQL for Everybody Specialization, University of Michigan

## Education

B.Sc. Management Information Systems, Karadeniz Technical University (2023)

## Contact

[LinkedIn](https://www.linkedin.com/in/emre-hacimustafaoglu) · [Email](mailto:emre_hacimustafaoglu@outlook.com)
