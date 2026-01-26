# Swiggy Sales Analysis Project

## Project Description
This project analyzes Swiggy food delivery data to generate business insights using Python, SQL, and Power BI.  
The objective is to clean raw data, design a star schema model, and perform in-depth sales and customer behavior analysis to support data-driven decision-making.

---

## Tools & Technologies
- Python – Data cleaning, preprocessing, and validation  
- SQL – Data transformation and dimensional modeling (Star Schema)  
- Power BI – Dashboard creation and visual analytics  
- Excel – Initial data exploration  

---

## Data Cleaning & Validation

The raw dataset `swiggy_data` contains food delivery records across states, cities, restaurants, categories, dishes, and order details.

### Checks Performed
- Null value detection for key columns  
- Blank/empty value handling  
- Duplicate record detection  
- Duplicate removal using SQL window functions and Python filtering  

---
## Project Outcome

This project enables:
- Identification of high-performing cities and cuisines  
- Understanding customer spending behavior  
- Detection of seasonal and weekly demand patterns  
- Support for data-driven business strategies  
---

## Repository Structure

```
Swiggy-Sales-Analysis/
│
├── data/
│   └── swiggy_data.csv
│
├── python/
│   └── data_cleaning.py
│
├── sql/
│   ├── data_cleaning.sql
│   ├── star_schema.sql
│   └── business_queries.sql
│
├── powerbi/
│   └── swiggy_dashboard.pbix
│
└── README.md
```
