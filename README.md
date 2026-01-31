# Food Delivery Data Integration & Analysis

## Objective
The objective of this project is to combine transactional, user, and restaurant data available in CSV, JSON, and SQL formats into a single unified dataset for analysis.

## Datasets Used
- orders.csv – Order transaction details
- users.json – User master data
- restaurants.sql – Restaurant master data

## Approach
1. Loaded data from CSV, JSON, and SQL formats using Python
2. Executed SQL script using SQLite
3. Performed LEFT JOINs to retain all order records
4. Cleaned and structured the final dataset

## Tools & Technologies
- Python
- Pandas
- SQLite
- Jupyter Notebook

## Output
- final_food_delivery_dataset.csv – Final merged dataset used for analysis
