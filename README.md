# Home_Sales
Use SparkSQL to determine key metrics about home sales data

In this challenge, you'll use your knowledge of SparkSQL to determine key metrics about home sales data. Then you'll use Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

Instructions:

Rename the Home_Sales_starter_code.ipynb file as Home_Sales.ipynb.

Import the necessary PySpark SQL functions for this assignment.

Read the home_sales_revised.csv data in the starter code into a Spark DataFrame.

Create a temporary table called home_sales.

Answer the following questions using SparkSQL:
        
    What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
    ![Question 1](https://github.com/user-attachments/assets/d8cfbe87-9945-474a-b05d-0dd97c341bba)
    What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
    Images/Question 2.png
    What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
    Images/Question 3.png  
    What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.
    Images/Question 4.png
Cache your temporary table home_sales.
Check if your temporary table is cached.
Images/Cache temp table.png
Using the cached data, run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
Images/Rating of 35000.png
Partition by the "date_built" field on the formatted parquet home sales data.

Create a temporary table for the parquet data.

Run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
Images/Parquet.png
Uncache the home_sales temporary table.

Verify that the home_sales temporary table is uncached using PySpark.
Images/Uncache temp table.png
Download your Home_Sales.ipynb file and upload it into your "Home_Sales" GitHub repository.
