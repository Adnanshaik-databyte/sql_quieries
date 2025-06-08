# sql_quieries
# 📊  SQL for Data Analysis

## 🎯 Objective
Use SQL to extract insights and perform data analysis on a relational database.

---

## 🧰 Tools Used
- SQLite 
- DB Client:  SQLite CLI
- Dataset: https://www.kaggle.com/datasets/shrishtimanja/ecommerce-dataset-for-data-analysis 

---

## 📦 Dataset Overview
The dataset contains simulated e-commerce data, such as:
- Customers
- Orders
- Products
- Payments
- Shipping

> 💡 Replace with a short description of your actual dataset if different.

---

## 🚀 Tasks & Query Topics
![image](https://github.com/user-attachments/assets/9d48cff3-0ef4-4bf2-bf83-bb265405bfd2)

![image](https://github.com/user-attachments/assets/246444d2-78a1-4ca4-8056-3c2924b0b2c4)


### ✅ 1. Basic SQL Queries
- `SELECT`, `WHERE`, `ORDER BY`, `LIMIT`
- Filtering and sorting customer/order data
![image](https://github.com/user-attachments/assets/b00c12ba-48a1-4299-9cf0-73c990ed0c08)

![image](https://github.com/user-attachments/assets/0019c209-f00a-440f-9b77-15edd11cf9e5)

![image](https://github.com/user-attachments/assets/955f8b37-e47e-4489-8277-79aec8a284ea)



### ✅ 2. Grouping & Aggregation
- `GROUP BY`, `HAVING`
- Aggregate functions: `SUM`, `AVG`, `MAX`, `MIN`, `COUNT`
- Example: Total revenue per category
- 
![image](https://github.com/user-attachments/assets/e52fb45d-9520-4536-9c24-33c29eb05aaa)

- Total discount amount availed per location:
  
  ![image](https://github.com/user-attachments/assets/4b516b1c-1ecb-4432-9b40-d18befd00456)
  
- query gives you a full summary by category, showing:
  Total number of purchases (COUNT(*))
  Total revenue (SUM)
  Average revenue (AVG)
  Maximum revenue (MAX)
  Minimum revenue (MIN)
  
  ![image](https://github.com/user-attachments/assets/48e8159b-b766-42f7-962d-8a5cc74de540)




### ✅ 3. JOIN Operations
- `INNER JOIN`, `LEFT JOIN`, `RIGHT JOIN`
- Example: Combine order and customer details
  - New table Customers
    
![image](https://github.com/user-attachments/assets/c007d55a-d398-4f4a-a320-0d7bc5ad8ad2)

-INNER JOIN : Returns only the records where CID exists in both tables:
![image](https://github.com/user-attachments/assets/f8f7863e-621b-444e-b980-ae4e2527905f)

-LEFT JOIN : Returns all records from ecommerce (orders), and matching rows from customers.
![image](https://github.com/user-attachments/assets/e7c1c0f6-d89e-44ea-8ff9-2f44768ce4f1)

-RIGHT JOIN : Shows all customers, even if they didn’t place an order 
![image](https://github.com/user-attachments/assets/021920ff-03a1-4171-97e1-eb0c28748f21)





### ✅ 4. Subqueries
- Subquery in `WHERE`, `FROM`, or `SELECT` clause
- Example: Orders above average order value
- 
![image](https://github.com/user-attachments/assets/829985dd-7c02-44ec-9f15-6968d5edca56)

-Details of customers who purchased from "Electronics" category.

![image](https://github.com/user-attachments/assets/13b6e64a-e3ca-4795-9e15-4a361abd5b14)



### ✅ 5. Views
- Create views for reusable analysis
- Example: View for monthly sales summary



### ✅ 6. Indexing and Optimization
- Add `INDEX` to improve performance on large joins or filters
- Use `EXPLAIN` (optional) to evaluate query efficiency


---



