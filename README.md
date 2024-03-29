# Home Sales Analytics with Spark
Utilizing SparkSQL, I will analyze home sales data, establish temporary views, partition data, and manage caching of a temporary table. The challenge concludes with ensuring the table's uncaching is verified.

### Instructions

1: I'll rename the **Home_Sales_starter_code_colab.ipynb** file as **Home_Sales_colab.ipynb**.

2: Then, I'll import the necessary PySpark SQL functions for this project.

3: I'll read the **home_sales_revised.csv** data in the starter code into a Spark DataFrame.

4: Create a temporary table called **home_sales**.

5: I'll answer the following questions using SparkSQL:

  - What is the average price for a four-bedroom house sold for each year? Round off the answer to two decimal places.
  - What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off the answer to two decimal places.
  - What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off the answer to 
    two decimal places.
  - What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off the answer to two decimal places.

6: Cache my temporary table **home_sales**.

7: Check if my temporary table is cached.

8: Using the cached data, run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Then, I'll determine the runtime and compare it to uncached runtime.

9: Partition by the **"date_built"** field on the formatted parquet home sales data.

10: I'll create a temporary table for the parquet data.

11: Run the query that filters out the view ratings with an average price greater than or equal to $350,000. I'll determine the runtime and compare it to uncached runtime.

12: I'll uncache the **home_sales** temporary table.

13: I'll verify that the **home_sales** temporary table is uncached using PySpark.

14: Then I'll download my **Home_Sales_colab.ipynb** file and upload it into my **"Home_Sales"** GitHub repository.

***References***

Data for this dataset was generated by edX Boot Camps LLC.


