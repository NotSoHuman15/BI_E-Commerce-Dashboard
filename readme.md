# E-Commerce Business Intelligence Dashboard

## Cleaning and Analyzing Raw E-Commerce Transaction Data to Improve Revenue Insight and Forecasting

### Academic Project | Business Intelligence (23UDSPEL4704) - TAE1

---

## Project Team

- **Kartik Bhat** (P23)
- **Sanjay Yadav** (P43)

**Institution:** G H Raisoni College of Engineering and Management, Pune  
**Department:** Computer Science & Engineering (Data Science)  
**Guide:** Mr. Chinmay Mukim  
**Academic Year:** 2026-2027

---

## Project Overview

This project demonstrates a complete Business Intelligence workflow, from raw data cleaning to interactive dashboard creation. We work with the **Online Retail Dataset** (2010-2011) containing over 540,000 transactions with significant data quality issues.

## Dataset Download Link:

### Key Objectives:
1. Audit and document data quality issues in raw transactional data
2. Design and implement a systematic data cleaning pipeline
3. Build an interactive Power BI dashboard with 3 pages
4. Perform revenue forecasting using time-series analysis
5. Demonstrate measurable impact of data cleaning on analytical accuracy

---

## Project Highlights

### Data Quality Issues Addressed:
- **Missing Customer IDs:** 25% of records (~135,080 rows)
- **Duplicate Records:** 5,268 exact duplicates
- **Cancellations/Returns:** 10,624 return transactions (properly handled)
- **Invalid Values:** Zero prices, negative quantities, inconsistent formatting
- **Text Inconsistencies:** Case-sensitivity issues in product codes and descriptions

### Key Metrics (After Cleaning):
- **Total Records:** 524,878 transactions
- **Gross Revenue:** £10,642,110.80
- **Return Rate:** 8.6%
- **Unique Customers:** 4,372
- **Unique Products:** 3,684
- **Countries:** 38

---

## Technology Stack

### Data Processing & Analysis:
- **Python 3.10+**
  - pandas - Data manipulation
  - numpy - Numerical operations
  - matplotlib/seaborn - Visualizations
  - datetime - Time-series handling

### Business Intelligence:
- **Power BI Desktop** - Interactive dashboards
- **DAX** - 52 custom measures for calculations
- **Power Query** - Data transformation

### Version Control:
- **Git** - Version control
- **GitHub** - Repository hosting

---

## Project Structure