# 🎧 Chinook Music Store SQL Analysis

This project analyzes the Chinook Music Store database using SQL and Python (via SQLite and pandas). The goal is to extract meaningful business insights such as top customers, best-selling albums, and monthly revenue trends. All queries were executed using SQLite in a Jupyter Notebook.

---

## 📁 Project Structure

| File | Description |
|------|-------------|
| `chinook_sales_analysis.ipynb` | Main notebook containing all queries and insights |
| `chinook.db` | SQLite database file |
| `README.md` | Project overview and explanation of each query |

---

## 📊 Analyses Performed

### 🎯 Query 1: Top 10 Customers by Total Spending

This query joins the `invoices` and `customers` tables to calculate how much each customer has spent in total.  
The result is sorted in descending order to find the top 10.

---

### 🎯 Query 2: Top 10 Artists by Sales

This query joins the `invoice_items`, `tracks`, `albums`, and `artists` tables to calculate total sales of each artist's tracks.  
The result is sorted in descending order to find the top 10.

---

### 🎯 Query 3: Most Popular Genres

This query joins the `genres`, `tracks`, and `invoice_items` tables to calculate sales count by genre.  
The result is sorted in descending order to find the top 10.

---

### 🎯 Query 4: Best-Selling Albums

This query joins the `albums`, `tracks`, and `invoice_items` tables to calculate total sales count for each album.  
The result is sorted in descending order to find the top 5.

---

### 🎯 Query 5: Top 10 Countries by Sales

This query uses the `invoices` table to calculate total sales count for each country.  
The result is sorted in descending order to find the top 10.

---

### 🎯 Query 6: Monthly Revenue Trend

This query uses the `invoices` table to calculate sales per month.  
It helps visualize monthly trends and identify peak business periods.

---

## 🛠️ Tools Used

- **SQLite**: Executing SQL queries on the Chinook database
- **Pandas**: Data formatting and manipulation
- **Jupyter Notebook**: Interactive analysis and presentation
- **DB Browser for SQLite** *(optional)*: Visual inspection of database structure

---

## 📂 About the Chinook Database

The Chinook database simulates a digital music store and includes:
- Customers and their invoices
- Employees and their reporting structure
- Albums, artists, tracks, and genres
- Invoice items representing purchases

It’s commonly used for SQL training and analytics.

---

## 🚀 Future Improvements

- Add data visualizations (bar charts, time series)
- Create dashboards using Streamlit or Tableau
- Add unit tests for automated query checks
- Extend analysis to include customer segmentation or retention

---

## 📬 Contact

Feel free to open an issue or fork this repository for collaboration or feedback.

> 🔗 **Explore the data. Learn SQL. Build insights.**
