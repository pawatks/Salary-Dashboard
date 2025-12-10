# Salary Insights Dashboard (Excel Analytics Project)

A complete end-to-end transformation of a raw collaboration dataset into an interactive Excel dashboard for analyzing salary trends by job title, location, job type, and platform. This project demonstrates strong data cleaning, formula engineering, dynamic arrays, and dashboard design — critical skills for junior and mid-level data analyst roles.

<p align="center">
  <img src="images/dashboard.png" width="800">
</p>

## Project Purpose
The objective of this project was to take an unstructured dataset and convert it into a professional, interactive Excel dashboard that allows users to:
- Compare salaries across countries, job titles, and job types
- Calculate median salaries dynamically
- Filter results using validated dropdown selectors
- Analyze job markets across multiple recruitment platforms
- Display insights clearly using clean Excel UI design

## Challenges in the Raw Dataset (dataset.xlsx)
The original dataset contained multiple issues:
- Inconsistent job titles
- Missing / zero salary entries
- Mixed country naming conventions
- No structured categories for job type or platform
- No easy way to aggregate or analyze salaries
- No automated calculations
- Data scattered across multiple columns

## What I Built in the Final Dashboard (Salary_insight.xlsx)
### Cleaned and Validated Dataset
I prepared the data by:
- Normalizing job titles
- Removing invalid salary entries (0 or blank)
- Standardizing country names
- Creating data validation lists for dropdown filters
- Structuring the data into analysis-ready tables
- Preparing lookup tables for Country, Type, and Platform

### Dynamic Calculation Engine (Excel Formulas)
To produce real-time salary insights, I built a calculation engine using modern Excel functions:
- FILTER()
- MEDIAN()
- Spill ranges (#)
- UNIQUE()
- SORT()
- XLOOKUP() / VLOOKUP()
- Data Validation

### Salary Calculation Logic
1. Match Job Title  
2. Match Country  
3. Match Job Type  
4. Salary must be greater than 0  
5. Return all matching rows in a filtered array  
6. Apply MEDIAN()  

### Interactive Dashboard Design
The final dashboard includes:
- Dropdown filters
- Auto-calculating salary insights
- Dynamic table outputs
- Summary metric sections
- Clean, readable UI

## Key Skills Demonstrated
- Data wrangling
- Excel formula engineering
- Dashboard design
- Business interpretation

## Repository Structure
dataset.xlsx — Final dashboard  
salary_insight.xlsx — Raw dataset  
README.md — Documentation
