# Car Dekho Data Analysis (MySQL)

## 📌 Overview
This project analyzes the **Car Dekho** dataset using MySQL queries to answer various business-related questions for a car dealership manager.

## 🛠 Skills Used
- MySQL (SELECT, WHERE, GROUP BY, HAVING, BETWEEN, IN)
- Data filtering and aggregation
- Business insights extraction

## 📂 Files
- `car project.sql` — Contains all SQL queries used in the analysis.

## 📊 Key Insights
1. Total cars available in each year from 2015 to 2023.
2. Breakdown of cars by fuel type (Petrol, Diesel, CNG) for each year.
3. Identification of years with more than 500 or fewer than 500 cars.
4. Year-wise counts for specific years such as 2020, 2021, 2022, and 2023.
5. Complete list of cars available between 2015 and 2023.

## 🔍 Example Queries
```sql
-- Total cars available in 2023
SELECT COUNT(*) 
FROM `car dekho` 
WHERE year = 2023;

-- Number of diesel cars in 2020
SELECT COUNT(*) 
FROM `car dekho` 
WHERE year = 2020 AND fuel = "diesel";
