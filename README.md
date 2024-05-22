# Pizza Sales Analytics using Azure

## Project Overview
- The "Pizza Sales Analytics using Azure" project aims to build a comprehensive data pipeline and analytical solution for pizza sales data. The project involves extracting sales data from SQL Server, transforming it using Azure Databricks, and visualizing it in Power BI to provide insightful dashboards for stakeholders.

## Table of Contents
- Introduction
- Architecture
- Setup and Installation
- Data Pipeline
- Data Transformation
- Data Visualization
- Usage
- Contributing
- Contact

## Introduction
This project demonstrates a complete data analytics workflow using Microsoft Azure services. It includes data extraction, transformation, and visualization steps, which are essential for making data-driven decisions.

## Architecture
The project architecture consists of the following components:
- SQL Server: The source database containing pizza sales data.
- Azure Data Factory (ADF): Orchestrates the data pipeline to extract data from SQL Server and load it into Azure Blob Storage.
- Azure Blob Storage: Serves as the data lake to store raw and transformed data.
- Azure Databricks: Performs data transformation to clean and format the data.
- Power BI: Visualizes the transformed data through interactive dashboards.

## Setup and Installation
### Prerequisites
- Azure subscription
- SQL Server with pizza sales data
- Power BI Desktop

### Steps
#### 1. Create Resources in Azure:
- Set up an Azure Data Factory instance.
- Create a storage account with a Blob Storage container.
- Set up an Azure Databricks workspace.

2. SQL Server Configuration:
- Ensure the SQL Server is accessible from Azure services.
- Create necessary tables and populate them with sales data.

3. Azure Data Factory:
- Create linked services for SQL Server and Blob Storage.
- Develop and publish the pipeline to extract data from SQL Server and load it into Blob Storage.

4. Azure Databricks:
- Configure a cluster and workspace.
- Develop notebooks to transform the data and save the results back to Blob Storage.

5. Power BI:
- Connect to the transformed data in Blob Storage.
- Create dashboards to visualize the sales data.

## Data Pipeline

1. Extraction:
- Use Azure Data Factory to create a pipeline that extracts data from SQL Server.
- Load the extracted data into Azure Blob Storage in a raw format.

2. Loading:
- The raw data is stored in Blob Storage for further processing.

## Data Transformation
1. Azure Databricks:
- Develop notebooks to read raw data from Blob Storage.
- Apply necessary transformations, such as cleaning, aggregation, and formatting.
- Write the transformed data back to Blob Storage in a structured format suitable for analysis.

## Data Visualization
1. Power BI:
- Import the transformed dataset from Blob Storage.
- Create interactive and insightful dashboards.
- Customize visuals to meet client requirements.

## Usage
1. Running the Pipeline:
- Trigger the Azure Data Factory pipeline to refresh data.
- Monitor the pipeline for successful execution.

2. Analyzing Data:
- Open Power BI Desktop.
- Refresh the dataset to load the latest transformed data.
- Explore the dashboards to gain insights into pizza sales trends.

## Contributing
Contributions are welcome! Please create a pull request or open an issue to discuss any changes or improvements.

## Contact
For more information, to provide feedback, or to get involved, please contact me at anujjhunjhunwala98@gmail.com
