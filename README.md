# sales_data
Creating sales_data end-to-end project using Medallion Architecture (Bronze, Silver, Gold) layers.

SOURCE- AzureSQLDB (Gets the data from Github)

AZURE DATA FACTORY- Orchestrates the Data Ingestion Pipeline.

                  - Handles Incremental Data.
                  
                  - Ingests the data into ADLS bronze folder.
