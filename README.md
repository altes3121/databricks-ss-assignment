# Pre-Interview Data Engineering Assignment

This repository contains my solution for the practical pre-interview assignment. 

## Project Overview
The objective of this assignment was to demonstrate hands-on skills in data ingestion, transformation, and SQL analysis using **Apache Spark (PySpark)** and **Databricks**.

* **Dataset:** Online Retail transactional data (real-world e-commerce dataset containing sales records).
* **Environment:** Databricks Community Edition.

## Completed Tasks
1. **Load & Explore:** Ingested the CSV data into a Spark DataFrame, analyzed the schema, calculated total row counts, and identified columns with missing values (`CustomerID` and `Description`).
2. **Transformations:** Formulated business logic justifications for handling missing data, engineered a new derived business metric column (`TotalAmount`), and filtered out operational noise (cancelled/invalid orders).
3. **SQL Analysis:** Registered a temporary view, built a complex aggregation query utilizing analytical SQL (`GROUP BY`, aggregate functions), and saved the consolidated results into a managed **Delta table**.

## How to Review
The complete workflow, code cells, execution outputs, and short analytical commentary are preserved in the attached `.dbc` archive. You can download the `Retail_Data_Project.dbc` file from this repository and import it directly into your Databricks workspace.
