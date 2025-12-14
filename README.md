# Hi there, I'm Phuc Vo! 👋

**Data Engineer | Big Data Enthusiast | Real-Time Analytics**

I am a final-year student passionate about designing and building scalable **Data Lakehouses** and **Real-Time Streaming** systems. My expertise lies in modern open-source data stacks, automating data workflows, and bridging the gap between Data Engineering and MLOps.

Currently, I'm focusing on **Spark Structured Streaming**, **Delta Lake**, and **CDC** patterns to solve complex data challenges.

---

## Tech Stack

### Languages & Scripting
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

### Big Data & Streaming
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta%20Lake-D95F02?style=for-the-badge&logo=deltalake&logoColor=white)
![Trino](https://img.shields.io/badge/Trino-DD00A1?style=for-the-badge&logo=trino&logoColor=white)

### Orchestration & Infrastructure
![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO-C72E49?style=for-the-badge&logo=minio&logoColor=white)
![Hive](https://img.shields.io/badge/Hive-FDEE21?style=for-the-badge&logo=apachehive&logoColor=black)

### MLOps & Backend
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

---

## Featured Project

### [Real-Time Fraud Detection Lakehouse](https://github.com/hungfnguyen/real-time-fraud-detection-lakehouse)
*A complete end-to-end data platform detecting credit card fraud with <1s latency.*

This project demonstrates a production-grade **Lakehouse Architecture** integrating streaming, batch processing, and machine learning.

**Architecture Highlights:**
- **Ingestion (CDC):** Capturing real-time changes from PostgreSQL using **Debezium** & **Kafka**.
- **Processing:** Hybrid processing with **Spark Structured Streaming** (Bronze) and Batch jobs (Silver/Gold).
- **Storage:** ACID transactions and Time Travel capabilities using **Delta Lake** on **MinIO** (S3-compatible).
- **Orchestration:** Automated ETL and Model Retraining pipelines managed by **Apache Airflow**.
- **MLOps:** Full lifecycle management (Tracking, Registry, Deployment) with **MLflow**.
- **Serving:** Low-latency inference API using **FastAPI** with rule-based fallback mechanisms.

**Key Metrics:**
- **Latency:** End-to-end transaction to alert in **< 1 second**.
- **Accuracy:** Achieved **92.8%** accuracy and **98.4% AUC-ROC** with RandomForest.


## Connect with me

- **Email:** [votrieu.phuc@gmail.com](mailto:votrieu.phuc@gmail.com)

*"The best way to learn data engineering is to build and break things. I'm here doing both."*
