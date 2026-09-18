::: {align="center"}
# Hi, I'm Naveed Jokhio

### Cloud Data Engineer \| Data Engineering • Cloud • Streaming • Analytics

Building production-style data pipelines across **AWS • GCP • Microsoft
Fabric • SAP**

```{=html}
<p>
```
`<a href="https://linkedin.com/in/naveed-jokhio">`{=html}`<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>`{=html}`</a>`{=html}
`<a href="https://github.com/Naveedjokhio">`{=html}`<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>`{=html}`</a>`{=html}
`<a href="https://naveedjokhio.netlify.app">`{=html}`<img src="https://img.shields.io/badge/Portfolio-00C7B7?style=for-the-badge&logo=netlify&logoColor=white"/>`{=html}`</a>`{=html}
`<a href="mailto:naveedjokhio243@gmail.com">`{=html}`<img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>`{=html}`</a>`{=html}
```{=html}
</p>
```
`<img src="https://komarev.com/ghpvc/?username=Naveedjokhio&style=for-the-badge&color=0ea5e9&label=PROFILE+VIEWS"/>`{=html}
:::

------------------------------------------------------------------------

## About Me

I'm a **Software Engineering student and Data Engineer** focused on
building scalable **batch, streaming, ETL/ELT, and cloud data
pipelines**.

My work covers the complete data engineering lifecycle:

**Data Sources → Ingestion → Bronze → Silver → Gold → Data Warehouse →
Analytics**

I work with **AWS, GCP, Microsoft Fabric, SAP Datasphere, Snowflake,
Apache Spark, Kafka, dbt, Docker, Terraform, and modern orchestration
tools**.

-   🎓 **BS Software Engineering** --- SMIU, Karachi
-   ☁️ **Focus:** Cloud Data Engineering
-   ⚡ **Building:** Batch & Streaming Data Pipelines
-   🏗️ **Architecture:** Medallion, Lakehouse & Data Warehouse
-   📊 **Analytics:** Power BI, SAP Analytics Cloud & Streamlit
-   🚀 **Open to:** Junior / Associate Data Engineering opportunities

------------------------------------------------------------------------

## Tech Stack

### Programming & Processing

`Python` `SQL` `Apache Spark` `PySpark` `Pandas` `NumPy`

### Streaming & Ingestion

`Apache Kafka` `dlt` `REST APIs`

### AWS

`Amazon S3` `AWS Lambda` `AWS Glue` `Amazon Athena`

### GCP

`BigQuery` `Google Cloud Storage` `Cloud Run`

### Microsoft Data Platform

`Microsoft Fabric` `Power BI` `SQL Server`

### Data Warehousing & Transformation

`Snowflake` `BigQuery` `dbt`

### Orchestration & DevOps

`Apache Airflow` `Kestra` `Bruin` `Docker` `Terraform` `Git`

### SAP Data & Analytics

`SAP Datasphere` `SAP Analytics Cloud` `SAP ERP`

### Core Data Engineering

`ETL / ELT` `Medallion Architecture` `Star Schema` `SCD Type 2`
`Data Lakes` `Data Warehousing` `Batch Processing`
`Near Real-Time Streaming` `Data Quality`

------------------------------------------------------------------------

# Featured Projects

## 🏭 Hyundai Elevator --- SAP Data & Analytics Case Study

Enterprise data and analytics case study for an elevator/manufacturing
environment with fragmented operational data.

**Architecture**

``` text
SAP ERP ───────────┐
Procurement ───────┤
MES ───────────────┤
Elevator IoT ──────┼──► SAP Datasphere ──► Analytical Models ──► SAP Analytics Cloud
Maintenance ───────┤
AWS S3 ────────────┤
Python / SQL ──────┘
```

**Highlights** - Integrated data across ERP, procurement, manufacturing,
IoT, and maintenance domains - Designed relationships for customers,
elevators, locations, production, and maintenance - Built analytical
data models using SAP Datasphere - Designed business KPI and
visualization layer using SAP Analytics Cloud - Worked with large-scale
synthetic elevator sensor, alarm, and maintenance datasets

`SAP Datasphere` `SAP Analytics Cloud` `SAP ERP` `AWS S3` `Python` `SQL`

------------------------------------------------------------------------

## 🌍 AQI Predictor --- End-to-End ML & MLOps

Serverless forecasting platform designed to predict **Air Quality Index
up to 3 days ahead across six major cities in Pakistan**.

``` text
OpenWeather API
      │
      ▼
Data Ingestion
      │
      ▼
BigQuery Bronze
      │
      ▼
dbt Silver / Gold
      │
      ▼
Feature Engineering
      │
      ▼
ML Models
      │
      ├──► Cloud Run API
      └──► Streamlit Dashboard
```

**Highlights** - Automated hourly weather and pollution ingestion -
Historical data backfill - Bronze → Silver → Gold data architecture -
Separate models by city and forecast horizon - Ridge Regression, Random
Forest, and TensorFlow models - RMSE, MAE, and R² evaluation -
Serverless API and dashboard deployment on Google Cloud Run - Automated
scheduled pipeline execution

`GCP` `BigQuery` `dbt` `TensorFlow` `Python` `Cloud Run` `Streamlit`

------------------------------------------------------------------------

## 🏏 AWS Cricket Data Pipeline

Production-style data pipeline combining **batch schedules with
near-real-time cricket updates**.

``` text
Schedules API ──► Lambda ──┐
                           ├──► S3 Bronze ──► AWS Glue / PySpark ──► Silver
Live Scores ────► Lambda ──┘                                  │
                                                              ▼
                                                         dbt + Athena
                                                              │
                                                              ▼
                                                             Gold
                                                              │
                                                              ▼
                                                     Streamlit Dashboard
```

**Highlights** - Batch + near-real-time ingestion - Duplicate handling
across repeated ingestion - PySpark cleaning and deduplication - dbt
analytical modeling with Athena - Bronze, Silver, and Gold
architecture - Kestra orchestration - Terraform infrastructure -
Dockerized development workflow

`AWS` `S3` `Lambda` `Glue` `PySpark` `Athena` `dbt` `Kestra` `Terraform`
`Docker`

------------------------------------------------------------------------

## ✈️ Flight Operations Analytics Pipeline

-   Automated OpenSky Network API ingestion every 30 minutes
-   Bronze → Silver → Gold architecture
-   Apache Airflow DAG orchestration
-   Retry logic and idempotent task design
-   Snowflake Gold layer
-   Aviation KPIs and Power BI visualization

`Airflow` `Python` `Snowflake` `Docker` `Power BI`

------------------------------------------------------------------------

## 🏨 Hotel Booking Data Pipeline

End-to-end analytical pipeline implemented inside Snowflake.

-   Raw booking ingestion into Bronze
-   Data-quality transformations in Silver
-   Business aggregations in Gold
-   Cleaned invalid emails, negative amounts, and inconsistent statuses
-   Interactive analytics through Snowsight

`Snowflake` `SQL` `Medallion Architecture` `Snowsight`

------------------------------------------------------------------------

## ⚡ AWS Serverless ETL Pipeline

``` text
Raw JSON ──► Amazon S3 ──► AWS Lambda ──► Parquet ──► Glue Catalog ──► Athena
```

-   Event-driven serverless processing
-   JSON → Parquet transformation
-   S3 partitioning
-   Automated schema discovery
-   Query-ready datasets through Amazon Athena

`AWS Lambda` `S3` `Glue` `Athena` `Python` `Parquet`

------------------------------------------------------------------------

# Experience

### Data Engineer --- Saylani Mass IT Training

Hands-on Data Engineering work involving: - Apache Kafka - PySpark /
Apache Spark - dlt - BigQuery - dbt - Kestra & Bruin - Docker - Batch
and streaming pipelines - Cloud data architectures

Worked under the mentorship of **Sir Qasim Hassan and Sir Ayan
Hussain**.

### Data Science Intern --- 10Pearls Pakistan

Built an end-to-end **AQI Forecasting & MLOps platform**, covering: -
Data ingestion and transformation - BigQuery and dbt - Feature
engineering - Machine learning and TensorFlow - Cloud Run API
deployment - Streamlit dashboard - Pipeline automation

### Data Engineering Intern --- Arch Technologies

**Jan 2026 -- Mar 2026 \| Remote**

-   Built ETL pipelines using Python, Pandas, and NumPy
-   Implemented automated data validation and quality checks
-   Standardized datasets across processing workflows
-   Prepared analytics-ready transformed datasets

------------------------------------------------------------------------

# Certification

::: {align="center"}
`<img src="https://img.shields.io/badge/Microsoft%20Certified-Fabric%20Data%20Engineer%20Associate-0078D4?style=for-the-badge&logo=microsoft&logoColor=white"/>`{=html}

### Microsoft Certified: Fabric Data Engineer Associate

**DP-700 --- Implementing Data Engineering Solutions Using Microsoft
Fabric**
:::

------------------------------------------------------------------------

# Education

  -----------------------------------------------------------------------
  Degree                  Institution             Duration
  ----------------------- ----------------------- -----------------------
  **BS Software           Sindh Madressatul Islam 2023 -- 2027
  Engineering**           University (SMIU),      
                          Karachi                 

  Intermediate ---        Govt. Boys Degree       2019 -- 2021
  Pre-Engineering         College, Naudero        
  -----------------------------------------------------------------------

------------------------------------------------------------------------

# Certifications & Learning

-   **Microsoft Certified: Fabric Data Engineer Associate --- DP-700**
-   Big Data Fundamentals with PySpark --- DataCamp
-   Snowflake Hands-On Essentials
-   Python --- DataCamp
-   Data Analytics --- Deloitte
-   GenAI Data Analytics --- Tata

------------------------------------------------------------------------

# GitHub Analytics

::: {align="center"}
`<img height="170" src="https://github-readme-stats.vercel.app/api?username=Naveedjokhio&show_icons=true&hide_border=true&bg_color=0d1117&title_color=38bdf8&icon_color=38bdf8&text_color=cbd5e1"/>`{=html}

`<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Naveedjokhio&layout=compact&hide_border=true&bg_color=0d1117&title_color=38bdf8&text_color=cbd5e1"/>`{=html}

`<br>`{=html}`<br>`{=html}

`<img src="https://streak-stats.demolab.com?user=Naveedjokhio&theme=dark&hide_border=true&background=0D1117&ring=38BDF8&fire=0EA5E9&currStreakLabel=38BDF8"/>`{=html}

`<br>`{=html}`<br>`{=html}

`<img src="https://github-readme-activity-graph.vercel.app/graph?username=Naveedjokhio&bg_color=0d1117&color=38bdf8&line=0ea5e9&point=ffffff&area=true&hide_border=true"/>`{=html}
:::

------------------------------------------------------------------------

::: {align="center"}
## Let's Connect

**Open to Junior / Associate Data Engineer roles, internships,
collaborations, and Data Engineering projects.**

`<a href="https://linkedin.com/in/naveed-jokhio">`{=html}`<img src="https://img.shields.io/badge/Connect%20on%20LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>`{=html}`</a>`{=html}
`<a href="mailto:naveedjokhio243@gmail.com">`{=html}`<img src="https://img.shields.io/badge/Email%20Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>`{=html}`</a>`{=html}
`<a href="https://naveedjokhio.netlify.app">`{=html}`<img src="https://img.shields.io/badge/View%20Portfolio-00C7B7?style=for-the-badge&logo=netlify&logoColor=white"/>`{=html}`</a>`{=html}

`<br>`{=html}`<br>`{=html}

**Python • SQL • Spark • Kafka • AWS • GCP • Microsoft Fabric • SAP •
Snowflake • dbt**
:::
