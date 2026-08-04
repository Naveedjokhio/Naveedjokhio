<div align="center">

# Naveed Jokhio

**Cloud Data Engineer** — Streaming & Batch Pipelines at Scale

<p>
  <img src="https://img.shields.io/badge/Final%20Year%20SE%20Student-SMIU%20Karachi-1e293b?style=flat-square&labelColor=0f172a"/>
  <img src="https://img.shields.io/badge/Data%20Engineer-Saylani%20Mass%20IT%20Training-1e293b?style=flat-square&labelColor=0f172a"/>
  <img src="https://img.shields.io/badge/Data%20Science%20Intern-10Pearls%20Pakistan-1e293b?style=flat-square&labelColor=0f172a"/>
</p>

<p>
  <a href="https://linkedin.com/in/naveed-jokhio"><img src="https://img.shields.io/badge/LinkedIn-1e293b?style=flat-square&logo=linkedin&logoColor=white"/></a>
  <a href="https://github.com/Naveedjokhio"><img src="https://img.shields.io/badge/GitHub-1e293b?style=flat-square&logo=github&logoColor=white"/></a>
  <a href="https://naveedjokhio.netlify.app"><img src="https://img.shields.io/badge/Portfolio-1e293b?style=flat-square&logo=netlify&logoColor=white"/></a>
  <a href="mailto:naveedjokhio243@gmail.com"><img src="https://img.shields.io/badge/Email-1e293b?style=flat-square&logo=gmail&logoColor=white"/></a>
</p>

<img src="https://komarev.com/ghpvc/?username=Naveedjokhio&style=flat-square&color=1e293b&label=Profile+Views"/>

</div>

<br>

## About

I'm a final-year Software Engineering student building production-style data pipelines — real-time streaming, batch ETL, and cloud-native medallion architectures. My work centers on taking raw data through a Bronze → Silver → Gold lifecycle: ingesting it reliably, cleaning and modeling it, and turning it into analytics-ready output.

Currently working as a Data Engineer at Saylani Mass IT Training and a Data Science Intern at 10Pearls Pakistan, alongside my degree at SMIU, Karachi.

| | |
|---|---|
| **Role** | Data Engineer |
| **Education** | BS Software Engineering, SMIU, Karachi (2023 – 2027) |
| **Location** | Karachi, Pakistan |
| **Open to** | Cloud Data Engineering roles, internships & collaborations |
| **Core stack** | Python · SQL · Kafka · PySpark · dlt · dbt · Bruin · Kestra · Snowflake · BigQuery · AWS · Airflow · Docker |

---

## Technical Skills

**Languages**
`Python` `SQL`

**Streaming & Processing**
`Apache Kafka` `PySpark` `dlt`

**Cloud — GCP**
`BigQuery` `Google Cloud Storage`

**Cloud — AWS**
`Amazon S3` `AWS Lambda` `AWS Glue` `Athena`

**Data Warehousing**
`Snowflake` `SQL Server`

**Orchestration & Transformation**
`Kestra` `Apache Airflow` `dbt` `Bruin` `Docker`

**Processing & Visualization**
`Pandas` `NumPy` `Power BI`

**Core Concepts**
`Medallion Architecture` `Star Schema` `SCD Type-2` `Real-Time Streaming` `ELT/ETL` `Data Orchestration`

---

## Featured Pipelines

### Cricbuzz Real-Time Data Pipeline — Flagship Project

Full GCP-based real-time streaming pipeline delivering live cricket match data end-to-end, with a synthetic match simulator built in as a resilient fallback layer.

- **Kafka → GCS → dlt → BigQuery → dbt** medallion flow, orchestrated with **Bruin + Kestra**
- Resolved real production issues: Docker-in-Docker volume mounting, GCP ADC credential mounting inside Kestra containers, dlt pipeline state corruption, and WSL2 disk space exhaustion
- Built a synthetic match simulator as a fallback for when the live RapidAPI quota ran out, keeping the demo pipeline running end-to-end
- Presented with a 20-slide deck and verified pipeline metrics

`Apache Kafka` `dlt` `BigQuery` `dbt` `Kestra` `Docker`

---

### E-Commerce Data Pipeline — In Progress

Production-grade e-commerce data pipeline built as a flagship portfolio piece, combining streaming ingestion with a full cloud-native medallion architecture.

- **dlt + Apache Kafka + PySpark** for ingestion and transformation
- **GCS → BigQuery** as the cloud data lake and warehouse layer
- Orchestrated with **Bruin** and **Kestra**, fully containerized via **Docker Compose**
- Developed end-to-end on Windows + GCP, targeting production-style reliability and observability

`Apache Kafka` `PySpark` `GCS` `BigQuery` `Kestra` `Docker Compose`

---

### Flight Operations Analytics Pipeline

Production-grade batch pipeline ingesting live flight data from the OpenSky Network API every 30 minutes via an Airflow DAG.

- Medallion Architecture (Bronze → Silver → Gold) across 4 modular tasks
- Retry logic & idempotent task design for reliable scheduling
- Gold-layer KPIs (air traffic volume, congestion signals, country-level activity) loaded into Snowflake via UPSERT
- Fully Dockerized with `docker-compose`, visualized in Power BI

`Apache Airflow` `Python` `Snowflake` `Docker` `Power BI`

---

### End-to-End Hotel Booking Data Pipeline

Complete hotel booking data pipeline built entirely inside Snowflake using Medallion Architecture.

- **Bronze** — Raw booking ingestion
- **Silver** — SQL transformations fixing invalid emails, negative amounts & status typos
- **Gold** — Aggregation tables powering an interactive Snowsight dashboard with KPIs, trend charts & booking breakdowns

`Snowflake` `SQL` `Snowsight` `Medallion Architecture`

---

### AWS Serverless ETL Pipeline

Event-driven, serverless ETL pipeline converting raw JSON into columnar Parquet, cutting storage costs by ~40%. Schema inference automated via AWS Glue Crawlers, with modular Lambda functions and S3 partitioning.

`Amazon S3` `AWS Lambda` `AWS Glue` `Athena` `Python` `Parquet`

---

### PySpark + dbt Streaming Pipeline

Streaming-style pipeline combining PySpark transformations with dbt modeling for analytics-ready outputs.

🔗 [github.com/Naveedjokhio/Pyspark_Dbt_Project](https://github.com/Naveedjokhio/Pyspark_Dbt_Project)

`PySpark` `dbt`

---

## Experience

**Data Engineer** · Saylani Mass IT Training · *Current*
- Building streaming & batch pipelines with Kafka, PySpark, dlt, and BigQuery under the mentorship of Sir Qasim Hassan & Sir Ayan Hussain
- Working hands-on with orchestration tools (Kestra, Bruin) for production-style pipeline reliability

**Data Science Intern** · 10Pearls Pakistan · *Current*
- Applying data science and analytics skills in a professional, industry-facing environment alongside the Saylani internship

**Data Engineering Intern** · Arch Technologies · *Jan 2026 – Mar 2026* · Remote
- Built end-to-end ETL pipelines in Python (Pandas, NumPy), cutting data prep time by ~30%
- Automated data validation & quality checks, improving data accuracy by ~20%
- Standardized datasets across pipelines, improving data reliability by ~25%

---

## Education & Certifications

| Program | Institution | Years |
|---|---|---|
| BS Software Engineering | Sindh Madressatul Islam University (SMIU), Karachi | 2023 – 2027 |
| Intermediate (Pre-Engineering) | Govt. Boys Degree College, Naudero | 2019 – 2021 |

**Certifications:** Data Analytics (Deloitte) · GenAI Data Analytics (TATA) · Python (DataCamp) · Snowflake Essentials · Data Scientist (NED University)

---

## GitHub Stats

<div align="center">

<img width="48%" src="https://github-readme-stats.vercel.app/api?username=Naveedjokhio&show_icons=true&theme=default&hide_border=true&title_color=1e293b&icon_color=334155&text_color=334155&bg_color=ffffff"/>
<img width="48%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Naveedjokhio&layout=compact&theme=default&hide_border=true&title_color=1e293b&text_color=334155&bg_color=ffffff"/>

<br><br>

<img src="https://streak-stats.demolab.com?user=Naveedjokhio&theme=default&hide_border=true&background=ffffff&ring=1e293b&fire=334155&currStreakLabel=1e293b"/>

<br><br>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Naveedjokhio&theme=minimal&hide_border=true&bg_color=ffffff&color=1e293b&line=334155&point=0f172a"/>

</div>

---

<div align="center">

**Open to Data Engineering roles, internships & collaborations**

<a href="https://linkedin.com/in/naveed-jokhio"><img src="https://img.shields.io/badge/Let's_Connect-1e293b?style=flat-square&logo=linkedin&logoColor=white"/></a>
<a href="mailto:naveedjokhio243@gmail.com"><img src="https://img.shields.io/badge/Say_Hello-1e293b?style=flat-square&logo=gmail&logoColor=white"/></a>

</div>
