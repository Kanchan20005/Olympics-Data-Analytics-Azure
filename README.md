# Olympics-Data-Analytics-Azure
This is an end to end data engineering project on Azure portal with the use of Kaggle data (Olympic Data Analytics).The tools used here are Azure Data Factory, Data Lake Gen 2, Synapse Analytics, and Azure Databricks.

## Introduction
The goal of this project is to create an end-to-end data pipeline that integrates with different CSV files stored in this github repository. We load the data into the Azure Data Factory and transform the data using Databricks using Spark. Then the data is finally loaded into the Azure Data Lake Gen 2. Also, the data is analyzed using Azure Synapse Analysis and visualized using Power BI.

The project consists of several components, including data extraction/ingestion, transformation, data loading, data analysis, and finally data visualization.

___

## Architecture
<p>
<img src="https://github.com/Kanchan20005/Olympics-Data-Analytics-Azure/assets/43069585/5180932a-dae3-49fb-a6c1-28ef54f912e8" align="left"
     alt="Mage-ai"  width=100% height=100%>
</p>

<br>

## Technology Used
___
### Programming Language
     * Python
     * pySpark
     * SQL
### Azure Platform 
     * Azure Data Factory
     * Azure Data Lake Gen 2
     * Databricks
### Visualization and Analytics
     * Power BI
     * Azure Synapse Analysis


## Project Structure:
#### Data Ingestion
Use Azure Data Factory to configure data ingestion from your chosen data sources. Define the data movement and transformation activities required to bring the Olympics data into the Azure ecosystem.

####  Data Storage
The ingested data will be stored in Azure Data Lake Storage Gen2. Set up the appropriate folder structure and permissions to organize and secure your data.

#### Data Transformation
Utilize Azure Databricks with PySpark for data transformation. Cleanse, preprocess, and reshape the data as necessary to prepare it for analysis.

#### Analytics
Write SQL queries using Azure Synapse Analytics to gain insights from the transformed data. Identify trends, statistics, and patterns related to the Olympics data.


## Power BI Dashboard

<p>
<img src="https://raw.githubusercontent.com/Kanchan20005/Olympics-Data-Analytics-Azure/main/Power%20BI.png" align="left"
     alt="Mage-ai"  width=100% height=100%>
</p>

<br>

