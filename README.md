# Flight Booking Data Pipeline

## Project Overview  
This project processes flight booking data using PySpark on Google Cloud Dataproc, orchestrated by Apache Airflow. It performs data transformation and loads insights into BigQuery tables for business analysis.

## Tech Stack  
- PySpark  
- Google Cloud Platform (Dataproc, BigQuery, Cloud Storage)  
- Apache Airflow  
- GitHub Actions (CI/CD)

## Features  
- Batch processing of flight booking data  
- Data transformation with derived columns and aggregations  
- Automated workflows using Airflow  
- Data ingestion into BigQuery  
- CI/CD deployment via GitHub Actions  

## How to Run  
1. Set up Google Cloud project with required permissions  
2. Upload source data to Google Cloud Storage  
3. Configure Airflow connections and variables  
4. Deploy PySpark job on Dataproc via Airflow DAG  
5. Run DAG to process and load data into BigQuery  

## Learnings  
- Hands-on experience with PySpark transformations  
- Building and scheduling data pipelines with Airflow  
- Working with cloud data platforms and serverless compute  
- Automating deployments with GitHub Actions  

## Files  
- `pyspark_jobs/flight_booking_etl.py`: PySpark job performing data processing  
- `airflow_dags/flight_booking_dag.py`: Airflow DAG to orchestrate the job  
- `requirements.txt`: Python dependencies  

## Author  
Farheen
