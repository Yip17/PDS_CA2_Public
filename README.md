# HDB Resale Housing Affordability in Singapore

## Project Overview

This project analyses whether HDB resale flats in Singapore have become less affordable over time. Using real-world public datasets from Singapore government sources, the project performs data cleaning, exploratory data analysis (EDA), inflation adjustment, and visualisation using Python in Jupyter Notebook.

The analysis focuses on identifying long-term price trends, the impact of inflation, and factors that may have contributed to the sharp increase in HDB resale prices after 2020.

---

# Objectives

* Analyse historical HDB resale price trends in Singapore
* Investigate whether rising resale prices are caused mainly by inflation
* Compare nominal prices and inflation-adjusted real prices
* Identify possible reasons behind recent price increases
* Apply Python data analysis and visualisation techniques on real-world datasets

---

# Dataset Sources

This project uses publicly available datasets from Singapore government sources:

### 1. HDB Resale Flat Prices

Source: data.gov.sg

Datasets used:

* Resale Flat Prices (Based on Approval Date), 1990 - 1999
* Resale Flat Prices (Based on Approval Date), 2000 - Feb 2012
* Resale Flat Prices Based on Registration Date From Jan 2015 to Dec 2016
* Resale Flat Prices Based on Registration Date From Jan 2017 Onwards

### 2. Consumer Price Index (CPI)

Source: Department of Statistics Singapore

Used for inflation adjustment and real price calculation.

---

# Technologies & Libraries Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib

---

# Project Workflow

## 1. Data Loading & Cleaning

* Imported multiple HDB resale datasets
* Combined datasets into a single dataframe
* Converted dates and numerical values
* Removed missing and invalid records
* Standardised columns for analysis

## 2. Exploratory Data Analysis (EDA)

* Calculated yearly median resale prices
* Analysed long-term price trends
* Visualised price movement across years

## 3. Inflation Adjustment

* Integrated CPI datasets
* Calculated inflation-adjusted resale prices
* Compared nominal prices against real prices

## 4. Data Visualisation

Generated charts and trend analysis including:

* Yearly resale price trends
* Inflation-adjusted real price comparison
* Percentage increase calculations
* Trend interpretation and findings

---

# Key Findings

## 1. Sharp Increase in HDB Resale Prices After 2020

The analysis identified a significant rise in resale flat prices after 2020.

Possible contributing factors include:

* COVID-19 construction delays
* Supply shortages in BTO projects
* Increased housing demand
* Low interest rates
* Preference for larger homes during the pandemic

## 2. Price Increase Was Not Caused Only by Inflation

After adjusting prices using CPI data, the analysis showed that real prices also increased significantly.

This suggests that the rise in HDB resale prices represents a genuine increase in housing affordability pressure rather than normal inflation alone.

---

# Skills Demonstrated

* Data Cleaning
* Data Analysis
* Exploratory Data Analysis (EDA)
* Data Visualisation
* Real-world Dataset Handling
* Inflation Adjustment Analysis
* Python Programming
* Problem Solving

---

# Project Structure

```text
├── PDS_CA2.ipynb
├── README.md
```

---

# Notes

Dataset files were excluded due to file size limitations.  
Data sources are publicly available from data.gov.sg and Singapore Department of Statistics.

---

# How to Run the Project

1. Clone or download the repository
2. Open the Jupyter Notebook file
3. Ensure required Python libraries are installed
4. Run all notebook cells sequentially

Required libraries:

```python
pip install pandas numpy matplotlib
```

---

# Author

Singapore Polytechnic – Diploma in Information Technology Student
Specialisation: Cloud Computing & Cybersecurity
Minor in Data & AI
