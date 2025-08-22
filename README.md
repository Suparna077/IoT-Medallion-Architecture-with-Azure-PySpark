# IoT Medallion Architecture with Azure & PySpark 📡⚙️

This project demonstrates a real-time data engineering pipeline for IoT sensor data using **Apache Spark**, **Azure Databricks**, and the **Medallion Architecture** (Bronze → Silver → Gold). 
It showcases how to ingest, transform, and aggregate streaming data for analytics and machine learning use cases.

## 🏗️ Architecture Overview
IoT Devices → Azure IOT Hub → Databricks (Bronze → Silver → Gold) → Azure Synapse / Power BI


- **Bronze Layer**: Raw ingestion from Azure Event Hub
- **Silver Layer**: Cleansed and structured data with schema enforcement
- **Gold Layer**: Aggregated KPIs for business intelligence

## 🔧 Tech Stack

- **Azure IOT Hub** (Streaming ingestion)
- **Azure Databricks** (Spark Structured Streaming)
- **PySpark** (DataFrame API, window functions)
- **Delta Lake** (ACID transactions, schema evolution)
- **Azure Synapse / Power BI** (Downstream analytics)

## 📁 Notebook Highlights

| Notebook | Description |
|----------|-------------|
| `Streaming_Data_Engineering_Project.ipynb` | End-to-end pipeline from IOT Hub to Delta Lake, implementing Medallion architecture with checkpointing and watermarking. |

## 🧠 Key Concepts Demonstrated

- Real-time ingestion using Spark Structured Streaming
- Medallion architecture for scalable data modeling
- Delta Lake for versioned, reliable storage
- Window functions and aggregations for IoT metrics
- Checkpointing and fault tolerance in streaming jobs

## 🚀 How to Run

1. Set up Azure Event Hub and stream sample IoT data.
2. Configure secrets and connection strings in Databricks.
3. Upload the notebook and run each cell sequentially.
4. Monitor streaming job progress and validate Delta tables.

## 📌 Author

**Suparna Chakraborty**  
Azure Data Engineer | Streaming & ETL Specialist  
📍 Preparing for relocation to Germany 🇩🇪  
📫 [LinkedIn](https://www.linkedin.com/in/suparna-chakraborty/) | [GitHub](https://github.com/Suparna077)

---

