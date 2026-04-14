# Coffee Shop Sales Analysis

Exploratory data analysis on a coffee shop's daily sales data using Python.

## Tools Used
- Python, pandas, numpy, matplotlib, seaborn

## Dataset
50 orders across 16 days (Jan 2024) covering 4 drink types, 3 sizes, 3 baristas, and 2 payment methods. Dataset included missing values and duplicate rows that were handled during cleaning.

## What I Did

**Data Cleaning**
- Imputed missing `price` values with column mean
- Removed 2 duplicate rows using `drop_duplicates()`
- Parsed `date` column to datetime

**Feature Engineering**
- Created `revenue` column (`price × quantity`)
- Extracted `day_of_week` from date

**Analysis**
- Revenue breakdown by drink type, size, barista, and day
- Payment method distribution
- Top 3 highest revenue orders

## Key Findings
- **Card** was the most popular payment method
- **Monday** recorded the highest revenue day
- **B01** had the highest single-order revenue (₹16.5)
- Top 3 orders were all Cash payments with quantity of 3
- Cappuccino (Medium, qty 3) was the single highest revenue order at ₹16.5

