# Elevate_labs_task_7

# 🧮 Task 7 - Sales Summary using SQLite and Python

## 📌 Objective
Analyze a sales dataset using **SQL in Python** and generate a basic **sales summary** with:
- Total quantity sold per product
- Total revenue per product

## 🛠 Tools Used
- Python (Google Colab)
- SQLite (`sqlite3`)
- pandas
- matplotlib

## 📁 Dataset
The dataset used was `sales_data_sample.csv`, which contains product-level sales data.

## 🔧 What I Did
1. Uploaded the CSV file to Google Colab.
2. Loaded the dataset into a pandas DataFrame.
3. Created a **SQLite database** and inserted the data as a table.
4. Ran a SQL query to calculate:
   - Total quantity sold (`SUM(QUANTITYORDERED)`)
   - Total revenue (`SUM(QUANTITYORDERED * PRICEEACH)`)
5. Printed the result and plotted a **bar chart** showing revenue per product.
6. Saved the chart as `sales_chart.png`.

## 📊 Sample Output
```python
  product  total_qty     revenue
0  S10_1678        230     33089.80
1  S10_1949        200     30800.00
...
