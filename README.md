 Basic Sales Summary with Python & SQLite
This project is part of a Data Analyst internship assignment. The goal is to extract and visualize basic sales data using SQL inside Python.

📌 Objective
Connect to a SQLite database (sales_data.db)

Run SQL queries to summarize sales (total quantity sold, total revenue per product)

Visualize the results using a simple bar chart with matplotlib

🛠 Tools Used
Python (3.x)

SQLite (sqlite3)

Pandas

Matplotlib

🗃 Dataset
The database contains a single table named sales with at least the following columns:

product

quantity

price

🚀 What the Script Does
Connects to the sales_data.db database

Executes a SQL query to calculate:

Total quantity sold per product

Total revenue per product (quantity * price)

Loads results into a pandas DataFrame

Prints the results

Plots a simple bar chart showing revenue per product

📊 Output
Console output showing the summarized data

A bar chart (optionally saved as sales_chart.png)

🧠 Key Learnings
Writing and executing SQL inside Python

Using pandas for data manipulation

Basic data visualization with matplotlib
