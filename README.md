## Home_Sales.ipynb

The `Home_Sales.ipynb` notebook contains a series of tasks performed using PySpark to analyze home sales data. Here's an overview of the tasks covered:

1. **Data Loading and Preparation**: Loading the home sales data from a CSV file, creating a temporary view, and performing basic data exploration.
  
2. **Task 3**: Calculating the average price for a four-bedroom house sold per year, rounded to two decimal places.
  
3. **Task 4**: Determining the average price of a home for each year the home was built, specifically for homes with three bedrooms and three bathrooms, rounded to two decimal places.
  
4. **Task 5**: Finding the average price of a home for each year the home was built, considering homes with specific criteria (three bedrooms, three bathrooms, two floors, and greater than or equal to 2,000 square feet), rounded to two decimal places.
  
5. **Task 6**: Calculating the average price of a home per "view" rating, rounded to two decimal places, for homes with an average price greater than or equal to $350,000. Also measuring the runtime of the query.
  
6. **Task 7-9**: Caching the table, checking if it's cached, and executing the query again using the cached data, comparing the runtime with the uncached runtime.
  
7. **Task 10-12**: Partitioning the data by the "date_built" field and reading the parquet formatted data. Then, running the query again using the Parquet DataFrame and comparing the runtime with the cached runtime.
  
8. **Task 13**: Uncaching the temporary table and checking if it's no longer cached.

The notebook demonstrates how PySpark can be used to perform data analysis tasks efficiently, utilizing SparkSQL for querying and manipulating large datasets.
