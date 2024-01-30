### Pizza Shop Sales Analysis and Visualisation Project

**Project Overview:**

In this project, an extensive sales analysis was conducted for a pizza shop, with the aim of uncovering key performance indicators (KPIs) and enhancing decision-making. The data, initially hosted on an on-premises database, underwent a transformation to be synchronised with the Azure Cloud. The analysis seamlessly transitioned through various Azure services and Databricks, culminating in a Power BI dashboard for intuitive and actionable insights.

**Project Steps:**

1. **Azure Storage Account Creation:**
   - Created an Azure Storage Account, setting up a container to house the pizza sales data.

2. **Azure Data Factory Setup:**
   - Established an Azure Data Factory to facilitate the orchestration of data workflows.

3. **Integration Runtime Configuration:**
   - Configured an Integration Runtime in Azure Data Factory to seamlessly connect on-premises data with cloud services.

4. **Data Pipeline from SQL to Storage:**
   - Orchestrated a data pipeline in Azure Data Factory, utilising a self-hosted link service and a runtime installed on-premises.
   - Connected the runtime to the cloud using Azure keys, facilitating the transfer of data from the on-premises SQL database to Azure Blob Storage.

5. **Databricks Integration:**
   - Connected Databricks to Azure Storage, enabling efficient data processing with PySpark on a created compute cluster.

6. **Aggregates Table Building with Spark SQL:**
   - Utilised Spark SQL in Databricks to aggregate and build tables that encapsulate key metrics and KPIs.

7. **Power BI Integration:**
   - Integrated Power BI with Azure Databricks using server hostname, HTTP path, and a personal access token.

8. **Power BI Dashboard Composition:**
   - Designed a Power BI dashboard encompassing the following key visualisations:
     - Card Display: Total pizza sold, total number of orders, and total sales.
     - Slicer Functionality: Filter by month name, day name, and order time.
     - Pie Chart: Illustrating total sales by pizza category and pizza size.
     - Line Chart: Depicting total orders and sales trends over different months.
     - Funnel Chart: Identifying the top 10 pizza names by total sales.
     - Column Chart: Displaying total orders categorised by day name.

**Outcome:**

The project successfully transitioned the pizza shop's sales data to the Azure Cloud, processed and aggregated it using Azure Data Factory and Databricks, and presented actionable insights through an interactive Power BI dashboard. This end-to-end solution empowers decision-makers with a comprehensive view of sales performance, facilitating strategic and informed actions for the pizza shop's growth and optimisation.
