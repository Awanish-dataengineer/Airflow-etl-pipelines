# 🔄 Airflow ETL Pipelines — AWS & Snowflake

## 📌 Project Overview
Production-grade Apache Airflow ETL pipelines for
end-to-end data orchestration. Processes 1TB–10TB
of data using AWS and Snowflake — built for
reliability, scalability and monitoring.

## 🏗️ Architecture
Source Data → AWS S3 → Airflow DAGs → Snowflake
→ DBT Transformation → Reporting Layer

## 🛠️ Tech Stack
| Tool | Purpose |
|------|---------|
| Apache Airflow | Pipeline Orchestration |
| Snowflake | Data Warehouse |
| AWS S3 | Raw Data Storage |
| DBT | Data Transformation |
| Python | DAG Development |
| SQL | Data Processing |
| Git | Version Control & CI/CD |
| Azure | Cloud Data Processing |

## 📊 Key Features
- ✅ Processes 1TB–10TB data on Snowflake
- ✅ 100+ business metrics supported
- ✅ AWS S3 to Snowflake ingestion pipelines
- ✅ Airflow DAGs with retry and alerting logic
- ✅ DBT integrated within Airflow workflows
- ✅ CI/CD deployment using Git
- ✅ Supports healthcare and retail domains

## 📁 Project Structure

├── dags/
│   ├── healthcare/     # Hospital readmission DAGs
│   ├── retail/         # PETCO analytics DAGs
│   └── marketing/      # Campaign analytics DAGs
├── plugins/            # Custom Airflow operators
├── scripts/
│   └── ingestion.py    # AWS S3 ingestion scripts
├── config/             # Airflow connections config
├── tests/              # DAG unit tests
└── README.md

## 🔑 Key Achievements
- Orchestrated pipelines processing **1TB–10TB**
  of data on Snowflake using Airflow + AWS
- Supported **100+ business metrics** for Key
  Driver Analysis at PETCO
- Reduced query processing time from **2 hours
  to 30 minutes** through pipeline optimization
- Implemented CI/CD for seamless pipeline
  deployment using Git

## 📬 Contact
**Awanish Kumar** — Senior Data Engineer
- 📧 awshi91@gmail.com
- 🔗 linkedin.com/in/awanish-kumar-4621a1a1
