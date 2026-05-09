<h1 align="center">Antoine Gélin</h1>

<p align="center">
  Data Engineer · Modern Data Stack · Python · dbt · Spark · AWS · GCP
</p>

<p align="center">
  <a href="https://antoinegelin.alt144.net/">Website</a> ·
  <a href="https://www.linkedin.com/in/antoinegelin/">LinkedIn</a> ·
  <a href="mailto:antoineg@alt144.net">Email</a>
</p>

<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img alt="dbt" src="https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white">
  <img alt="Apache Spark" src="https://img.shields.io/badge/Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white">
  <img alt="AWS" src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white">
  <img alt="Google Cloud" src="https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white">
  <img alt="Terraform" src="https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white">
</p>

---

I build data platforms that are easier to trust, operate, and extend.

My background is in Java/Spark production systems on high-volume banking platforms. I now focus on Modern Data Stack architectures: Python ingestion, raw storage, dbt transformations, cloud warehouses, BI layers, data quality, orchestration, and clean handover to data teams.

## What I Like To Solve

| Problem | What I bring |
| --- | --- |
| Fragile Python or SQL ETL | Modular ELT design with clear responsibilities |
| Slow or risky batch pipelines | Incremental strategies, raw replay, validation, monitoring |
| Business logic spread everywhere | dbt layers, tests, documentation, governed marts |
| BI blocked by data debt | Analytics-ready models and self-service foundations |
| Cloud migration or platform rebuild | Practical architecture, delivery focus, team handover |

## Featured Build

### [velib-data-platform](https://github.com/gelinant/velib-data-platform)

Serverless ELT platform on Google Cloud for Velib Metropole open data.

It captures the state of the bike network every 5 minutes, stores raw JSON in GCS, loads BigQuery, transforms with dbt, and exposes analytics-ready tables for a Streamlit dashboard.

| Area | Stack |
| --- | --- |
| Ingestion | Python 3.12, Cloud Run Jobs, Cloud Scheduler, Cloud Workflows |
| Storage & warehouse | Google Cloud Storage, BigQuery |
| Transformation | dbt-core, dbt-bigquery, incremental models |
| Infrastructure | Terraform, Docker, IAM least privilege |
| Quality | pytest, ruff, SQLFluff, CI/CD |

The goal is to show a complete data platform, not just a pipeline: reproducible infrastructure, raw replay, layered modeling, tests, documentation, and cost-conscious serverless execution.

## Experience Snapshot

| Context | Highlights |
| --- | --- |
| Fintech scale-up | Rebuilt a data platform in 3 months with Python, S3, Redshift Serverless, dbt, AWS Fargate, QuickSight, RBAC, and GDPR masking policies. Reduced a nightly pipeline from 3-4h to less than 1h. |
| Banking platform | Built and maintained Java/Spark distributed pipelines on production systems with Hive, SQL Server, Jenkins, and 24/7 operational constraints. |
| Banking group | Worked on Java, Spark, IBM ODM, business rules, distributed processing, TDD, and Agile delivery. |

## Toolbox

| Data | Cloud | Engineering |
| --- | --- | --- |
| Python | AWS S3 | Terraform |
| SQL | Redshift Serverless | Docker |
| dbt | AWS Fargate | GitHub Actions |
| Spark | QuickSight | Forgejo Actions |
| Hadoop / Hive | BigQuery | Jenkins |
| Data quality | GCS | pytest / ruff / SQLFluff |

## How I Work

- I prefer simple, explicit data flows over clever pipelines that nobody wants to touch.
- I separate ingestion, raw storage, transformations, marts, and BI responsibilities.
- I care about tests, documentation, naming, and operational clarity because data platforms live longer than their first delivery.
- I like working close to analysts, business teams, DevOps, infrastructure, and security.

## Contact

Open to Data Engineering roles or freelance missions around platform modernization, ELT architecture, dbt, cloud warehouses, and reliable analytics foundations.

<p align="center">
  <a href="mailto:antoineg@alt144.net">antoineg@alt144.net</a> ·
  <a href="https://antoinegelin.alt144.net/">antoinegelin.alt144.net</a> ·
  <a href="https://github.com/gelinant">github.com/gelinant</a>
</p>
