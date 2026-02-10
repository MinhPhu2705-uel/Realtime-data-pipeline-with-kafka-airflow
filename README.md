# Requirements
kafka==1.3.5
kafka-python==2.0.2
requests==2.27.1
json5==0.9.6
mysql-connector-python==8.0.33

# Project Overview
This project implements a real-time cryptocurrency data streaming pipeline using modern data engineering tools. The system collects live crypto market data, processes it through a streaming platform, and stores it in a database for further analysis.

# Tech Stack
- Python
- Apache Kafka
- Apache Airflow
- MySQL
- Docker & Docker Compose

# Pipeline Flow
- Fetch live crypto data from an API.
- Stream the data into Kafka topics.
- Use Airflow DAG to orchestrate the workflow.
- Consume Kafka messages and write them into MySQL.
- Store structured data for analytics or downstream applications.
