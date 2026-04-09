# Medallion Data Pipeline using PySpark & Databricks

## Overview
This project demonstrates an end-to-end data pipeline using Medallion Architecture (Bronze -> Silver -> Gold) to transform raw data into structured, analytics-ready datasets in Databricks. It mirrors enterprise data engineering workflows focused on scalable ingestion, reliable transformations, and AI-ready data products.

![bronze-silver-gold](https://github.com/vinodtkn/MedallionArchitecture/assets/82138543/fb2e7768-7c89-4947-930d-7a5d91afecb7)

## Architecture
- **Bronze Layer (Raw Ingestion):** Raw data landing zone for auditability and replay.
- **Silver Layer (Cleaned + Validated):** Standardized schema, data quality checks, and transformations.
- **Gold Layer (Business Aggregates):** Curated, analytics-ready outputs for reporting or ML/AI consumption.

## Tech Stack
- PySpark
- Databricks (Notebooks + Workflows)
- SQL
- Parquet

## Key Features
- Layered ETL pipeline design aligned to Medallion Architecture
- PySpark transformations and aggregations across Bronze, Silver, and Gold
- Databricks Workflows orchestration for end-to-end execution
- Data quality checkpoints to improve reliability and AI readiness

## Relevance
- **Data Engineering:** Multi-layer pipeline with PySpark/SQL in Databricks
- **Medallion Architecture:** Clear Bronze/Silver/Gold separation with quality gates
- **AI-Ready Data:** Curated Gold datasets suitable for analytics or downstream AI PoCs
- **Governance Foundations:** Structured layers and reproducible workflows for lineage-ready datasets

## Project Structure
- `bronze_*.ipynb` - raw ingestion notebooks
- `silver_*.ipynb` - cleaning, validation, and transformation notebooks
- `gold_*.ipynb` - aggregations and business-ready outputs

## Dataset
Sample dataset is included in the repo (gz file). Full dataset reference:
https://www.unb.ca/cic/datasets/andmal2020.html

## References
- Databricks Workflows: https://docs.databricks.com/en/workflows/index.html
