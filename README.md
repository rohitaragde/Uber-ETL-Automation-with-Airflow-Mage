# Uber-ETL-Automation-with-Airflow-Mage

## Introduction
The project focuses on performing thorough data analytics on Uber datasets, leveraging an array of tools like GCP Storage, Python, Compute Instance, Mage Data Pipeline Tool, BigQuery, and Looker Studio. Our methodology includes:

# Project Overview

This project aims to conduct comprehensive data analytics on Uber datasets by leveraging a variety of tools and technologies. The process involves several key steps:

- **Data Structuring with Lucid:** We begin by structuring Uber data using Lucid to create a comprehensive data model.

- **Data Extraction and Transformation with Mage:** Using Mage, we extract data from APIs and transform it into a star schema. Subsequently, the transformed data is loaded into BigQuery, making use of Google Cloud's compute instance.

- **In-depth Analysis on Google BigQuery:** We delve into detailed analysis on Google BigQuery, harnessing its computational capabilities to gain valuable insights from the data.

- **Visualizations with Looker Studio:** Insights derived from the analysis are presented through intuitive visualizations using Google's Looker Studio.


## Architecture 
<img src="images/architecture.jpg">

## Technologies Used

### Programming Language
- Python

### Google Cloud Platform
1. Google Storage
2. Compute Instance 
3. BigQuery
4. Looker Studio

### Modern Data Pipeline Tool
- [Mage](https://www.mage.ai/)


## Dataset Used
TLC Trip Record Data
Yellow and green taxi trip records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts. 

Here is the dataset - https://github.com/rohitaragde/Uber-ETL-Automation-with-Airflow-Mage/blob/master/data/uber_data.csv

More info about dataset can be found here:
1. Website - https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
2. Data Dictionary - https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf

## Data Model
<img src="data_model.jpeg">

## Screenshots
<img src="images/gcp_bucket.png">
<img src="images/architecture.jpg">
<img src="images/architecture.jpg">

## Complete Video Tutorial 
Video Link - https://youtu.be/WpQECq5Hx9g
