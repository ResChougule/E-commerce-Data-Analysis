# 🚀 PROJECT: E-commerce Data Analysis

Scenario 
A data analyst at an online store.

### The company says:
“Revenue has been unstable. We want to understand what's happening and how to improve it.”

----


## 🚀 Overview

This project analyzes e-commerce data to identify key drivers of revenue, conversion performance, and business growth opportunities.

The dataset initially contained messy and inconsistent data, which was cleaned and transformed into an analysis-ready format.

---

## 🎯 Objectives

* Understand revenue trends over time
* Identify key drivers of revenue changes
* Analyze conversion rate and user behavior
* Detect data quality issues
* Provide actionable business recommendations

---

## 🧹 Data Cleaning

The raw dataset contained several issues:

* Missing values (country, device, sessions, product)
* Inconsistent categories (e.g., "Germany" vs "germany")
* Invalid date formats
* Non-numeric revenue values

### Cleaning Steps:

* Standardized text fields (lowercase)
* Replaced missing values with:

  * `unknown` (categorical fields)
  * median (sessions)
  * 0 (revenue/conversions where necessary)
* Removed invalid dates
* Converted all numeric fields properly

---

## 📊 Key Metrics

* **Conversion Rate** = conversions / sessions
* **Average Order Value (AOV)** = revenue / conversions

---

## 📈 Analysis

### 1. Revenue Trend

* Revenue analyzed over time to detect patterns and anomalies

### 2. Conversion Rate Analysis

* Compared across devices and countries
* Identified underperforming segments

### 3. Product Performance

* Identified top products by revenue
* Analyzed AOV for pricing insights

### 4. Data Quality Insights

* Measured impact of unknown categories
* Highlighted tracking/data issues

---

## 🔍 Key Insights

* Revenue fluctuations driven primarily by changes in conversion rate
* Mobile users show lower conversion compared to desktop
* Some products generate high revenue but low AOV
* A portion of revenue is linked to unknown categories, indicating tracking issues

---

## 💡 Business Recommendations

* Improve mobile user experience to increase conversions
* Focus marketing on high-performing segments
* Promote high AOV products
* Fix tracking issues for missing product and country data

---

## 🛠 Tools Used

* Excel (data cleaning, pivot tables, charts)
* Python (data generation and preprocessing)

---

## 📁 Files

* `data/` → raw and cleaned datasets
* `images/` → charts and visualizations
* `analysis_summary.md` → detailed insights

---

## 🧠 Key Learning

This project demonstrates how messy data can be transformed into actionable insights that drive business decisions.

---

## 📌 Author

Reshma Chougule 
