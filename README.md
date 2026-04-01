# Global Layoffs Analysis Using SQL

## Overview
This project analyzes global layoff trends using SQL, focusing on data cleaning and exploratory data analysis. The analysis uncovers patterns across companies, industries, countries, and time using real-world data.

---

## Tools Used
- MySQL
- SQL (Aggregation, Joins, Window Functions)

---

## Project Structure
- `data/` → Raw dataset  
- `sql/` → Data cleaning and analysis scripts  
- `report/` → Final report with insights  

---

## Key Highlights
- Analyzed **400,000+ layoffs globally**
- Identified top companies like Amazon (18,150 layoffs) and Google (12,000)
- Found that the **United States accounts for ~66% of layoffs**
- Discovered **2022 as the peak year (162,034 layoffs)**
- Used **window functions (RANK, rolling totals)**

---

## Data Cleaning
Performed entirely in SQL:
- Removed duplicates using ROW_NUMBER()
- Standardized company names
- Handled NULL and missing values
- Converted date formats

---

## Analysis Performed
- Company-level layoffs analysis  
- Industry trends  
- Country-wise layoffs  
- Yearly and monthly trends  
- Stage-based analysis  
- Rolling totals and rankings  


---

## Key Insights
- Layoffs peaked in **2022 and remained high in 2023**
- Large tech firms led layoffs after over-expansion
- Several companies experienced **100% workforce reductions**
- Layoffs were widespread across industries
