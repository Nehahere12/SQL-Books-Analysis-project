BOOK SALES ANALYTICS & INVENTORY SYSTEM | MS SQL SERVER <br>
<br>
PROJECT OVERVIEW <br>
This project demonstrates data cleaning, exploratory analysis, and business intelligence extraction using Microsoft SQL Server on a relational Book Sales dataset. The system links three relational tables—Books, Customers, and Orders—to evaluate inventory health, customer demographics, ordering behavior, and overall revenue performance. <br>
<br>
DATASET STRUCTURE & RELATIONS <br>
- Books Table: Stores inventory details including Book ID, Title, Author, Genre, Published Year, Price, and Stock. Used for catalog and stock management. <br>
- Customers Table: Stores demographic attributes including Customer ID, Name, City, and Country. Used for geographic and customer segmentation. <br>
- Orders Table: Stores transaction records including Order ID, Book ID, Customer ID, Order Date, Quantity, and Total Amount. Links customers to books to evaluate purchasing behavior. <br>
<br>
DATA CLEANING & TRANSFORMATIONS <br>
- Deduplication: Identified and resolved duplicate entries across all three tables. <br>
- Null Handling: Cleaned missing and blank fields across datasets. <br>
- Numeric Standardization: Converted and standardized monetary columns (`Price` and `Total Amount`) to `DECIMAL(10,2)` for uniform financial reporting. <br>
- Relational Joins: Executed multi-table `JOIN` operations to merge catalog, demographic, and transactional attributes. <br>
<br>
CORE SQL OPERATIONS <br>
- Inventory Management: Evaluated genre availability, identified lowest-stock titles to prevent stockouts, and calculated post-sale remaining stock. <br>
- Price & Revenue Analytics: Ranked top-tier prices by genre, isolated high-value orders (`>$20`), and computed total cumulative revenue. <br>
- Customer Segmentation: Isolated geographic clusters (e.g., Canada, cities with spend `>$30`), identified repeat buyers, and ranked the Top 10 highest-spending customers. <br>
- Sales & Author Performance: Analyzed sales volume by genre, author popularity, and identified the most frequently ordered books. <br>
<br>
TECH STACK <br>
- Database Engine: Microsoft SQL Server (MS SQL) <br>
- Core Features: Data Types Casting, Aggregate Functions (`SUM`, `AVG`, `COUNT`), Grouping & Sorting (`GROUP BY`, `ORDER BY`), Multi-table Joins (`INNER JOIN`), Subqueries & Filters (`HAVING`, `WHERE`). <br>
