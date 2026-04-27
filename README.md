# BigData-FinalProject-Airlines: Big Data Processing with PySpark

## ✈️ Project Overview
This project focuses on processing and analyzing a large-scale aviation dataset (~2 million records) using **Apache Spark**. The goal is to demonstrate the ability to handle massive datasets, perform data cleaning (preprocessing), and implement real-time data streaming pipelines.

## 🛠 Tech Stack
* **Language:** Python
* **Core Engine:** Apache Spark (PySpark)
* **Storage Formats:** CSV, Optimized Parquet
* **Processing:** Spark SQL & Structured Streaming
* **Environment:** Hadoop Ecosystem / Local Cluster

## 🌟 Key Features
* **Big Data Preprocessing:** Cleaning and casting raw CSV data into optimized types.
* **Performance Optimization:** Converting flat CSV files into **Partitioned Parquet** format, significantly reducing I/O overhead.
* **Complex Aggregations:** Identifying top-performing airlines and busiest airports using Spark SQL and `Union` operations.
* **Real-time Streaming:** Implementing a **Micro-batch** pipeline to monitor and process flight data folders in real-time using `writeStream` and `Checkpointing` for fault tolerance.

## 📈 Key Results
* **Data Locality:** Leveraged Spark's distributed computing to process millions of rows in seconds.
* **Throughput:** Established a streaming trigger interval of 10 seconds per batch for consistent data flow.
* **Insight:** Successfully identified the top 20 busiest airports based on total traffic (Origin + Destination).

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/AeroSpark-Analytics.git](https://github.com/your-username/AeroSpark-Analytics.git)
2. Ensure you have PySpark installed:
   ```bash
   pip install pyspark
3. Place the airline_2m.csv in the data/ folder.
4. Run the main script or Jupyter Notebook in the notebooks/ directory.
