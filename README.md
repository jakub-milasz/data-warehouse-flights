## Flights Data Warehouse - Medallion Architecture

This project presents a Data Warehouse solution built on the **Flights dataset**, designed using the **Medallion Architecture** approach. The pipeline follows a multi-layered structure to ensure data quality, scalability, and analytical readiness.

### Architecture Overview

The solution is organized into three core layers:

* **Bronze Layer**
  Raw data ingestion layer. The original Flights data is stored in its native format with minimal transformation, ensuring traceability and reproducibility.

* **Silver Layer**
  Cleaned and transformed data layer. This stage includes data validation, deduplication, schema standardization, and business rule implementation to prepare high-quality, structured datasets.

* **Gold Layer**
  Business-ready, aggregated data layer. Optimized tables are created for analytical and reporting purposes, supporting KPIs and performance analysis.

## ERD diagram

<p align="center">
  <img width="588" height="697" alt="image" src="https://github.com/user-attachments/assets/a55095a1-2231-42bd-a0b1-51734c6fc211" />
</p>


### Analysis

The project includes:

* Exploratory Data Analysis (EDA)
* Aggregations and business metrics
* Visualizations and charts presenting key insights (e.g., delays, cancellations, airline performance, seasonal trends)

### Testing

The pipeline incorporates data quality and transformation tests to ensure:

* Schema consistency
* Null and constraint validation
* Data integrity across layers
* Reliable metric calculations

### Technologies & Concepts

* Medallion Architecture (Bronze / Silver / Gold)
* ETL/ELT data processing
* Data validation & testing
* Analytical reporting and visualization
