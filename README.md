# Task 7: Basic Sales Summary using SQLite and Python

This project performs a basic sales data analysis using a small SQLite database and Python. The output includes total quantity sold and total revenue for each product, displayed in both text and a bar chart format.

## 📌 Objective

- Use SQL queries inside Python to pull sales info (total quantity and revenue)
- Display results using print statements
- Visualize revenue per product using a bar chart

## 🛠️ Tools Used

- Python (sqlite3, pandas, matplotlib)
- SQLite (built-in)
- Google Colab (for writing and running the code)

## 📂 Files

- `sales_data.db` - SQLite database with a single `sales` table
- `Task7.ipynb` - Google Colab notebook with full code

## 🧾 Steps Performed

1. Created and connected to a SQLite database (`sales_data.db`)
2. Created a `sales` table with sample data
3. Inserted sample sales records (product, quantity, price)
4. Queried total quantity and revenue per product using SQL
5. Loaded SQL result into pandas and printed it
6. Plotted a bar chart of revenue per product using matplotlib
7. Saved and optionally downloaded the chart as `sales_chart.png`

## 📊 Sample Output

| Product     | Total Quantity | Revenue  |
|-------------|----------------|----------|
| Laptop      | 8              | 6400     |
| Smartphone  | 22             | 13200    |
| Tablet      | 12             | 3600     |

## 📉 Chart

![Revenue Chart](sales_chart.png)

## ✅ Outcome

- Learned how to write basic SQL queries using `sqlite3`
- Practiced importing SQL data into pandas
- Performed a simple sales summary
- Created and saved a basic sales chart

---

