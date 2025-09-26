# Ecommerce Database SQL Analysis

## 📌 Project Overview
This project involves creating and analyzing an **Ecommerce database** using SQL. The main objective was to practice **data manipulation, querying, aggregation, joins, subqueries, and creating views** to extract meaningful business insights from structured data.

The database contains tables for **customers, cities, products, categories, orders, ordered products, and reviews**.

---

## 🛠️ Tools & Technologies
- **Database:** MySQL  
- **Tools Used:** MySQL Workbench / DBeaver / Any SQL client  
- **SQL Concepts Applied:**  
  - SELECT, WHERE, ORDER BY, GROUP BY  
  - INNER JOIN, LEFT JOIN  
  - Subqueries  
  - Aggregate functions: SUM, AVG, COUNT  
  - Views for analysis  
  - Indexing for query optimization

---

## 📁 Database Schema
**Tables Created:**
1. **City:** CityID, CityName, Country  
2. **Customer:** CustomerID, FirstName, LastName, Email, Password, Contact, CityID  
3. **Category:** CategoryID, CategoryName  
4. **Product:** ProductID, ProductName, Price, CategoryID  
5. **Orders:** OrderID, CustomerID, OrderDate, TotalAmount  
6. **OrderedProduct:** OrderProductID, OrderID, ProductID, Quantity, Price  
7. **Review:** ReviewID, CustomerID, ProductID, Rating, ReviewText, ReviewDate  

All tables were populated with **15 sample records each**.

---

## 📊 Data Analysis Performed
The following steps were executed using SQL queries:

1. **Data Preview**
   - Displayed first 5 rows from each table to verify data insertion.

2. **Basic Queries**
   - Listed all customers along with their city names.  
   - Listed all products along with their categories and prices.

3. **Filtering**
   - Selected customers from specific cities.  
   - Filtered products above a certain price.

4. **Sorting**
   - Ordered products by price.  
   - Sorted orders by most recent dates.

5. **Aggregation**
   - Calculated total sales per product.  
   - Calculated average product ratings.  
   - Counted the number of orders per customer.

6. **Joins**
   - Combined orders with customer and product details.  
   - Used LEFT JOIN to display all customers including those with no orders.

7. **Subqueries**
   - Identified customers who spent more than the average.  
   - Found products that were never ordered.

8. **Views**
   - Created `CustomerOrderSummary` view to summarize total orders and spending per customer.

9. **Indexing**
   - Created indexes on frequently joined columns for query optimization.

---

## 📂 Deliverables
- **SQL File:** `Ecommerce_Analysis.sql` containing all queries.  
- **Database Schema and Sample Data:** SQL creation and insertion scripts.  
- **Screenshots:** Output of each query executed (for reporting purposes).  

---

## ✅ Outcome
- Successfully **created and populated the Ecommerce database**.  
- Executed **complex SQL queries** to analyze customer behavior, product performance, and order trends.  
- Gained hands-on experience in **SQL querying, aggregation, joins, subqueries, views, and optimization**.  

---

## 📌 Notes
- The database was designed for **learning and analysis purposes**.  
- All queries were tested and executed successfully in **MySQL**.
