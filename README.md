###Build an ELT Pipeline in 1 Hour (dbt, Snowflake, Airflow)
Table of Contents
Project Overview
Technologies Used
Architecture
Setup Instructions
Step 1: Setup Snowflake Environment
Step 2: Configure dbt Profiles
Step 3: Create Source and Staging Files
Step 4: Create Macros
Step 5: Transform Models (Fact Tables, Data Marts)
Step 6: Testing with dbt
Step 7: Deploying with Airflow
Airflow DAG Configuration

Conclusion
Project Overview
This project demonstrates how to build an ELT (Extract, Load, Transform) pipeline using dbt (Data Build Tool), Snowflake, and Apache Airflow. The objective is to extract data from Snowflake's sample data, transform it using dbt models, and orchestrate the workflow using Airflow. The project follows best practices, including modular SQL files, reusable macros, and automated tests.

Technologies Used
dbt (Data Build Tool) for data transformation and modeling
Snowflake as the data warehouse
Apache Airflow for orchestration and scheduling
Docker for containerized development
Python for scripting and automation
Architecture
The ELT pipeline is designed as follows:

Extract: Data is extracted from Snowflake's sample TPCH dataset.
Load: Raw data is loaded into Snowflake tables.
Transform: dbt transforms the raw data into cleaned and aggregated tables.
Orchestrate: Airflow schedules and monitors the entire pipeline.
