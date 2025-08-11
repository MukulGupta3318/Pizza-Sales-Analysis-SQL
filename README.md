# Pizza-Sales-Analysis-SQL
SQL-based data analysis of pizza sales, covering basic to advanced queries for business insights, built using MySQL.
# 🍕 Pizza Sales Analysis (MySQL)

This project analyzes pizza sales data using **MySQL** to extract meaningful business insights.  
It covers **Basic**, **Intermediate**, and **Advanced** SQL queries — from simple aggregations to category-based revenue breakdowns.

---

## 📂 Project Structure
The project is divided into three difficulty levels:

### **Basic Queries**
- Retrieve the total number of orders placed.
- Calculate the total revenue generated from pizza sales.
- Identify the highest-priced pizza.
- Identify the most common pizza size ordered.
- List the top 5 most ordered pizza types along with their quantities.

### **Intermediate Queries**
- Join necessary tables to find the total quantity of each pizza category ordered.
- Determine the distribution of orders by the hour of the day.
- Find the category-wise distribution of pizzas.
- Group orders by date and calculate the average number of pizzas ordered per day.
- Determine the top 3 most ordered pizza types based on revenue.

### **Advanced Queries**
- Calculate the percentage contribution of each pizza type to total revenue.
- Analyze the cumulative revenue generated over time.
- Determine the top 3 most ordered pizza types based on revenue for each pizza category.

---

## 🛠️ Tools & Technologies
- **MySQL** — For writing and executing queries.
- **SQL Joins, Aggregations, and Window Functions** — To handle complex queries.
- **Data Analysis Techniques** — To generate insights from raw transactional data.

---
<h2>⚡ Challenges Faced</h2>
<ul>
  <li><strong>Data Cleaning Requirements:</strong> Normalizing inconsistent pizza names and categories before analysis to ensure accurate aggregations.</li>
  <li><strong>Complex Joins:</strong> Combining multiple tables (orders, items, products, timestamps) required careful join logic to avoid duplication and ensure correctness.</li>
  <li><strong>Time-Based Analysis:</strong> Converting and handling timestamp formats for hour-of-day and date-based aggregations required additional preprocessing.</li>
  <li><strong>Query Optimization:</strong> Advanced aggregations and window functions initially performed slowly; indexing and query refactoring were needed for acceptable runtimes.</li>
</ul>

<h2>✅ Conclusion</h2>
<p>
  This project highlights how MySQL can transform raw transaction data into actionable business insights. By applying a mix of basic, intermediate, and advanced SQL techniques, we identified top-selling pizzas, peak ordering hours, and category-level revenue contributions. These results provide a strong foundation for building visual dashboards and automating sales reporting to support data-driven decisions.
</p>
