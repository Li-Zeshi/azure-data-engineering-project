 azure-data-engineering-project
End-to-End Azure Data Engineering Project based on Udemy course

 🌐 Azure Data Engineering Project (End-to-End Pipeline)

 📌 Overview
This project simulates a real-world enterprise-grade data engineering pipeline using Microsoft Azure cloud services. It demonstrates a complete data workflow from extraction to transformation and loading (ETL), leveraging key Azure services.

 ⚙️ Tech Stack
- Azure Data Factory (ADF)
- Azure Blob Storage
- Azure SQL Database
- Azure Logic Apps (optional)
- PySpark / Python
- Powerbi

 📐 Architecture Diagram
A high-level overview of the pipeline architecture is included in the 'diagrams/' folder.  
It includes data ingestion, transformation, storage, and automation flows.

 🔁 Workflow Steps
1. Ingestion: ADF retrieves raw data from external sources (e.g., API, Blob)
2. Transformation: Data is cleaned and processed using PySpark
3. Storage: Final datasets are loaded into Azure SQL Database
4. Automation: ADF Trigger automates pipeline execution on schedule

 🧠 Key Features
- End-to-end orchestration using ADF pipelines and linked services
- Error handling and retry logic for reliability
- Modular and reusable PySpark scripts
- Realistic simulation of enterprise data processing pipelines

 📷 Screenshots
Visuals showing your ADF pipeline, Key Vault secrets, database output, and pipeline runs can be found in the `screenshots/` folder.


 📝 Notes
This repository is based on a guided course project I followed on Udemy:  
“End to End Real-Time Azure Data Engineering Project”
All configurations, steps, and screenshots are documented for learning and interview preparation purposes.
