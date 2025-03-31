# Ecommerce_data_analysis
 This project is designed to efficiently handle large datasets stored in CSV format by leveraging Pandas for data processing and PostgreSQL for database storage. The pipeline reads raw CSV data, creates a structured database table, and inserts the data using SQLAlchemy.

## Key Features
-  Load and process large CSV datasets using Pandas
-  Establish a connection with PostgreSQL using SQLAlchemy
-  Create and manage database tables dynamically
-  Append data efficiently to PostgreSQL
-  se Jupyter Notebook for data exploration and transformation

##  Workflow
**1.** Read the dataset from CSV files

**2.** Create a connection with PostgreSQL

**3.** Define and create database tables

**4.** Insert data into the database

**5.** Perform data analysis in Jupyter Notebook

 

## Use Case
This project is useful for data engineers, analysts, and developers who need to store and analyze large datasets in a structured database instead of handling them in raw CSV format. It is ideal for:

- Data warehousing

- ETL (Extract, Transform, Load) processes

- Business intelligence applications

## The dataset used in this project can be found [here](https://www.kaggle.com/datasets/psparks/instacart-market-basket-analysis/data)




<img src="https://github.com/Bhargav-data-driven/Ecommerce_data_analysis/blob/main/dm.jpg" alt="Data Architecture" width="600" height="500">


## Some Example  insights SQL

**1** Create a temporary table that joins the orders, order_products, and products tables to get information about each order, including the products that were purchased and their department and aisle information.

**2** Create a temporary table that groups the orders by product and finds the total number of times each product was purchased, the total number of times each product was reordered, and the average number of times each product was added to a cart.

**3** Create a temporary table that groups the orders by department and finds the total number of products purchased, the total number of unique products purchased, the total number of products purchased on weekdays vs weekends, and the average time of day that products in each department are ordered.

**4** Combine the information from the previous temporary tables into a final table that shows the product ID, product name, department ID, department name, aisle ID, aisle name, total number of times purchased, total number of times reordered, average number of times added to cart, total number of products purchased, total number of unique products purchased, total number of products purchased on weekdays, total number of products purchased on weekends, and average time of day products are ordered in each department.
