🍽️ Restaurant & Consumer Data Analysis using SQL
📌 Project Description

The restaurant industry produces a large amount of data related to customers, restaurants, cuisines, and ratings. Managing and analyzing this data effectively is important to understand customer behavior and evaluate restaurant performance.

This project focuses on building a relational database using SQL to analyze consumer demographics, food preferences, and restaurant ratings. The dataset represents a real-world restaurant recommendation and review system. By using SQL queries, the project extracts meaningful insights that can help businesses make better decisions.

🎯 Problem Statement

In a competitive restaurant environment, understanding customer preferences and restaurant performance is essential. This project aims to design and implement a structured SQL database that analyzes consumer details, preferred cuisines, and restaurant ratings. Using advanced SQL queries, the system identifies trends such as top-rated restaurants, customer behavior patterns, and cuisine popularity to support data-driven decision-making.

🛠️ Tools & Technologies

Database: MySQL

Query Language: SQL

Tool Used: MySQL Workbench

Dataset Format: CSV files

🗂️ Database Tables

The project consists of the following tables:

consumers – Stores consumer demographic information

consumer_preferences – Stores preferred cuisines of consumers

restaurants – Stores restaurant details such as location and services

restaurant_cuisines – Links restaurants with their cuisines

ratings – Stores ratings given by consumers to restaurants

These tables are connected using primary keys and foreign keys to maintain data integrity.

📥 How to Import CSV Files into MySQL

Open MySQL Workbench

Create and select the database

Create tables using the provided SQL script

Right-click on a table → Table Data Import Wizard

Select the corresponding CSV file

Complete the import steps

Repeat for all tables

🔍 SQL Concepts Used

SELECT & WHERE clauses

INNER JOIN and subqueries

GROUP BY & HAVING

Common Table Expressions (CTEs)

Window Functions (RANK, ROW_NUMBER, AVG OVER)

Views

Stored Procedures

📊 Key Analysis Performed

Identified highly rated restaurants by cuisine and city

Analyzed consumer behavior based on age, occupation, and budget

Studied cuisine preferences and popularity

Ranked restaurants and consumers using ratings

Created reusable views and dynamic stored procedures

⚠️ Challenges Faced

Designing a normalized database structure

Handling multiple cuisines and preferences

Writing complex JOIN and nested queries

Implementing window functions correctly

📈 Key Outcomes

Better understanding of customer preferences

Identification of top-performing restaurants

Clear insights into restaurant ratings and service quality

Practical application of advanced SQL concepts

👨‍💻 Contributors
Purushottam Kumar
Project Guide: Manohar Chary V

✅ Conclusion

This project demonstrates how SQL can be used to design a relational database and perform advanced data analysis. The insights derived from this system can help restaurants improve customer satisfaction and optimize business strategies. It also strengthens practical understanding of SQL for real-world applications.



## 📊 Project Presentation

📄 [View Presentation (PDF)]("C:\Users\Purus\OneDrive\Desktop\SQL Project PPT.pdf")  


📁 Folder Structure

Restaurant-Consumer-SQL-Project/
│
├── 📁 dataset/
│   ├── consumers.csv
│   ├── consumer_preferences.csv
│   ├── restaurants.csv
│   ├── restaurant_cuisines.csv
│   └── ratings.csv
│
├── 📁 sql/
│   ├── 01_database_schema.sql
│   ├── 02_data_import.sql
│   ├── 03_basic_queries.sql
│   ├── 04_joins_subqueries.sql
│   ├── 05_advanced_queries.sql
│   ├── 06_views.sql
│   └── 07_stored_procedures.sql
│
├── 📁 documentation/
│   ├── ER_Diagram.png
│   ├── Project_PPT.pdf
│   └── SQL_Project_Report.pdf
│
├── 📁 screenshots/
│   ├── table_creation.png
│   ├── sample_queries.png
│   └── output_results.png
│
├── README.md
└── LICENSE

