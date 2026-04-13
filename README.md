# new-wheels-sql-analysis
SQL analysis of a vehicle sales database to identify revenue trends, customer satisfaction patterns, and operational insights across quarters
# New Wheels SQL Analysis

## Overview
SQL-based analysis of a vehicle resale company's database to identify revenue trends, customer satisfaction patterns, and operational inefficiencies across four quarters. Built as a quarterly business report for executive leadership.

## Objective
Answer 10 business questions using SQL to assess company health, diagnose declining performance, and provide actionable recommendations to the CEO.

## Tools
SQL, SQLite

## Methodology
- Queried customer, order, and product tables across multiple joins
- Analyzed quarterly revenue trends using window functions and LAG for QoQ calculations
- Tracked customer satisfaction via CASE WHEN feedback mapping
- Measured shipping time degradation using date functions
- Cross-analyzed orders, revenue, feedback, and logistics to identify root causes

## Key Findings
- Revenue declined 41% from Q1 to Q4, representing approximately $16M in lost revenue
- Customer satisfaction dropped from 3.55 in Q1 to 2.40 in Q4
- Average shipping time tripled from 57 days in Q1 to 174 days in Q4
- By Q4, 59% of customer feedback was negative, up from 22% in Q1
- Chevrolet and Ford accounted for the majority of demand; Texas and California led customer concentration

## Business Recommendations
- Prioritize logistics and shipping time reduction as the primary driver of satisfaction decline
- Focus retention efforts on Texas, California, and Florida which represent the largest customer base
- Implement strategic discounting by brand rather than applying flat rates across all products

## Files
- `New_Wheels_Project__Manuel_Larios.pdf` — Full project including SQL queries, outputs, and business recommendations
