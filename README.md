# Build an ELT Pipeline in 1 Hour (dbt, Snowflake, Airflow)

## Table of Contents
- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Architecture](#architecture)
- [Conclusion](#conclusion)

## Project Overview
This project demonstrates how to build an ELT (Extract, Load, Transform) pipeline using **dbt (Data Build Tool)**, **Snowflake**, and **Apache Airflow**. The objective is to extract data from Snowflake's sample data, transform it using dbt models, and orchestrate the workflow using Airflow. The project adheres to best practices, including modular SQL files, reusable macros, and automated tests.

## Technologies Used
- **dbt (Data Build Tool)**: For data transformation and modeling
- **Snowflake**: As the data warehouse
- **Apache Airflow**: For orchestration and scheduling
- **Docker**: For containerized development
- **Python**: For scripting and automation

## Architecture
The ELT pipeline is designed as follows:
1. **Extract**: Data is extracted from Snowflake's sample TPCH dataset.
2. **Load**: Raw data is loaded into Snowflake tables.
3. **Transform**: dbt transforms the raw data into cleaned and aggregated tables.
4. **Orchestrate**: Airflow schedules and monitors the entire pipeline.

## Conclusion 
This project showcases how to build a scalable and efficient ELT pipeline using dbt, Snowflake, and Airflow. The pipeline leverages best practices in data transformation, testing, and orchestration, ensuring a robust data workflow.
Feel free to fork this repository and adapt it to your use case. Contributions and feedback are welcome!
