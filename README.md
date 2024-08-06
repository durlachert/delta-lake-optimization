# Optimizing Delta Lake Lakehouse Tables for Improved Performance and Scalability


**Author:** Thomas Durlacher  
**Date:** 10 August 2024

## 1. Introduction

The project conducted an investigation of different Delta Lake optimization methods. The evaluation took place on a virtual Apache Spark cluster, providing insights into their efficiency, scalability, and compatibility within a distributed big data processing environment. To make the performance measurements comparable, one dataset was generated to create tables.


## 2. Repository

GitHub Repository: [https://github.com/DurlacherT/aws_emr_lakehouse](https://github.com/durlachert/delta-lake-optimization)

## 3. Objectives

- Evaluate the performance impact of optimization techniques.
- Assess the scalability of the solutions as the size of the dataset increases.
- Analyze the query performance on complex analytical workloads.
- Identify any notable advantages or limitations of each solution in the context of the project requirements.

## 4. Tools and Technologies

- Delta Lake
- Apache Spark
- Pyspark
- Scala
- Apache Kafka
- Apache Hive
- MySql
- HDFS
- Ubuntu
- Jupyter Notebook
- Apache Toree


## 5. Methodology

### Dataset Preparation:

Generate synthetic datasets of varying sizes to simulate real-world big data scenarios.

### Cluster Setup:

Deploy an Apache Spark and necessary dependencies for Delta Lake.

### Data Ingestion:

Load datasets into tables using both Iceberg and Delta Lake formats.

### Performance Metrics:

- Measure the time taken for read and write operations.
- Evaluate the scalability by gradually increasing the dataset size.
- Execute complex analytical queries and measure query performance.

### Observations and Analysis:

Document any challenges encountered during setup and configuration. Compare and contrast the performance metrics obtained.

## 6. Expected Outcomes

- A detailed report highlighting the strengths and weaknesses of Delta Lake optimization methods.
- Insights into the performance characteristics of both solutions under varying workloads and dataset sizes.
- Recommendations for selecting the appropriate solution based on specific use cases.
- Description and visual representation of different performance measurements.
