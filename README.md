# Northwind DBT Project



### Overview
The project demonstrates a robust implementation of data modeling using DBT, incorporating staging, warehouse, and analytics layers to buid a dimensional data warehouse.


### Project structure
Some of the key steps involved in the project include requirements gathering, data profiling, Bus Matrix, conceptual modeling, architecture design, source-to-target mapping, logical and physical model design, staging and data warehouse layers, analytics OBT, debugging, and testing. These steps are not exhaustive and do not necessarily follow a strict order, as I had to iterate and revisit different stages throughout the process.

#### Staging Layer (staging):
- Raw data from the Northwind database is cleaned and standardized.
- Tables are named using the prefix stg_ (e.g., stg_orders, stg_customers).

#### Warehouse Layer (warehouse):

- The staging data is transformed into intermediate models for analytical readiness.
- Tables represent core business entities (e.g., dim_product, dim_customer, fact_sales).

#### Analytics Layer (analytics):
- Final models designed for specific analytics use cases.
- Examples include product inventory, customer and sales overview reports.



### Key Features
- Database: Northwind.
- Tools Used:
  - DBT: For data transformation and modeling.
  - BigQuery: As the underlying data warehouse.
- Techniques Implemented:
  - Data cleaning and deduplication.
  - Dimensional modeling with fact and dimension tables.
  - Use of macros and tests for quality assurance.



### Resources:
- Learn more about dbt (https://docs.getdbt.com/docs/introduction)
- Northwind - The Northwind database is a sample relational database created by Microsoft. It was originally designed as part of their Access database product to demonstrate database concepts and functionalities.
- BigQuery (https://cloud.google.com/bigquery)
