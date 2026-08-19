# Bike Sales Analysis Dashboard 
# Project Overview

This project focuses on analyzing customer demographic data to identify trends and patterns that influence bike purchases. By transforming raw data into an interactive Excel dashboard, I provide insights into how factors like income, age, and commute distance impact a customer's likelihood of buying a bike.

Dataset
The dataset contains information on 1,000 customers, including:

Demographics: Marital status, Gender, Income, Education, Occupation.
Logistics: Commute distance, Region, Home ownership, Number of cars.
Target Variable: Whether or not the customer purchased a bike.
Key Workflow
1. Data Cleaning
Removed Duplicates: Ensured each customer record was unique.
Standardized Values: Used "Find and Replace" to change shorthand (e.g., "M" to "Married", "S" to "Single", "F" to "Female") for better readability.
Data Formatting: Adjusted currency and numerical columns for consistency.
2. Data Transformation (Processing)
Nested IF Statements: Created a new Age Brackets column to categorize customers into "Adolescent," "Middle Age," and "Old" to allow for better demographic grouping.
3. Data Analysis (Pivot Tables)
Calculated average income per purchase.
Analyzed customer commute distances.
Segmented sales by age groups and regions.
4. Data Visualization (Dashboard)
Pivot Charts: Created Clustered Column and Line charts to visualize trends.
Interactive Slicers: Added filters for Marital Status, Education, and Region, allowing users to interact with the data in real-time.
Tools Used
Microsoft Excel:
Pivot Tables & Pivot Charts
Nested IF Functions
Slicers for Interactivity
Data Cleaning & Normalization
