# PySpark Project to Learn Advanced DataFrame Concepts

This is the second project in the PySpark series.

## Overview
Apache Spark is an open-source, distributed computing framework designed for processing and analyzing large-scale datasets. It provides a unified engine that supports various data processing tasks, including batch processing, interactive queries, streaming, machine learning, and graph processing. Spark is implemented in Scala and offers APIs in Scala, Java, Python (PySpark), and R (SparkR).

PySpark stands as a robust open-source tool designed to process and analyze data across a network of computers. It presents a Python interface to Apache Spark, a swift and versatile system for distributed computing. Here are a few explanations for PySpark's extensive adoption: handling vast amounts of data, quick and efficient operations, staying resilient and scalable even when issues arise, seamless collaboration with the Python environment, intricate data analysis capabilities, and being a part of a supportive community and ecosystem.

## Data
The TLC (Taxi and Limousine Commission) Trip Record Data refers to a dataset that contains detailed information about taxi trips in New York City. This dataset is made available by the TLC, which regulates and oversees the taxi and for-hire vehicle industry in the city.

The TLC Trip Record Data includes various attributes for each taxi trip, such as the pickup and drop-off locations, trip distance, trip duration, fare amount, payment type, and additional surcharges. It also provides information about the taxi's unique identifier, driver details, and other relevant trip-related information.

The dataset is often used for a wide range of purposes, including transportation analysis, urban planning, predictive modeling, fare optimization, and studying travel patterns in the city. Researchers, data scientists, and analysts can leverage this dataset to gain insights into taxi usage, passenger behavior, and transportation trends.

_Data is not included in this repository._

## Tech stack
➔ Language: Python, SQL ➔ Package: PySpark

Key Takeaways:
- Understanding the New York Taxi Trip dataset
- Installing PySpark on the local system
- Understanding the difference between Spark Datasets, DataFrames
- Understanding the use of Spark SQL to query Structured data
- Understanding Spark SQL in detail
- Understanding Spark SQL Joins
- Understanding Spark Life Cycle
- Understanding Spark Performance
- Understanding Spark Optimizations techniques
- Different Query Executions Plans in Spark
- Understanding the importance of Spark User-defined Functions
- Difference between Spark UDF and P.

## How to run
Notebooks: [`lab_1_notebook.ipynb`](Code/notebooks/lab_1_notebook.ipynb), [`lab_2_notebook.ipynb`](Code/notebooks/lab_2_notebook.ipynb), [`lab_3_notebook.ipynb`](Code/notebooks/lab_3_notebook.ipynb), [`lab_4_notebook.ipynb`](Code/notebooks/lab_4_notebook.ipynb)

## Project structure
```
.gitignore
Code/
  notebooks/
    lab_1_notebook.ipynb
    lab_2_notebook.ipynb
    lab_3_notebook.ipynb
    lab_4_notebook.ipynb
  spark-jobs/
    spark-write-partitioned-data-lab-01.py
README.md
```

## Credits
Based on a ProjectPro guided project.
