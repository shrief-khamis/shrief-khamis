# Shrief Khamis
 
Backend and data engineer in Cairo, working CET hours. I build data-heavy systems in Python: pipelines, APIs, and the AWS infrastructure they run on.
 
## Current work
 
**[DataStandIn](https://www.datastandin.com)** is a synthetic data platform that I designed, built, and operate as the sole engineer. It generates relational datasets from SQL DDL or templates and exports CSV, JSONL, or Parquet to downloads or S3/GCS. It launched in October 2026.
 
- **Engine:** keeps foreign-key integrity by deriving keys deterministically instead of storing or re-reading them, so large key sets never sit in memory or on disk. Generated 1B rows in about 2 hours on 2 vCPU and 15 GB of RAM.
- **Platform:** benchmark-calibrated workload estimation routes jobs to an autoscaling pool of small instances or to ECS Fargate tasks sized per job.
- **Operations:** Terraform for infrastructure, GitHub Actions CI/CD for staging and production, Grafana for logs, traces, and metrics, Stripe for credit billing.
- **Stack:** Python, FastAPI, Celery, Angular, PostgreSQL, Redis, AWS.
The source is private. The product and its docs are public at [datastandin.com](https://www.datastandin.com).
 
## Background
 
I worked at DataBees from 2022 to 2026. I started as a Data Quality Analyst and moved into engineering in Feb 2025, after proposing and building internal automation that became core infrastructure. Main projects there:
 
- A data collection pipeline: browser extension, FastAPI service on EC2, PostgreSQL on RDS, about 5K records per day.
- Browser extensions that extract structured data from platforms without public APIs.
- An analysis of about 600K spreadsheet column headers that informed schema standardisation.
On the side, I am building a research crawler that uses retrieval-augmented generation (RAG) to return answers with exact-quote evidence and page locations.
 
I am also studying for a BSc in Computer Science at the University of London (Goldsmiths), part-time, expected 2028.
 
## Stack
 
- **Languages:** Python, TypeScript, JavaScript, SQL, Shell
- **Backend:** FastAPI, Django, Celery, PostgreSQL, Redis, SQLAlchemy, DuckDB
- **Frontend:** Angular, Chrome extensions (Manifest V3)
- **Cloud and CI/CD:** AWS (EC2, ECS Fargate, RDS, ElastiCache, S3, Lambda), Terraform, Docker, GitHub Actions, Grafana
- **Data:** ETL pipelines, Pandas, Parquet, Power BI
## Links
 
- Website: [shrief-khamis.com](https://shrief-khamis.com)
- LinkedIn: [shrief-khamis](https://www.linkedin.com/in/shrief-khamis/)
- Email: [shriefkhamis@gmail.com](mailto:shriefkhamis@gmail.com)
