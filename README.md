# Olivia's Home Sales Assignment
This repository contains the code and results for the Module 22 Challenge, which focuses on using SparkSQL to analyze home sales data. The challenge involves creating temporary views, partitioning the data, caching and uncaching a temporary table, and verifying the cache status.
## UofT Data Analytics Bootcamp Module 22 Challenge

### Table Of Contents
1. [Instructions](#instructions)
2. [Requirements](#requirements)

## Instructions
1. Clone this repository to your local machine.
2. Rename the `Home_Sales_starter_code.ipynb` file to `Home_Sales.ipynb`.
3. Ensure that you have the necessary PySpark SQL functions installed for this assignment.
4. Run the `Home_Sales.ipynb` notebook to execute the SparkSQL code and obtain the results.
5. The notebook performs the following tasks:
    - Reads the `home_sales_revised.csv` data into a Spark DataFrame.
    - Creates a temporary table called `home_sales`.
    - Answers the provided questions using SparkSQL queries.
    - Caches the `home_sales` temporary table and checks its cache status.
    - Executes a query on the cached data and compares the runtime with the uncached runtime.
    - Partitions the data by the `date_built` field and reads the formatted parquet data.
    - Creates a temporary table for the parquet data.
    - Executes a query on the parquet temporary table and compares the runtime with the uncached runtime.
    - Uncaches the `home_sales` temporary table and verifies its cache status.
6. Once you have run the notebook and reviewed the results, you can download the modified `Home_Sales.ipynb` file and upload it to your GitHub repository named "Home_Sales".

## Requirements
The following requirements are fulfilled by the code in this repository:
- A Spark DataFrame is created from the dataset.
- A temporary table of the original DataFrame is created.
- Queries are written to calculate the average price for different scenarios and round off the results.
- The view rating for homes costing more than or equal to $350,000 is determined, and the runtime of the query is calculated.
- The temporary table is cached and validated.
- The query from step 6 is executed on the cached table, and the runtime is computed and compared with the uncached runtime.
- The home sales dataset is partitioned by the `date_built` field, and the formatted parquet data is read.
- A temporary table is created for the parquet data.
- The query from step 6 is executed on the parquet temporary table, and the runtime is computed and compared with the uncached runtime.
- The `home_sales` temporary table is uncached and verified.
Please note that a Spark environment is required to run the code successfully.

[Back To Top](#olivias-home-sales-assignment)