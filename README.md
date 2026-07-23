<div align="center">

<img src="https://capsule-render.vercel.app/api?type=soft&color=0:0D1117,100:161B22&height=180&section=header&text=Naveed%20Jokhio&fontSize=42&fontColor=E6EDF3&fontAlignY=45&desc=Data%20Engineer%20%7C%20Streaming%20%26%20Batch%20Pipelines%20at%20Scale&descAlignY=68&descSize=16&descColor=8B949E" width="100%"/>

<br>

<a href="https://naveedjokhio.netlify.app"><img src="https://img.shields.io/badge/Portfolio-161B22?style=flat-square&logo=netlify&logoColor=00C7B7"/></a>
<a href="https://github.com/Naveedjokhio"><img src="https://img.shields.io/badge/GitHub-161B22?style=flat-square&logo=github&logoColor=E6EDF3"/></a>
<a href="https://linkedin.com/in/naveed-jokhio"><img src="https://img.shields.io/badge/LinkedIn-161B22?style=flat-square&logo=linkedin&logoColor=0A66C2"/></a>
<a href="mailto:naveedjokhio243@gmail.com"><img src="https://img.shields.io/badge/Email-161B22?style=flat-square&logo=gmail&logoColor=EA4335"/></a>

<img src="https://komarev.com/ghpvc/?username=Naveedjokhio&style=flat-square&color=6366F1&label=PROFILE+VIEWS"/>
<img src="https://img.shields.io/github/followers/Naveedjokhio?style=flat-square&color=6366F1&labelColor=161B22"/>

</div>

<br>

## About

Final-year Software Engineering student at **Sindh Madressatul Islam University (SMIU), Karachi** (Batch 2023–2027), currently working across two concurrent roles — **Data Engineer at Saylani Mass IT Training** and **Data Science Intern at 10Pearls Pakistan**.

I work at the intersection of streaming and batch data engineering — Kafka pipelines, PySpark transformations, cloud warehouses, and orchestration that survives real production failures, not just demo runs. Based in Karachi, Pakistan.

<div align="center">

<img src="https://img.shields.io/badge/Status-Final%20Year%20Student-6366F1?style=flat-square&labelColor=161B22"/>
<img src="https://img.shields.io/badge/Role-Data%20Engineer-6366F1?style=flat-square&labelColor=161B22"/>
<img src="https://img.shields.io/badge/Location-Karachi%2C%20Pakistan-6366F1?style=flat-square&labelColor=161B22"/>
<img src="https://img.shields.io/badge/Open%20to-Cloud%20Data%20Engineering%20Roles-22C55E?style=flat-square&labelColor=161B22"/>

</div>

---

## Experience

<table>
<tr>
<td width="220" valign="top"><b>Data Engineer</b><br/><sub>Saylani Mass IT Training</sub><br/><sub>Current</sub></td>
<td valign="top">Building streaming &amp; batch pipelines with Kafka, PySpark, dlt, and BigQuery. Mentored by Sir Qasim Hassan &amp; Sir Ayan Hussain.</td>
</tr>
<tr>
<td width="220" valign="top"><b>Data Science Intern</b><br/><sub>10Pearls Pakistan</sub><br/><sub>Current</sub></td>
<td valign="top">Applying data science and analytics skills in a professional, industry-facing engineering environment.</td>
</tr>
<tr>
<td width="220" valign="top"><b>Data Engineering Intern</b><br/><sub>Arch Technologies · Remote</sub><br/><sub>Jan 2026 – Mar 2026</sub></td>
<td valign="top">Built end-to-end ETL pipelines in Python (Pandas, NumPy) — <b>↓30%</b> data prep time. Automated data validation &amp; quality checks — <b>↑20%</b> data accuracy. Standardized datasets across pipelines — <b>↑25%</b> data reliability.</td>
</tr>
</table>

---

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🏏 Cricbuzz Real-Time Data Pipeline
**Flagship project**

Full GCP-based streaming pipeline delivering live match data end-to-end:
**Kafka → GCS → dlt → BigQuery → dbt**, orchestrated with **Bruin + Kestra**.

Solved real production issues — Docker-in-Docker volume mounting, GCP ADC credential mounting inside Kestra containers, dlt pipeline state corruption, and WSL2 disk space exhaustion. Built a synthetic match simulator as a fallback when the live RapidAPI quota ran out. Presented with a 20-slide deck and verified pipeline metrics.

`Kafka` `dlt` `BigQuery` `dbt` `Kestra` `Bruin` `Docker`

</td>
<td width="50%" valign="top">

### 🛒 E-Commerce Data Pipeline
**In progress**

Production-grade pipeline combining **Kafka + PySpark** streaming ingestion with a full cloud-native medallion architecture landing in **GCS → BigQuery**.

Orchestrated with **Bruin** and **Kestra**, fully containerized via **Docker Compose**, developed end-to-end on Windows + GCP, targeting production-style reliability and observability.

`Kafka` `PySpark` `dlt` `GCS` `BigQuery` `Kestra` `Docker Compose`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ✈️ Flight Operations Analytics Pipeline

Batch pipeline ingesting live flight data from the OpenSky Network API every 30 minutes via an Airflow DAG. Medallion Architecture across 4 modular tasks, retry logic and idempotent task design, gold-layer KPIs loaded into Snowflake via UPSERT, visualized in Power BI.

`Airflow` `Python` `Snowflake` `Docker` `Power BI`

</td>
<td width="50%" valign="top">

### 🏨 End-to-End Hotel Booking Pipeline

Complete Medallion pipeline built natively in Snowflake. Bronze layer for raw ingestion, Silver layer fixing invalid emails/negative amounts/status typos, Gold layer powering an interactive Snowsight dashboard with KPIs and trend charts.

`Snowflake` `SQL` `Snowsight`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ⚡ AWS Serverless ETL Pipeline

Event-driven, serverless ETL pipeline converting raw JSON into columnar Parquet, cutting storage costs by ~40%. Schema inference automated via AWS Glue Crawlers with modular Lambda functions and S3 partitioning.

`S3` `Lambda` `Glue` `Athena` `Parquet`

</td>
<td width="50%" valign="top">

### 🔥 PySpark + dbt Streaming Pipeline

Streaming-style pipeline combining PySpark transformations with dbt modeling for analytics-ready outputs.

`PySpark` `dbt`
[→ github.com/Naveedjokhio/Pyspark_Dbt_Project](https://github.com/Naveedjokhio/Pyspark_Dbt_Project)

</td>
</tr>
</table>

---

## Tech Stack

<table>
<tr>
<td valign="top" width="25%">

**Languages**
<br>
<img src="https://img.shields.io/badge/Python-161B22?style=flat-square&logo=python&logoColor=3776AB"/><br>
<img src="https://img.shields.io/badge/SQL-161B22?style=flat-square&logo=postgresql&logoColor=4169E1"/>

</td>
<td valign="top" width="25%">

**Streaming & Processing**
<br>
<img src="https://img.shields.io/badge/Apache_Kafka-161B22?style=flat-square&logo=apachekafka&logoColor=white"/><br>
<img src="https://img.shields.io/badge/PySpark-161B22?style=flat-square&logo=apachespark&logoColor=E25A1C"/><br>
<img src="https://img.shields.io/badge/dlt-161B22?style=flat-square&color=161B22"/>

</td>
<td valign="top" width="25%">

**Cloud**
<br>
<img src="https://img.shields.io/badge/BigQuery-161B22?style=flat-square&logo=googlebigquery&logoColor=4285F4"/><br>
<img src="https://img.shields.io/badge/GCS-161B22?style=flat-square&logo=googlecloud&logoColor=4285F4"/><br>
<img src="https://img.shields.io/badge/AWS-161B22?style=flat-square&logo=amazonaws&logoColor=FF9900"/>

</td>
<td valign="top" width="25%">

**Warehousing**
<br>
<img src="https://img.shields.io/badge/Snowflake-161B22?style=flat-square&logo=snowflake&logoColor=29B5E8"/><br>
<img src="https://img.shields.io/badge/SQL_Server-161B22?style=flat-square&logo=microsoftsqlserver&logoColor=CC2927"/>

</td>
</tr>
<tr>
<td valign="top">

**Orchestration**
<br>
<img src="https://img.shields.io/badge/Airflow-161B22?style=flat-square&logo=apacheairflow&logoColor=017CEE"/><br>
<img src="https://img.shields.io/badge/Kestra-161B22?style=flat-square&color=6C3EF4"/><br>
<img src="https://img.shields.io/badge/Bruin-161B22?style=flat-square&color=161B22"/>

</td>
<td valign="top">

**Transformation**
<br>
<img src="https://img.shields.io/badge/dbt-161B22?style=flat-square&logo=dbt&logoColor=FF694B"/>

</td>
<td valign="top">

**Tooling**
<br>
<img src="https://img.shields.io/badge/Docker-161B22?style=flat-square&logo=docker&logoColor=2496ED"/><br>
<img src="https://img.shields.io/badge/Pandas-161B22?style=flat-square&logo=pandas&logoColor=E70488"/><br>
<img src="https://img.shields.io/badge/NumPy-161B22?style=flat-square&logo=numpy&logoColor=4DABCF"/>

</td>
<td valign="top">

**Visualization**
<br>
<img src="https://img.shields.io/badge/Power_BI-161B22?style=flat-square&logo=powerbi&logoColor=F2C811"/>

</td>
</tr>
<tr>
<td colspan="4" valign="top">

**Core Concepts**
<br>
<img src="https://img.shields.io/badge/Medallion_Architecture-6366F1?style=flat-square&labelColor=161B22"/>
<img src="https://img.shields.io/badge/Star_Schema-6366F1?style=flat-square&labelColor=161B22"/>
<img src="https://img.shields.io/badge/SCD_Type--2-6366F1?style=flat-square&labelColor=161B22"/>
<img src="https://img.shields.io/badge/Real--Time_Streaming-6366F1?style=flat-square&labelColor=161B22"/>
<img src="https://img.shields.io/badge/ETL%2FELT-6366F1?style=flat-square&labelColor=161B22"/>

</td>
</tr>
</table>

---

## Education & Certifications

<table>
<tr>
<td width="240" valign="top"><b>BS Software Engineering</b></td>
<td valign="top">Sindh Madressatul Islam University (SMIU), Karachi — 2023 to 2027</td>
</tr>
<tr>
<td width="240" valign="top"><b>Intermediate (Pre-Engineering)</b></td>
<td valign="top">Govt. Boys Degree College, Naudero — 2019 to 2021</td>
</tr>
</table>

<div align="center">

<img src="https://img.shields.io/badge/Data_Analytics-Deloitte-161B22?style=flat-square&labelColor=161B22&color=86BC25"/>
<img src="https://img.shields.io/badge/GenAI_Data_Analytics-TATA-161B22?style=flat-square&labelColor=161B22&color=00BFFF"/>
<img src="https://img.shields.io/badge/Python-DataCamp-161B22?style=flat-square&labelColor=161B22&logo=datacamp&logoColor=03EF62"/>
<img src="https://img.shields.io/badge/Essentials-Snowflake-161B22?style=flat-square&labelColor=161B22&logo=snowflake&logoColor=29B5E8"/>
<img src="https://img.shields.io/badge/Data_Scientist-NED_University-161B22?style=flat-square&labelColor=161B22&color=DC143C"/>

</div>

---

## GitHub Activity

<div align="center">

<img width="48%" src="https://github-readme-stats.vercel.app/api?username=Naveedjokhio&show_icons=true&theme=tokyonight&hide_border=true&title_color=6366F1&icon_color=8B5CF6&text_color=c9d1d9&bg_color=0D1117"/>
<img width="48%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Naveedjokhio&layout=compact&theme=tokyonight&hide_border=true&title_color=6366F1&text_color=c9d1d9&bg_color=0D1117"/>

<br><br>

<img src="https://streak-stats.demolab.com?user=Naveedjokhio&theme=tokyonight&hide_border=true&background=0D1117&ring=6366F1&fire=8B5CF6&currStreakLabel=A78BFA"/>

<br><br>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Naveedjokhio&theme=tokyo-night&hide_border=true&bg_color=0D1117&color=6366F1&line=8B5CF6&point=A78BFA"/>

</div>

---

## Trophy Room

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=Naveedjokhio&theme=discord&no-frame=true&row=1&column=6&margin-w=8"/>

</div>

---

<div align="center">

### Let's build the next pipeline together

*Open to Data Engineering roles, internships &amp; collaborations*

<a href="https://linkedin.com/in/naveed-jokhio"><img src="https://img.shields.io/badge/Connect-161B22?style=flat-square&logo=linkedin&logoColor=0A66C2"/></a>
<a href="mailto:naveedjokhio243@gmail.com"><img src="https://img.shields.io/badge/Say_Hello-161B22?style=flat-square&logo=gmail&logoColor=EA4335"/></a>

<br><br>

<img src="https://capsule-render.vercel.app/api?type=soft&color=0:161B22,100:0D1117&height=100&section=footer" width="100%"/>

</div>
