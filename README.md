<div align="center">

# Michael Okang

### Data Engineer | Batch, Streaming & Lakehouse Platforms

I build reliable data platforms that turn operational source data into governed, analytics-ready products.

[![Portfolio](https://img.shields.io/badge/Portfolio-okangmichael.com-1363C6?style=for-the-badge)](https://okangmichael.com)
[![Email](https://img.shields.io/badge/Email-okang.michael%40gmail.com-444444?style=for-the-badge)](mailto:okang.michael@gmail.com)

**Vienna, Austria • Open to relocation**

</div>

---

## Featured Engineering

### 🏔️ Project Alpine
**Real-Time Crypto Market Intelligence Platform**

`Kafka` `PySpark` `Spark Structured Streaming` `Databricks` `Delta Lake` `dbt` `Unity Catalog`

A fully shipped streaming lakehouse for multi-source cryptocurrency market data. Independent exchange feeds are isolated at ingestion, standardised through PySpark, validated, and promoted into governed analytical marts.

**Engineering highlights**
- Independent Python producers with source-isolated Kafka topics
- PySpark schema standardisation and reference joins
- Quarantine flow for invalid or incompatible records
- Checkpointed Delta processing for deterministic recovery
- Governed Bronze, Silver and Gold workloads in Databricks
- `fact_market_prices` plus 8 dbt Gold marts
- 38 passing data tests
- Local Docker, Kafka, Spark and Delta validation before cloud compute

**Repository:** [Project Alpine](https://github.com/Matoxki/Project-Alpine-Real-Time-Crypto-Market-Intelligence-Platform)  
**Portfolio:** [Read the project case study](https://okangmichael.com)

---

### 🚇 Vienna Transit Intelligence Platform
**Cloud Batch ELT Platform**

`Python` `Apache Airflow` `BigQuery` `dbt` `REST APIs`

A scheduled data platform combining Vienna public transport and weather data into tested analytical models.

**Engineering highlights**
- REST API ingestion from transport and weather sources
- 150+ U-Bahn platform stops across U1 to U6
- Numeric source identifier resolution
- Haversine-based weather-station mapping
- Append-only BigQuery history
- Incremental dbt transformations and tests
- Automated Airflow backfills
- Source replacement while preserving downstream contracts

**Repository:** [Vienna Transit Pipeline](https://github.com/Matoxki/vienna-transit-pipeline)  
**Portfolio:** [Read the project case study](https://okangmichael.com)

---

### 🛒 Cart Abandonment Engine
**Real-Time E-Commerce Streaming Platform**

`Kafka` `Snowflake` `dbt` `Airflow` `SQL`

A streaming pipeline that reconstructs user sessions from clickstream events and identifies abandoned carts from behavioural activity.

**Engineering highlights**
- Confluent Cloud event streaming
- Snowflake ingestion with managed connectors and Snowpipe
- Session reconstruction using SQL window functions
- Abandonment detection after 15 minutes of inactivity
- Hourly dbt transformations and data-quality checks with Airflow

**Repository:** [Real-Time E-Commerce Streaming Pipeline](https://github.com/Matoxki/Real-Time-ECommerce-Streaming-Pipeline)  
**Portfolio:** [Read the project case study](https://okangmichael.com)

---

## Current Work

### 🌊 Project Danube
**Governed CDC Data Platform**

`PostgreSQL` → `Debezium` → `Kafka` → `Delta Lake` → `dbt`

Currently developing a CDC platform focused on:

- preserving insert, update and delete history
- replayability and recoverable processing
- deterministic current-state reconstruction
- SCD history
- reconciliation and data quality
- schema evolution and governance

---

## Engineering Toolkit

| Area | Technologies |
|---|---|
| **Languages** | Python, SQL, Bash |
| **Streaming & Processing** | Apache Kafka, Apache Spark, PySpark |
| **Orchestration & Transformation** | Apache Airflow, dbt |
| **Platforms** | Databricks, Delta Lake, Snowflake, BigQuery, PostgreSQL |
| **Engineering Practices** | Data Quality, Dimensional Modelling, CDC, Backfills, CI/CD, Docker, Git |

---

## Selected Analytics Work

While my primary focus is Data Engineering, my analytics background helps me design data products with the downstream consumer in mind.

- [Chocolate Sales Analytics](https://github.com/Matoxki/Chocolate-Sales-Analytics-End-to-End-BI-Pipeline)
- [Cultural Heritage & Sustainability Analytics](https://github.com/Matoxki/Cultural-Heritage-Tourism-Data-Modeling-Sustainability-Analytics)

---

## Engineering Principles

I care about more than getting a pipeline to run once.

I design around **failure recovery, schema isolation, testability, cost awareness and clear data ownership** so systems remain understandable as they grow.

When a source or design choice does not satisfy the data contract, I prefer to change the architecture rather than hide the problem downstream.

---

<div align="center">

### Let's connect

🌐 [okangmichael.com](https://okangmichael.com)  
📧 [okang.michael@gmail.com](mailto:okang.michael@gmail.com)

**Currently open to Data Engineering opportunities and relocation.**

</div>