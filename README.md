# Azure Synapse Medallion Pipeline

Data warehouse built with Azure Synapse Analytics implementing medallion (Bronze/Silver/Gold) architecture.

## Architecture

**Bronze Layer:** Raw data ingestion (immutable)  
**Silver Layer:** Cleaned data  
**Gold Layer:** Analytics-ready star schema for BI  

## Tech Stack

- Azure Synapse Analytics
- PySpark Notebooks
- Azure Data Lake Gen2
- Delta Lake / Parquet
- Git version control
