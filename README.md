# Big Data Workflow Project using Hadoop Ecosystem (Cloudera VM)

[![Hadoop](https://img.shields.io/badge/Hadoop-Ecosystem-yellow?logo=apache)](https://hadoop.apache.org/)
[![Spark](https://img.shields.io/badge/Spark-Big%20Data-orange?logo=apache-spark)](https://spark.apache.org/)
[![Hive](https://img.shields.io/badge/Hive-SQL-green?logo=apache-hive)](https://hive.apache.org/)
[![Linux](https://img.shields.io/badge/Linux-CLI-grey?logo=linux)](https://ubuntu.com/)

This project demonstrates a complete Big Data processing pipeline built on the Hadoop ecosystem using the Cloudera QuickStart VM. It covers hands-on implementations with **HDFS, YARN, Sqoop, Hive, Impala, Flume, Apache Spark (RDDs, SQL), and Spark Application development**.

---

## 📁 Repository Structure

```
Big-Data-Processing-with-Hadoop-Ecosystem/
│
├── Phase 1_HDFS_Sqoop/
│   └── Phase 1_HDFS_Sqoop.pdf
│
├── Phase 2_Hive_Impala_Sqoop_Flume/
│   └── Phase 2_Hive_Impala_Sqoop_Flume.pdf
│
├── Phase 3_Spark_RDD_SQL_Apps/
│   └── Phase 3_Spark_RDD_SQL_Apps.pdf
│
└── README.md
```

---

## 💡 Project Overview

The project simulates enterprise-level Big Data workflows using open-source technologies in a pseudo-distributed environment. All implementations were carried out inside a Cloudera VM using Linux shell commands, Hue interface, and various big data tools. Due to the nature of the tools used, **code and outputs were captured as annotated screenshots**, which are organized in PDF format for each phase.

---

## 📄 Documentation Summary

### 📘 Phase 1 – HDFS, YARN, Sqoop
📁 `Phase 1_HDFS_Sqoop/Phase 1_HDFS_Sqoop.pdf`

This phase covers foundational components of Hadoop and initial data ingestion.

✅ **Tools Covered**: HDFS, YARN, Hue, Sqoop

---

### 📘 Phase 2 – Hive, Impala, Avro, Flume
📁 `Phase 2_Hive_Impala_Sqoop_Flume/Phase 2_Hive_Impala_Sqoop_Flume.pdf`

Focuses on querying, data warehousing, and real-time ingestion.

✅ **Tools Covered**: Hive, Impala, Sqoop (Hive integration), Avro, Flume

---

### 📘 Phase 3 – Apache Spark (RDDs, SQL, Apps)
📁 `Phase 3_Spark_RDD_SQL_Apps/Phase 3_Spark_RDD_SQL_Apps.pdf`

Demonstrates distributed data processing with Apache Spark.

✅ **Tools Covered**: Apache Spark, Spark SQL, YARN, Hue, MySQL

---

## ⚙️ Environment Setup

- Cloudera QuickStart VM (CDH 5.13)
- VMware Workstation Player
- Terminal + Hue web interface

> 📝 All screenshots in the PDFs represent original work executed inside the Cloudera environment using CLI, editors, and web UIs.

---

## 🙋‍♂️ Author

**Shiva Kumar Reddy Koppula**  
Graduate Student – Business Analytics  
University of Texas at Dallas  
GitHub: [@shivakrdy](https://github.com/shivakrdy)

---

## 📈 Future Improvements

- Export terminal commands and script files from VM to GitHub
- Build a Docker-based replacement for the Cloudera VM
- Convert Spark logic to .py scripts for reuse and automation
