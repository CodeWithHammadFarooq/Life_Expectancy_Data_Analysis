🌍 Life Expectancy Data Cleaning and Initial Analysis
🔍 Project Overview
This project involves loading, inspecting, and cleaning a dataset related to global life expectancy indicators. The goal is to prepare the data for further analysis by handling missing or inconsistent entries and exporting a cleaned version of the dataset.

📂 Dataset
File Used: Life_Expectancy_Data_Analysis.csv

Source: Local CSV file

Features: Contains multiple features such as country names, life expectancy, GDP, schooling, health indicators, and more.

Target Objective: Clean and understand the dataset structure for future exploratory data analysis (EDA) and modeling.

🛠️ Tools & Libraries
Python

Pandas and NumPy for data processing and manipulation

📊 Data Exploration
Displayed the first few rows using head() to get a quick look at the data.

Used .shape to check the size (rows × columns).

Applied .info() to understand column data types and non-null values.

Identified missing values using .isnull().sum().

🧹 Data Cleaning
Replaced empty strings ("") and single spaces (" ") with "null" to make them easier to identify.

Applied .fillna("null") to fill remaining NaN values.

Verified the cleaned data by printing and re-checking null value counts.

💾 Data Export
Saved the cleaned dataset into a new file: cleaned_data.csv for downstream processing or visualization.

📌 Insights
The null value percentage per column was computed to identify data quality issues.

This cleaning phase sets the foundation for advanced analysis like:

Life expectancy trends by country

Correlation between health factors and life expectancy

Predictive modeling using machine learning

✅ Next Steps
Perform Exploratory Data Analysis (EDA) using charts and correlations

Handle "null" strings more meaningfully (e.g., convert them to actual NaN and impute values)

Build predictive models to estimate life expectancy

