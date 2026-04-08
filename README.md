##Healthcare Analytics Dashboard | SQL + Excel + Power BI
>Project Overview

This project simulates a real-world Healthcare MIS / Data Analyst role, where raw hospital data is transformed into meaningful insights to support operational and strategic decision-making.

The goal is to analyze:

Hospital revenue performance
Doctor efficiency
Department contribution
Patient behavior patterns

> Business Problem:
Hospitals generate large volumes of data daily, but without proper analysis:
Revenue leakages go unnoticed
High-performing doctors aren’t identified
Inefficient departments remain hidden
Patient trends are not utilized

This project solves these problems by building a data-driven reporting system.

 Tools & Technologies:
SQL (PostgreSQL) → Data modeling, transformation, analysis
Microsoft Excel → Data cleaning & validation
Power BI → Interactive dashboard & visualization

 Dataset Description

The dataset includes:

Patient demographics (age, gender, city)
Doctor and department details
Admission & discharge records
Treatment cost and hospital stay duration

 Data Modeling Approach:

Raw data was first stored in a staging table and then normalized into:

patients → Unique patient information
departments → Department mapping
doctors → Doctor details linked to departments
admissions → Transaction-level hospital data


This structure improves:

Query performance
Data consistency
Scalability
 Key Analysis & Insights
🔹 1. Hospital Performance
Total Revenue Generated
Average Length of Stay
🔹 2. Monthly Trends
Admission trends using time-based aggregation
Helps identify seasonality patterns
🔹 3. Department Contribution
Revenue by department
% contribution using window functions
🔹 4. Doctor Performance
Revenue generated per doctor
Patient load handled
Top 5 doctors ranked using SQL RANK()
🔹 5. Efficiency Metrics
Average stay per department
Helps identify operational inefficiencies
🔹 6. Repeat Patient Analysis
Identifies patients with multiple visits
Useful for understanding chronic care demand




Power BI Dashboard:

The dashboard provides a clear and interactive view of hospital performance:

Key Features:
KPI Cards (Revenue, Patients, Avg Stay)
Doctor Ranking Visualization
Department-wise Revenue Breakdown
Monthly Admission Trends
Interactive Filters (Department, Gender, City)


> Key Business Insights
A small group of doctors contributes to a large portion of revenue
Some departments generate high revenue but have longer patient stays
Repeat patients indicate ongoing treatment demand
Admission trends show potential seasonality


What This Project Demonstrates:
Strong SQL fundamentals (joins, aggregations, window functions)
Real-world data modeling
Business-focused analysis
Dashboard storytelling skills
Job-ready MIS / Data Analyst capabilities


> About Me
Rooney Nanda
Aspiring Data Analyst skilled in SQL, Excel, and Power BI
Focused on building real-world, business-driven projects
