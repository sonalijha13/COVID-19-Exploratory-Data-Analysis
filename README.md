
# 🦠 COVID-19 Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project focuses on Exploratory Data Analysis (EDA) of global COVID-19 data using Python. The objective is to analyze historical COVID-19 trends, compare the impact across countries, and identify relationships between different numerical variables through data visualization.

The analysis uses Matplotlib, Seaborn, Pandas, and NumPy.

## 🎯 Objectives

- Analyze global COVID-19 trends over time.
- Identify the top 5 countries by confirmed cases.
- Compare confirmed cases and deaths.
- Analyze the relationship between COVID-19 variables.
- Create meaningful visualizations using Matplotlib and Seaborn.

## 📂 Dataset

- **Source:** COVID-19 Dataset – Kaggle
- **File Used:** `full_grouped.csv`
- **Date Range:** 22 January 2020 to 27 July 2020

### Dataset Features

| Feature | Description |
|---|---|
| Date | Reporting date |
| Country/Region | Country name |
| Confirmed | Total confirmed cases |
| Deaths | Total deaths |
| Recovered | Total recovered cases |
| Active | Active COVID-19 cases |
| New cases | Newly reported cases |
| New deaths | Newly reported deaths |
| New recovered | Newly reported recoveries |
| WHO Region | WHO geographical region |

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Kaggle Notebook

## 🔍 Project Workflow

1. Data Loading and Inspection
2. Data Quality Analysis
3. Missing Value and Duplicate Checks
4. Date Conversion and Feature Engineering
5. Exploratory Data Analysis
6. Data Visualization
7. Insights and Conclusions

## 📊 Visualizations

### 1. Global COVID-19 Trend Analysis

Analyzed the progression of cumulative confirmed COVID-19 cases over time.

### 2. Top 5 Countries by Confirmed Cases

Compared the five countries with the highest reported confirmed cases as of 27 July 2020.

### 3. Confirmed Cases vs Deaths

Used scatter plots to explore the relationship between confirmed cases and deaths across countries.

### 4. Correlation Heatmap

Analyzed relationships between numerical variables such as confirmed cases, deaths, recoveries, and active cases.

### 5. Death Rate Analysis

Compared the reported death rate among the top five countries.

## 💡 Key Insights

- The United States had the highest confirmed COVID-19 cases among the top five countries in the dataset.
- Brazil ranked second, followed by India, Russia, and South Africa.
- Confirmed cases and deaths showed a strong positive correlation (0.91).
- Confirmed cases and active cases showed a correlation of 0.95.
- New cases and new deaths showed a positive correlation of 0.73.
- No missing values or duplicate records were detected.
- Some negative daily statistics were found, potentially reflecting historical reporting adjustments.

## 📌 Conclusion

This project demonstrates how Python-based data analysis and visualization techniques can be used to explore real-world datasets, identify patterns, and communicate meaningful insights.

It helped strengthen my practical understanding of Pandas, Matplotlib, Seaborn, data cleaning, exploratory analysis, and statistical correlation.

## 🚀 Future Improvements

- Analyze COVID-19 vaccination trends using an additional dataset.
- Compare country-wise mortality rates.
- Explore monthly and regional trends.
- Build an interactive COVID-19 dashboard using Streamlit.

## ⭐ Support

If you find this project useful, consider giving this repository a star!

---

**Project:** COVID-19 Exploratory Data Analysis

**Tools:** Python | Pandas | NumPy | Matplotlib | Seaborn
