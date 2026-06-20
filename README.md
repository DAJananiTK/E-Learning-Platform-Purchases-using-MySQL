# Online Learning Platform — SQL Database Analysis

SQL portfolio project demonstrating relational database design and business-focused data analysis using joins, aggregate functions, and grouped queries.

## Executive Summary

This project involves designing and analyzing a relational database for an online learning platform using SQL. A three-table schema — learners, courses, and purchases — was built to model enrollment and revenue data. Core SQL techniques such as joins, filtering, grouping, and aggregate functions were used to uncover learner engagement patterns, course performance, and revenue drivers.

## Business Objective

- Identify learners with and without purchase activity.
- Determine which courses have low or no enrollment.
- Measure total spending per learner to identify high-value customers.
- Evaluate revenue and engagement by course category.
- Detect learners purchasing across multiple categories.

## Dataset Overview

- **learners** — learner ID and profile details for each registered user.
- **courses** — course ID, course name, category, and price.
- **purchases** — transaction-level records linking learners to courses, including quantity purchased.

All three tables are connected through foreign keys, enabling relational, multi-table queries.

## SQL Techniques Used

- `SELECT`, `WHERE` for data retrieval and filtering
- `INNER JOIN`, `LEFT JOIN`, `RIGHT JOIN` across learners, courses, and purchases
- `GROUP BY`, `ORDER BY` for category-wise and ranked summaries
- Aggregate functions (`SUM`, `COUNT`) for spending, revenue, and learner counts

## Key Findings & Insights

- Designed a three-table relational database to support enrollment and revenue analysis.
- LEFT JOIN identified 3 learners with no purchase history: John David, Priya Sharma, and Emma Watson.
- RIGHT JOIN identified 3 unpurchased courses: Blockchain Basics, Digital Marketing Pro, and Tableau Masterclass.
- Ethan Miller was the highest-spending learner, due to multiple and higher-priced course purchases.
- Top 3 most purchased courses: Power BI Essentials, Java Programming, and Python for Data Science.
- Programming, Data Analytics, AI, and Design generated the highest revenue and learner engagement.
- 5 learners (Daniel Lee, Ethan Miller, Karthik Raj, Michael Scott, Rahul Verma) purchased courses across multiple categories, showing higher engagement.

## Conclusion

This project demonstrates practical, beginner-level SQL skills in relational database design and business-focused data analysis. Using joins, aggregate functions, and grouped queries, raw transactional data was converted into clear insights on learner behavior, course performance, and revenue drivers.

## Business Recommendations

1. Promote high-performing categories (Programming, AI, Data Analytics, Design) to grow revenue and engagement.
2. Introduce discounts, combo offers, and certification incentives for unpurchased courses.
3. Use purchase history to deliver personalized course recommendations.
4. Re-engage inactive learners through email campaigns, free trials, and limited-time offers.
5. Strengthen marketing visibility for low-performing or unpurchased courses.
6. Build dashboards and recurring reports to monitor learner behavior, revenue, and course performance.

## Tools Used

- SQL (joins, aggregate functions, grouping, sorting, relational schema design)
