# Building-a-MS-Fabric-End-To-End-Data-Pipeline
This project demonstrates a complete data engineering workflow using Microsoft Fabric and Power BI.

**Workflow Overview

Data Ingestion: A Fabric Data Pipeline copies data directly from GitHub into a Lakehouse.

Data Transformation: A Fabric Notebook cleans and processes the raw data, storing the results as Delta tables in the Lakehouse.

Analytics & Reporting: Power BI connects to the Lakehouse using DirectQuery, providing real-time dashboards and insights.

Automation: Pipelines can be scheduled to refresh automatically, ensuring up-to-date reporting without manual intervention.

🔹 Key Features

End-to-end data pipeline (ingestion → transformation → reporting).

Lakehouse storage with SQL Endpoint for seamless analytics.

Power BI dashboard with live connection (DirectQuery).

Scalable and reproducible setup for future projects.
