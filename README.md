# Python Data Analysis: Sales and Revenue Insights
This project demonstrates a fundamental data analysis workflow using Python and several key libraries. The goal is to perform data cleaning, transformation, and exploratory analysis on a sales dataset to answer specific business questions.

## Project Objective
The primary objective of this script is to analyze a sales dataset (kiwilytics_orders.csv) to derive key insights, including:

1- Calculating the total revenue.

2- Identifying the highest-selling product.

3- Determining the customer with the highest total spending.

## Data Preparation and Transformation
- The analysis begins with a series of data cleaning and preparation steps to ensure the data is reliable for analysis:

- The dataset is loaded and a data quality check is performed to identify null values and duplicates.

- Null values in the unit_price column are filled with the mean unit price for each corresponding product.

- The order_date column is converted to a datetime format for proper handling.

- A new column, total_price, is calculated by multiplying quantity by unit_price.

## Key Insights
The following key metrics were extracted from the dataset:

- Total Revenue: The sum of all total_price values.

- Highest Product Quantity Sold: The product with the highest total quantity sold.

- Highest Customer Spending: The customer who spent the most money in total.

## Technologies Used
- Python: The core programming language for the analysis.

- Pandas: Used for data manipulation, cleaning, and analysis.

- NumPy: Used for numerical operations.

- Matplotlib: Used for data visualization (though not explicitly used for plotting in the provided script, it is imported).

