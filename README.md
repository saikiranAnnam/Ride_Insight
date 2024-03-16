# Uber Data Analytics | Modern Data Engineering GCP Project

## Introduction


Creating a data analytics project for Uber using modern data engineering on Google Cloud Platform (GCP) involves several steps and components. 

Below is a high-level overview of how you could structure such a project:

## Project Overview:

**Objective:**

Enhance decision-making and optimize operations for Uber by analyzing and visualizing relevant data.

**Data Sources:**
Uber ride data, driver information, user feedback, geographic data, etc.
Tools and Technologies:

GCP services such as BigQuery, Cloud Storage, Dataflow, Pub/Sub, and Data Studio.
Python for data processing and analysis.


## Architecture 
<img src="architecture.jpg">


## Project Steps 

**Data Ingestion:**

Set up data ingestion pipelines to collect and process data from various sources.
Use Cloud Pub/Sub for real-time data streaming and Cloud Storage for batch data uploads.

**Data Storage:**
Store raw and processed data in BigQuery for easy querying and analysis.
Organize data into structured tables for efficient retrieval.

**Data Processing:**
Utilize Cloud Dataflow for data processing tasks, ensuring scalability and efficiency.
Implement data transformation and cleaning processes to handle missing or erroneous data.


## Technology Used
- Programming Language - Python

Google Cloud Platform
1. Google Storage
2. Compute Instance 
3. BigQuery
4. Looker Studio

Modern Data Pipeine Tool - https://www.mage.ai/

Contibute to this open source project - https://github.com/mage-ai/mage-ai


## Dataset Used
TLC Trip Record Data
Yellow and green taxi trip records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts. 

Here is the dataset used in the video - https://github.com/darshilparmar/uber-etl-pipeline-data-engineering-project/blob/main/data/uber_data.csv

More info about dataset can be found here:
1. Website - https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
2. Data Dictionary - https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf

## Data Model
<img src="data_model.jpeg">


