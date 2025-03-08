# Netflix Azure Project

## Overview

This project leverages Microsoft Azure services and Databricks to process, transform, and analyze Netflix data efficiently. It utilizes Databricks notebooks for data ingestion, transformation, and management using Delta Lake and Auto Loader features.

## Features

- **Automated Data Ingestion**: Uses Databricks Auto Loader for seamless data input.
- **Delta Lake Integration**: Ensures reliable, scalable, and ACID-compliant data storage.
- **Data Transformation Pipelines**: Implements Silver-layer transformations for cleaned and structured data.
- **Lookup Tables & Enhancements**: Includes supporting lookup tables for enriched data insights.
- **Notebook-Based Workflow**: Modular and reusable Databricks notebooks for efficient data processing.
- **Databricks Job Execution**: Automates workflow execution through scheduled Databricks jobs.

## Repository Contents

- **1_autoloader.dbc** – Automates the ingestion of Netflix datasets.
- **Silver.dbc** – Transforms raw data into structured Silver-layer data.
- **delta_notebook.dbc** – Implements Delta Lake for optimized storage and querying.
- **lookup.dbc** – Stores lookup tables for reference data.
- **lookupnotebook.dbc** – Handles data lookups and reference mappings.
- **silver_data_transformationNotebook.dbc** – Processes and refines Silver-layer data.
- **Azure Databricks Jobs Folder** – Contains job configurations and execution logs.

## Getting Started

### Prerequisites

- An **Azure Subscription** with Databricks workspace.
- Basic knowledge of **Azure Data Engineering** and **Apache Spark**.
- Configured **Azure Storage Account** for data access.
- Permissions to access and manage **Databricks Jobs**.

### Setup Instructions

1. **Clone the Repository**:
   ```sh
   git clone https://github.com/Seemasanga11/Netflix_Azure_project.git
   ```
2. **Import Notebooks into Databricks**:
   - Navigate to Databricks workspace.
   - Import `.dbc` files from the repository.
3. **Configure Azure Services**:
   - Ensure proper access to Azure Storage, Delta Lake, and Databricks Jobs.
4. **Run Notebooks in Sequence**:
   - Start with `1_autoloader.dbc` for data ingestion.
   - Process Silver-layer transformations using `Silver.dbc`.
   - Leverage Delta Lake using `delta_notebook.dbc`.
5. **Set Up Databricks Jobs**:
   - Use `Azure Databricks Jobs` to automate the execution of notebooks.
   - Monitor job runs and optimize performance using Databricks UI.

## Job Execution (Azure Databricks)

- **Scheduling**: Automate workflows using Databricks Jobs.
- **Monitoring**: Track execution logs and optimize data pipelines.
- **Scaling**: Leverage cluster configurations for performance tuning.

## Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request with enhancements.

## License

This project is licensed under the **MIT License**.



