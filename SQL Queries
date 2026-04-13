-- Total Sales
SELECT SUM(Sales) AS total_sales
FROM superstore;

-- Sales by Category
SELECT Category, SUM(Sales) AS total_sales
FROM superstore
GROUP BY Category
ORDER BY total_sales DESC;

-- Profit by Region
SELECT Region, SUM(Profit) AS total_profit
FROM superstore
GROUP BY Region;

-- Top Customers
SELECT Customer_Name, SUM(Sales) AS total_sales
FROM superstore
GROUP BY Customer_Name
ORDER BY total_sales DESC
LIMIT 10;
