# sql-projects
SQL project analyzing Netflix dataset with queries to filter movies/TV shows by date, category, and region. Demonstrates skills in filtering, grouping, aggregation, and reporting for real-world business insights.
# Netflix SQL Project

## Project Overview
This project analyses a Netflix dataset using SQL.  
It demonstrates filtering, grouping, and reporting queries to generate insights about movies and TV shows released on the platform.

---

## Key Features
- Filtered movies added in January 2024  
- Categorised content by type (Movie/TV Show)  
- Summarised results using `GROUP BY` and `HAVING`  
- Practised SQL operations like joins, constraints, and indexing (DDL + DML)

---

## 🔹 Sample Query
```sql
SELECT 
    show_title,
    season_title,
    date_added AS Released_JAN2024
FROM netflix
WHERE date_added BETWEEN '2024-01-01' AND '2024-01-31'
  AND category = 'Movie';
