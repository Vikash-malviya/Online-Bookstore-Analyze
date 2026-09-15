# Online-Bookstore-Analyze
This project focuses on analyzing an Online Bookstore database using SQL to extract meaningful insights about sales, customer behavior, and book performance. The goal of the project is to demonstrate practical SQL skills used in real-world data analyst roles. also there is a step-by-step workflow of doing analysis using six-phases Ask-Prepare-Process-Analyze-Share-Act

📚 Online Bookstore Data Analysis (SQL Project)
📌 Project Overview

This project focuses on analyzing an Online Bookstore database using SQL to extract meaningful insights about book sales, customer behavior, and overall business performance.

The dataset simulates a real-world online bookstore system with information about books, customers, and orders. Using SQL queries ranging from basic to advanced level, the project answers important business questions and identifies patterns in sales and customer activity.

The goal of this project is to demonstrate practical SQL skills and data analysis techniques used by data analysts in real-world business environments.

🗂 Dataset Description

The project uses three datasets representing the core operations of an online bookstore.

## 🗂 Dataset Description

### 📚 Books
Contains information about the books available in the store.

- **Book_ID** – Unique identifier for each book  
- **Title** – Name of the book  
- **Author** – Author of the book  
- **Genre** – Category or genre of the book  
- **Published_Year** – Year the book was published  
- **Price** – Price of the book  
- **Stock** – Number of copies available in inventory  

---

### 👥 Customers
Stores information about bookstore customers.

- **Customer_ID** – Unique identifier for each customer  
- **Name** – Customer's full name  
- **Email** – Customer's email address  
- **Phone** – Contact number  
- **City** – City where the customer lives  
- **Country** – Country of the customer  

---

### 🛍 Orders
Represents purchase transactions made by customers.

- **Order_ID** – Unique identifier for each order  
- **Customer_ID** – ID of the customer who placed the order  
- **Book_ID** – ID of the book purchased  
- **Order_Date** – Date when the order was placed  
- **Quantity** – Number of books purchased in the order  
- **Total_Amount** – Total price paid for the order  

#🧠 SQL Analysis

The project includes basic to advanced SQL queries to analyze bookstore data.

## 📊 SQL Analysis

### 🔹 Basic Analysis
- Retrieve books from specific genres  
- Find books published after a certain year  
- Identify customers from specific countries  
- Calculate total stock available  
- Find the most expensive book  

### 🔹 Advanced Analysis
- Calculate total revenue generated  
- Find the most frequently ordered books  
- Analyze book sales by genre  
- Identify top spending customers  
- Calculate remaining stock after orders  

# 📊 Key Insights

📚 The bookstore offers books across multiple genres, allowing readers with different interests to explore a wide catalog.

📦 Some books have low remaining stock, which may indicate high demand and the need for timely restocking.

👥 Customer data shows buyers from multiple cities and countries, highlighting a geographically diverse customer base.

🛒 Several customers placed multiple orders, suggesting repeat purchasing behavior and potential loyal customers.

📈 Sales analysis indicates that a small number of books generate a large portion of total sales, revealing bestseller trends.

🏆 Certain authors contribute significantly to total sales, showing strong reader demand for their work.

#💡 Business Recommendations

🚀 Monitor inventory levels regularly and restock high-demand books to avoid stock shortages.

🎯 Develop loyalty programs or targeted offers for repeat customers to increase retention.

📊 Focus marketing campaigns on best-selling books, popular authors, and high-performing genres to drive revenue growth.

## 📂 Project Files

| File Name | Description |
|-----------|-------------|
| Books.csv | Dataset containing book information |
| Customers.csv | Dataset containing customer details |
| Orders.csv | Dataset containing order transactions |
| SQL Online Book Store project.sql | SQL queries used for analysis |
| SQL Questions Basic to Advance | List of SQL questions used in the project |
| SQL Project Presentation.pptx | Presentation explaining project insights |

 #🛠 Tools Used
1.SQL (PostgreSQL)
2.CSV datasets
3.GitHub
4.PowerPoint (for presentation)

#✨ Skills Demonstrated

✔ SQL Query Writing
✔ Data Cleaning and Data Exploration
✔ Joins and Table Relationships
✔ Aggregation Functions (SUM, AVG, COUNT)
✔ GROUP BY and HAVING
✔ Business Insight Generation



