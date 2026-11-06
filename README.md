# Data Engineering Portfolio

A collection of end-to-end data engineering projects: streaming and batch ingestion, data quality, dimensional modelling and analytics. Each project lives in its own folder with its own README, architecture description and instructions to run.

## Projects

| Project | What it shows | Stack | Status |
|---|---|---|---|
| [SaaS Revenue & Churn Analytics](saas-revenue-churn-pipeline/) | Daily file and Kafka ingestion, Bronze → Silver → Gold, data quality with quarantine, SCD 1 and 2, star schema, reconciliation with an independent ground truth | Python, Confluent Cloud Kafka, Databricks (Lakeflow, PySpark, Delta Lake), Power BI | Stage 1 (data platform) complete, Stage 2 (Power BI) in preparation |

Projects are developed with AI assistance (Claude); each project README describes the division of work.

## About the data

All datasets in this repository are synthetic and generated with fixed random seeds. They do not describe any real company or person.
