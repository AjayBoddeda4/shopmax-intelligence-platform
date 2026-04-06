# ShopMax Intelligence Platform

End-to-end data engineering project built from scratch.

## Architecture
Source Data → S3 Data Lake (Bronze/Silver/Gold) → AWS Glue + PySpark → Snowflake → dbt → Airflow → GenAI Layer

## Week 1 — Data Modelling + Storage Setup
- Designed Star Schema from first principles
- Fact Tables: FACT_ORDERS, FACT_ORDER_ITEMS, FACT_PAYMENTS
- Dimension Tables: DIM_CUSTOMER, DIM_PRODUCT, DIM_SELLER, DIM_LOCATION, DIM_DATE
- Created S3 data lake: shopmax-datalake (Bronze/Silver/Gold layers)

## Tech Stack
Python | AWS S3 | Kafka | AWS Glue | PySpark | Snowflake | dbt | Airflow | Great Expectations | GenAI (Claude API)
