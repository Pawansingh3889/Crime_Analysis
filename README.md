# UK Crime Data Analysis (2022-2024)

## Overview
This project involved a comprehensive analysis of UK crime data from 2022 to 2024 to identify key trends and patterns related to crime type, geographical location (LSOAs), and reporting police agency.

## Goals
* Analyze the trend of overall crime rate over time, broken down by reporting police force.
* Visualize the geographical distribution of different crime types.
* Identify the most frequent crime types in specific local areas (LSOA).

## Data Processing
The analysis was performed using AWS services:
1. **Data Storage:** The raw crime data was stored in **Amazon S3**.
2. **Data Querying and Aggregation:** **Amazon Athena** was used to query the data directly from S3 using SQL. This involved aggregating crime counts by type, LSOA, and reporting agency over the specified years.
3. **Data Visualization:** **Amazon QuickSight** was used to create interactive visualizations from the data processed by Athena, including bar charts and stacked bar charts to represent the findings.

## Key Findings
* **Top Crime:** Violence and sexual offences were the most frequently recorded crimes.
* **Common Issue:** Anti-social behaviour also showed a high incidence.
* **Regional Differences:** The distribution of crime types varies significantly across different Local Super Output Areas (LSOAs).
* **High Reporting Agency:** The Metropolitan Police Service consistently reported the highest number of crimes.
* **Reporting Trends:** Trends in reported crime numbers varied among different police forces between 2022 and 2024.
