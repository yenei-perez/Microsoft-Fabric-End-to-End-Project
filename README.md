# Microsoft-Fabric-End-to-End-Project
This analytics project is designed to capture the scope of a data scientist role. We will be building a data lakehouse, warehouse, pipeline,notebook, dataflow, a data model and finally a PowerBI report/dashboard

We will first ingest a semi structured csv sales file, which we will source from microsoft learning (https://github.com/MicrosoftLearning/dp-data/raw/main/sales.csv), into our lakehouse using Fabrics API Data Pipeline, then prep and stage the data using PySpark Notebook & Fabric DataFlow Gen2. We will continue using Fabric SQL Analytics Endpoint to build a relational data model with dimension tables. Finally, we will visualize our findings w PowerBI
