--> Super Store Sales Analysis

# Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on a Super Store Sales dataset using Python. The objective is to uncover meaningful business insights related to sales performance, product demand, profitability, and shipping preferences.

The analysis was performed using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn. The project demonstrates the complete EDA workflow, including data exploration, feature engineering, aggregation, visualization, and insight generation.

---

## 🎯 Business Objectives

The following business questions were explored:

1. What is the overall sales trend over time?
2. Which are the Top 10 products by total sales?
3. Which products are sold in the highest quantities?
4. Which shipping mode is preferred by customers?
5. Which categories and sub-categories generate the highest profit?

---

## 🛠️ Tools & Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* vs code(.ipynb)
* Excel Dataset

---

##  Project Structure

Super_store_sales_analysis
│
├── data
│   └── superstore_sales.xlsx
│
├── notebook
   └── analysis.ipynb
```

---

## 📚 Dataset Description

The dataset contains information related to:

* Customer Orders
* Products
* Categories and Sub-Categories
* Sales
* Profit
* Quantity
* Order Dates
* Shipping Information

These fields help analyze business performance and identify opportunities for growth and optimization.

---

# Data Preparation & Feature Engineering

Before analysis, the following preprocessing steps were performed:

* Loaded dataset using Pandas
* Inspected column names and data types
* Generated statistical summaries
* Converted date fields into proper datetime format
* Extracted Month-Year information from order dates
* Created new features for trend analysis

---

## Exploratory Data Analysis

### 1. Overall Sales Trend

A Month-Year feature was created from the Order Date column to analyze how sales changed over time.

**Goal:**

* Identify sales growth patterns
* Detect seasonal trends
* Understand business performance over different periods

---

### 2. Top 10 Products by Sales

Products were grouped by total sales and ranked to identify the highest revenue-generating products.

**Goal:**

* Find star-performing products
* Understand product contribution to revenue
* Support inventory and marketing decisions

---

### 3. Most Selling Products

Products were grouped by quantity sold to identify items with the highest demand.

**Goal:**

* Measure customer demand
* Identify frequently purchased products
* Support stock planning

---

### 4. Preferred Shipping Mode

A count plot was used to visualize the distribution of shipping methods.

**Goal:**

* Understand customer shipping preferences
* Identify the most commonly used delivery method

---

### 5. Most Profitable Categories & Sub-Categories

Profit was aggregated across categories and sub-categories to determine which product groups contribute most to overall profitability.

**Goal:**

* Identify high-margin business segments
* Support strategic decision-making
* Highlight profitable product areas

---

## 🔍 Key Insights

Based on the analysis:

* Sales performance varies across different time periods.
* A small group of products contributes significantly to total sales.
* Some products generate high demand when measured by quantity sold.
* Customers show a clear preference for specific shipping methods.
* Certain categories and sub-categories contribute disproportionately to overall profit.

---

## 💡 Business Value

The insights generated from this analysis can help businesses:

* Improve inventory management
* Optimize product strategy
* Focus marketing efforts on high-performing products
* Improve profitability
* Better understand customer purchasing behavior

---

## 👨‍💻 Author

**Adarsh Pandey**

Aspiring Data Analyst | Python | SQL | Data Visualization | Exploratory Data Analysis

Currently building projects and developing analytical skills through real-world datasets.
