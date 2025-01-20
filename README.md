# Home_Sales

## Table of contents

* [Overview](#Overview)
* [Key Objectives](#Key-Objectives)
* [Steps](#Steps)
* [Questions](#Questions)
* [References](#References)

## Overview

This challenge, use SparkSQL to determine key metrics about home sales data. Then create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

## Key Objectives

1. Loading home sales data from a CSV file stored in AWS S3. 
2. Processing and analyzing the data using PySpark.
3. Visualization and insights extraction related to real estate trends.

## Steps

1. Spark Environment Setup: Initializes a PySpark session.

2. Data Loading: Reads the home sales data from a CSV file in an S3 bucket.

3. Data Processing: Includes filtering, grouping, and summarizing operations on the dataset.

4. Cache the temporary table home_sales.

5. Check if the temporary table is cached.

6. Using the cached data, run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

7. Partition by the "date_built" field on the formatted parquet home sales data.

8. Create a temporary table for the parquet data.

9. Run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

10. Uncache the home_sales temporary table.

11. Verify that the home_sales temporary table is uncached using PySpark.

12. Download the Home_Sales.ipynb file.

## Questions

In case of any additional questions please visit my GitHub link: [Feda](https://github.com/Feda2020)

## References

* Xpert Learning (https://bootcampspot.com)