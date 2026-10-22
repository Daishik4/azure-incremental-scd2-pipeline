# Azure Incremental SCD2 Pipeline

Incremental ETL pipeline using Azure Data Factory and Databricks.
Loads only new/changed records (watermark), keeps full history with SCD Type 2 (Delta Lake MERGE),
and can be re-run safely without creating duplicates.

**Status:** work in progress — design and build in progress.
