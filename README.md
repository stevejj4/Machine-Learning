# Real-Time Machine Learning and Prediction Pipeline

## Overview

This project aims to build a real-time data pipeline that enables continuous monitoring, analysis, and prediction based on data entered into Google Sheets. The system is designed to provide immediate insights and facilitate decision-making through real-time data processing and machine learning.

### Architecture

1. **Google Sheets**: Source of real-time data entry.
2. **Google Cloud Platform (GCP)**:
   - **BigQuery**: Data warehouse for storing and querying data.
   - **Pub/Sub**: Real-time messaging service for streaming data changes.
   - **Dataflow**: Processes data in real-time from Pub/Sub to BigQuery.
3. **Apache Spark**: Real-time data processing and analysis.
4. **Machine Learning Models**: Built using PyTorch or TensorFlow for predictions.
5. **Visualization**: Power BI dashboards for real-time data visualization and insights.

### Setup

#### Prerequisites

- Google Cloud Project with BigQuery, Pub/Sub, and Dataflow enabled.
- Google Sheets for data entry.
- Apache Spark installed with BigQuery connector.
- Google Cloud SDK installed and configured.
- Power BI for visualization.

#### Installation

1. **Google Colab Setup**

   Install necessary Python packages:

   ```python
   !pip install gspread google-auth google-cloud-bigquery pandas pyspark
