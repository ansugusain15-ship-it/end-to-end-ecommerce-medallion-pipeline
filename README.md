# End-to-End E-Commerce Medallion Pipeline

## Overview
-This project demonstrates an end-to-end Data Engineering pipeline built on Azure using Azure Databricks, PySpark, Delta Lake, and Apache Airflow.
The pipeline follows the Medallion Architecture (Bronze, Silver, and Gold) to ingest, validate, transform, and prepare e-commerce data for analytics.

-The workflow is orchestrated using Apache Airflow, while Databricks Jobs execute each stage of the pipeline.
The project also includes data quality validation, reconciliation checks, and audit tracking to simulate a production-ready data engineering workflow.


## Tech Stack
- Azure Databricks
- PySpark
- Azure Data Lake Storage Gen2 (ADLS)
- Azure Storage Account
- Apache Airflow
- SQL
- Python
- Git & GitHub
  

## Pipeline Flow
Start
  ↓
Source Readiness Check
  ↓
Bronze RDBMS Ingestion, Bronze File Ingestion
  ↓
Bronze Reconciliation Check
  ↓
Silver Transformation Job
  ↓
Silver Data Quality Summary Job
  ↓
Gold Transformation Job
  ↓
Gold Reconciliation Check
  ↓
End


## Project Workflow
1. Perform source readiness validation.
2. Ingest source data into the Bronze layer.
3. Validate and reconcile Bronze data.
4. Transform Bronze data into the Silver layer.
5. Generate data quality metrics for the Silver layer.
6. Transform curated data into Gold business models.
7. Perform reconciliation checks on Gold datasets.
8. Complete the pipeline execution.


## Key Features
- End-to-End ETL Pipeline
- Medallion Architecture
- Databricks Job Orchestration
- Apache Airflow DAG
- Bronze, Silver & Gold Layers
- Data Quality Validation
- PySpark Transformations
- Delta Lake Storage
- Modular Pipeline Design


## Project Structure
ecom-medallion-pipeline/

├── data_ingestion/
├── data_quality_rules/
├── bronze/
├── silver/
├── gold/
├── orchestration/
└── README.md


## Author
Ansu Gusain
Aspiring Data Engineer
