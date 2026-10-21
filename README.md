# Hi, I'm David Mudiwa

## About Me

I build data pipelines that turn messy APIs into clean, queryable tables.

I'm a data engineer focused on reliable batch and incremental ingestion — the kind of pipelines that survive retries, reruns and schema changes. I care about idempotency, explicit data contracts and making failures cheap to recover from.

## What I'm Building

- **Dagster ELT Platform** — an end-to-end pipeline from the GitHub REST API to BigQuery: raw JSON in GCS, Parquet in the processed layer, partitioned tables in BigQuery. The chain is orchestrated as a Dagster asset graph (`raw → parquet → bq`) with inferred lineage, daily partitions and parameterised backfills. Every stage is idempotent — deterministic GCS keys and `WRITE_TRUNCATE` partition decorators — so re-runs replace exactly one slice. Includes explicit BigQuery schemas, asset checks, and shared retry policies with exponential backoff and jitter.

## Experience Highlights
- **Junior Data Engineer at Homiee** (Australia, remote, 2025–2026)
  - Built and maintained automated ETL workflows for property listings using Python, MongoDB and Apache Airflow
  - Designed metadata driven batch and incremental ingestion for reliable, traceable, repeatable production loads
  - Implemented validation, normalization, deduplication and missing data handling across raw and transformed datasets
  - **Improved address matching from 84% to 90%**, increasing successful downstream loads
  - Supported data feeding application, analytics and machine learning workflows

## How I Like to Build Pipelines
- **Idempotent by default** — reruns and backfills should be safe
- **Metadata-driven** — configuration over hard-coded logic
- **Observable and testable** — validation, checks and clear lineage
- **Least privilege** — secure cloud access from day one

## Tech Stack

```python
languages = ["Python", "SQL"]
orchestration = ["Dagster", "Apache Airflow", "dbt Core"]
storage = ["BigQuery", "Google Cloud Storage", "PostgreSQL", "MongoDB"]
formats = ["Parquet", "JSON", "CSV"]
tools = ["Docker", "Docker Compose", "Git", "Linux/WSL"]
cloud = ["GCP", "BigQuery", "GCS", "IAM", "ADC"]
visualization = ["Tableau"]
```

## Let's Connect

- [LinkedIn](https://linkedin.com/in/david-m-a821b6183)
- [Gmail](davidmudiwa14@gmail.com)

---

*Reliable pipelines*
