# Cards-Issuance-Disparity

This project presents a SQL Server solution for a scenario frequently encountered in financial data analytics and technical interviews at JPMorgan Chase: calculating the disparity between the highest and lowest monthly issuance counts for each credit card, and ranking the cards based on this difference. The repository includes a realistic sample dataset containing credit card names, issuance volumes, and corresponding months and years. To solve the problem, the SQL `GROUP BY` clause is used in conjunction with the `MAX()` and `MIN()` aggregate functions; this allows for a dynamic comparison of the peak and lowest monthly values ​​for each individual card, with the resulting differences then sorted in descending order using `ORDER BY ... DESC`. The provided script covers the entire process: setting up the database schema, loading the sample data, and executing the specific query required to achieve the target output.

# This query algorithm was developed entirely through my own efforts.

Best regards,

# Azat Hallyyev

2nd-Year Student, Management Information Systems, Istanbul Gelişim University

# Data Analytics and Software Developer
