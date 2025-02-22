# Home_Sales
# Home Sales Analysis
This challenge involves analyzing home sales data using PySpark and SparkSQL. The dataset is read from an AWS S3 bucket. It involves using Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

The environment used to complete this challenge was Google Colab.

Tasks Performed
	1.	Load dataset into a Spark DataFrame.
	2.	Create a temporary table (home_sales).
	3.	Using SparkSQL, run SQL queries to compute average home prices based on various criteria.
	4.	Cache and verify table caching for improved performance.
	5.	Measure query runtime before and after caching.
	6.	Partition dataset by date_built to improve query performance.
	7.	Compare execution times for different optimization strategies.
	8.	Uncache table and verify.