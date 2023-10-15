# Data Engineering Project Submission for Sprint's Masterclass

## Overview

This repository showcases my comprehensive data engineering project, where I utilized the Azure ecosystem to create an end-to-end data pipeline, encompassing data ingestion, transformation, and visualization. The project not only demonstrates my technical skills but also emphasizes best practices in data engineering and visualization.

## Project Structure

The project is organized into several key sections:

### Step 1: Resource Setup
![Step 1: Resource Setup] (azureResources.png)

I began by setting up essential Azure resources, including Blob Storage, Azure Databricks, Azure SQL, and Azure Data Factory.

### Step 2: Linked Services
![Step 2: Linked Services](/pipline.png)

I configured linked services for each component to establish seamless connectivity and data transfer between them.

### Step 3: Data Ingestion
![Step 3: Data Ingestion](/storage/3.png)

As part of data ingestion, I uploaded the COVID-19 dataset to a Blob Storage container as the source data. I utilized Azure Data Factory (ADF) to create an efficient data ingestion pipeline, connecting to the repository and logging each step of the process.

### Step 4: Data Staging
![Step 4: Data Staging](/allpipline.png)

I staged the data as a copy into a second container as a step in the pipeline to ensure data integrity and facilitate further processing.

### Step 5: Exploratory Data Analysis (EDA)
![Step 5: Exploratory Data Analysis](/CovidAnalysis.ipynb.png)

For in-depth data analysis, I used Azure Databricks to perform exploratory data analysis, enabling me to gain valuable insights and uncover patterns within the data.

### Step 6: Data Transformation
![Step 6: Data Transformation](/Dataflow.png)

I designed a dataflow step in the pipeline to transform data types, ensuring that the data aligns with the intended structure.

### Step 7: Power BI Dashboard
![Step 7: Power BI Dashboard](/dashboard.png)

I connected Power BI to the Azure SQL database and created an interactive dashboard. The dashboard includes a world map visualizing COVID-19 cases, overview statistics, and rankings of top and least affected countries.

## Repository Contents

To provide a comprehensive overview of the project's progression, this repository includes the following components:
- **Screenshots**: Visual documentation of each key step in the project.
- **Pipeline JSON Files**: JSON files for the pipeline, datasets, and dataflow, offering complete transparency into the pipeline's structure and configuration.
- **EDA Databricks File**: The Databricks notebook used for exploratory data analysis.
- **Power BI Dashboard**: The Power BI report showcasing the visualization of COVID-19 data.

## How to Replicate the Project

For those interested in replicating this project, I have included detailed documentation and configurations in the repository. Follow these steps to recreate the project:

1. Set up the Azure resources, including Blob Storage, Azure Databricks, Azure SQL, and Azure Data Factory.
2. Configure linked services for each resource to establish connections.
3. Use Azure Data Factory to create a data ingestion pipeline.
4. Perform EDA using Azure Databricks.
5. Create a dataflow step in the pipeline to transform data types.
6. Connect Power BI to the Azure SQL database and recreate the dashboard.


## Get Started

- Clone this repository to access all project files.
- Refer to the project's documentation for step-by-step instructions.

By showcasing this project, I hope to provide an insightful and practical demonstration of data engineering best practices within the Azure ecosystem. For further details, please explore the repository and documentation.
