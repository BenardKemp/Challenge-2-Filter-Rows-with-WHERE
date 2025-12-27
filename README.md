# SQL Beginner Challenge #2: Filter Rows with WHERE

**Difficulty:** Beginner  
**Estimated time:** 5–10 minutes  
**Concepts:** `WHERE`, filtering rows, conditions  

This challenge introduces the `WHERE` clause—one of the most important tools in SQL for narrowing down results to only the data you need.

---

## 🧠 The Problem

You’re working with the same `products` table from Challenge #1.

This time, the product manager only wants to see **products that belong to the `Accessories` category**.

Your task is to filter the rows **directly in SQL**, instead of filtering later in a spreadsheet or dashboard.

---

## 📊 Table Schema

### `products`

| Column Name | Type      | Description |
|------------|-----------|-------------|
| product_id | INTEGER   | Unique product ID |
| name       | TEXT      | Product name |
| category   | TEXT      | Product category |
| price      | DECIMAL   | Product price |
| stock_qty | INTEGER   | Units in stock |
| created_at | TIMESTAMP | Creation timestamp |

---

## 🧪 Sample Data

| product_id | name                 | category     | price  | stock_qty |
|-----------:|----------------------|--------------|-------:|----------:|
| 101 | Wireless Mouse      | Accessories | 24.99 | 120 |
| 102 | Mechanical Keyboard | Accessories | 89.00 | 45  |
| 103 | 27-inch Monitor     | Displays    | 229.99| 18  |
| 104 | USB-C Hub           | Accessories | 34.50 | 70  |
| 105 | Laptop Stand        | Workspace   | 39.99 | 32  |

---

## ✅ Requirements

Your query must:

- Return **only** products in the `Accessories` category
- Show the following columns:
  - `name`
  - `price`
  - `category`
- Use a `WHERE` clause
- Not use `SELECT *`
- Match the category value exactly

---

🧩 Expected Output
name	price	category
Wireless Mouse	24.99	Accessories
Mechanical Keyboard	89.00	Accessories
USB-C Hub	34.50	Accessories

---



## ✍️ Your Task

Write a SQL query that fulfills the requirements.

```sql
-- Write your query here

