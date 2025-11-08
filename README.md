# Real-Time Stock Market Data Pipeline - Modern Data Stack

## Overview
End-to-end real-time streaming pipeline for NASDAQ stock market data using modern data engineering tools.

## Architecture


## Tech Stack
- **Streaming:** Apache Kafka, Zookeeper, Kafdrop
- **Storage:** MinIO (S3-compatible)
- **Orchestration:** Apache Airflow
- **Warehouse:** Snowflake
- **Transformation:** dbt (Data Build Tool)
- **Visualization:** Power BI
- **Infrastructure:** Docker Compose

## Prerequisites
- Docker Desktop
- Python 3.8+
- Snowflake Account (free trial)
- Finnhub API Key (free tier)
- Power BI Desktop

## Quick Start


## Project Structure


## Data Flow
1. Producer fetches live stock data from Finnhub API
2. Kafka streams events in real-time
3. Consumer writes to MinIO S3 bucket
4. Airflow orchestrates transfer to Snowflake
5. dbt transforms data (Bronze → Silver → Gold)
6. Power BI visualizes via DirectQuery

## Dashboard Features


