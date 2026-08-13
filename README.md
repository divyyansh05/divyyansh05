<div align="center">

# Divyansh Shrivastava

### AI Engineer | Senior Data Engineer

*Madrid, Spain · MSc Completed · Available Now*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-divyyansh05-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com/in/divyyansh05)
[![Portfolio](https://img.shields.io/badge/Portfolio-divyyansh05.github.io-C8A96E?style=flat-square)](https://divyyansh05.github.io)
[![Email](https://img.shields.io/badge/Email-divyyansh99@gmail.com-EA4335?style=flat-square&logo=gmail)](mailto:divyyansh99@gmail.com)

</div>

---

## About

At Real Madrid, I worked as the sole AI Engineer — identified the business problem, designed the architecture, and shipped **ClubOS**: a multi-agent agentic AI platform deployed on GCP Cloud Run, used by senior club stakeholders for monthly commercial decision-making.

Before that, 5 years in production data engineering. Tech Lead at **Deloitte** — architected AWS data lakehouses, shipped the team's first RAG system via Amazon Bedrock. At **Honeywell** — engineered high-volume pipelines processing 1,000+ source streams.

I don't reach for an LLM when a SQL query or a Python function gives you a deterministic answer. The AI layer sits on top of governed data infrastructure — not instead of it.

**MSc Sports Analytics** — Universidad Europea de Madrid (Real Madrid Graduate School), completed July 2026.

---

## What I Built

### ClubOS — Agentic AI Platform
*AI Engineer · Real Madrid · 2026*

Multi-agent agentic AI platform processing 59 business metrics across 5 digital platforms, benchmarking against 5 elite European clubs, delivering ranked priorities with predictive signals to club leadership. Deployed on GCP Cloud Run.

```
59 metrics  ·  22 validated signals (r ≥ 0.60)  ·  103 months history  ·  604 automated tests
```

Four LangGraph-orchestrated agents:
- **Scout** — three-tier hybrid retrieval: metric registry SQL → BM25 skill files → ChromaDB vector search
- **Watchdog** — pure Python anomaly detection, auto-triggers Investigator on CRITICAL alerts
- **Investigator** — ReAct agent with 6 tools + MCP web search, cited multi-step reasoning
- **Briefer** — monthly executive briefing generation from investigations + alerts + memory

No-fabricated-numbers guardrail: every AI-generated claim traces to a source-tagged tool result. Ungrounded numbers are rejected before reaching stakeholders.

**Stack:** Python · LangGraph · ChromaDB · OpenAI API · Databricks · Delta Lake · FastAPI · React · TypeScript · dbt · Pydantic v2 · GCP Cloud Run · Docker · GitHub Actions

→ [github.com/divyyansh05/ClubOS](https://github.com/divyyansh05/ClubOS)

---

### ScoutIQ — Football Scouting Intelligence Platform
*MSc Final Project · 2026*

Production-grade football scouting platform covering 15,000+ players across Europe's top 5 leagues. Role-based scoring engine across 13 positional profiles, player similarity engine, and AI Scout Assistant powered by the Anthropic API.

```
15,000+ players  ·  13 role profiles  ·  5 leagues  ·  20+ per-90 metrics
```

**Stack:** FastAPI · PostgreSQL · DuckDB · Anthropic API · React/Vite · Airflow · Docker · dbt · CI/CD

→ [github.com/divyyansh05/scoutiq](https://github.com/divyyansh05/scoutiq)

---

### Urban Pulse Platform — Multi-Cloud Data Lakehouse
*Portfolio Project · 2024*

Production-grade multi-cloud lakehouse ingesting NYC 311, NYPD crime, TfL London transit, AirNow EPA, and Open-Meteo data. Full dbt transformation layer with automated data quality testing.

```
5 APIs  ·  33+ unit tests  ·  4 Airflow DAGs  ·  GCP + AWS + Databricks
```

**Stack:** GCP (BigQuery, Pub/Sub, Dataflow) · AWS (S3) · Databricks · dbt · Airflow · Python · Docker · Terraform

→ [github.com/divyyansh05/urban-pulse-platform](https://github.com/divyyansh05/urban-pulse-platform)

---

## Tech Stack

**AI & Agentic Engineering**
```
LangGraph · Multi-Agent Systems · RAG Pipelines · ChromaDB · OpenAI API · Anthropic API
Prompt Engineering · Guardrails · LangSmith · RAGAS · Vector Databases · MCP
```

**Data Engineering**
```
Python · SQL · PySpark · Databricks · Delta Lake · Apache Iceberg
dbt · Apache Airflow · Kafka · CDC (Debezium) · Medallion Architecture
```

**Cloud & Infrastructure**
```
AWS (S3, Glue, EMR, Lake Formation, Bedrock, SageMaker)
GCP (BigQuery, Dataflow, Cloud Run, Pub/Sub)
Docker · Terraform · GitHub Actions · CI/CD
```

**Backend & Frontend**
```
FastAPI · PostgreSQL · DuckDB · Pydantic v2
React · TypeScript · Streamlit
```

---

## Experience

| Period | Role | Company |
|--------|------|---------|
| Mar 2026 – Jul 2026 | AI Engineer | Real Madrid C.F. |
| Jun 2021 – Oct 2024 | Senior Data Engineer (Tech Lead) | HashedIn by Deloitte |
| Oct 2019 – May 2021 | Big Data Engineer | Honeywell Technology Solutions |

---

## Education

| Period | Degree | Institution |
|--------|--------|-------------|
| 2025 – 2026 | MSc Sports Analytics (Completed) | Universidad Europea de Madrid (Real Madrid Graduate School) |
| 2019 | PG Diploma, Big Data & Analytics | IACSD, Pune |
| 2014 – 2018 | B.E. Mechanical Engineering | ITM Universe, Gwalior |

---

## Open To

```
AI Engineer · Forward Deployed Engineer · Applied AI · Senior Data Engineer
```

Open to EU, UK, and remote opportunities.

---

<div align="center">

**[Portfolio](https://divyyansh05.github.io) · [LinkedIn](https://linkedin.com/in/divyyansh05) · [Email](mailto:divyyansh99@gmail.com)**

</div>
