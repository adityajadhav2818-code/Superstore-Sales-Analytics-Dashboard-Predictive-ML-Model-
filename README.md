# Superstore-Sales-Analytics-Dashboard-Predictive-ML-Model-

##  Project Overview

This project performs an **end-to-end data analysis** on the Superstore dataset to extract meaningful business insights related to **sales, profit, customers, and regional performance**.

It demonstrates a real-world data workflow by combining:

*  **Python (Pandas)** for data cleaning & EDA
*  **SQL** for business-driven analysis

---

##  Business Problem

The goal of this project is to analyze retail sales data and identify:
- Profit-driving factors  
- Loss-making areas  
- Customer and regional performance  

This helps businesses improve profitability and optimize decision-making.

---

##  Objectives

* Identify **top-performing categories and products**
* Detect **loss-making areas**
* Analyze **customer and regional performance**
* Understand the **impact of discounts on profit**
* Track **sales and profit trends over time**

---

##  Tools & Technologies

* Python (Pandas, NumPy, Matplotlib, Seaborn)
* SQL (MySQL)
* Excel

---

##  Project Workflow

### 1️ Data Cleaning & Feature Engineering (Python)

* Handled missing values
* Converted date columns
* Created new features:

  * `order_year`
  * `order_month`
  * `shipping_days`

### 2️ Exploratory Data Analysis (EDA)

* Analyzed sales and profit distributions
* Identified trends, patterns, and anomalies

### 3️ Data Export

```python
df.to_excel("cleaned_superstore.xlsx", index=False)
```

### 4️ SQL Analysis

* Imported cleaned dataset into SQL
* Performed business queries to derive insights

---

##  Project Structure

```
Superstore-End-to-End-Project/
│
├── README.md
├── data/
│   └── superstore.csv
│
├── 1_EDA/
│   ├── Superstore_EDA.ipynb
│   └── README.md
│
├── 2_SQL_ANALYSIS/
│   ├── superstore_analysis.sql
│   └── README.md
│
├── 3_ML_MODEL/
│   ├── Superstore_ML_model.ipynb
│   └── README.md
|
├── 4_POWER_BI/
├   |── Superstore_Dashboard.pbix
│   ├── Dashboard.pdf
│   └── dashboard.png
├── images/
```

---

##  Key Business Questions & Insights

###  Category & Product Analysis

* Technology category generates the **highest profit**
* Some sub-categories (e.g., tables/bookcases) consistently show **low or negative profit**
* Certain products are **always loss-making**

---

###  Discount Impact

* High discounts (>20–30%) significantly **reduce profit**
* Many loss-making orders are linked to **heavy discounting**

---

###  Regional & State Analysis

* Some regions generate **high sales but low profit**
* Certain states dominate overall profit contribution
* Indicates **operational inefficiencies in specific regions**

---

###  Customer Analysis

* A small group of customers contributes **majority of total profit**
* These customers are critical for **business retention strategies**

---

###  Time-Based Analysis

* Sales show **seasonal trends**
* High sales periods do not always result in high profit
* Year-over-year growth shows **overall business expansion**

---

###  Profitability Analysis

* Profit margin varies significantly across sub-categories
* Some segments generate revenue but **fail to generate profit**

---

##  Key Findings

*  High discounts are the **primary cause of losses**
*  Sales ≠ Profit → high revenue doesn’t guarantee profitability
*  Several sub-categories and products consistently generate losses
*  Regional performance is uneven, indicating inefficiencies
*  A few customers drive a large share of profit
*  Sales and profit follow seasonal patterns

---

##  Machine Learning Insights

- **Random Forest provided the best overall performance** with the highest F1 Score and accuracy  
- The model achieves a strong balance between **precision and recall**, ensuring reliable predictions  

###  Model helps to:

- Identify patterns in data for **accurate classification**
- Reduce incorrect predictions (both false positives and false negatives)
- Improve **data-driven decision-making**
- Enable better **business strategy optimization**

---
## Power BI Dashboard

### Designed an interactive business dashboard to visualize key performance indicators.

- Dashboard Features
- Executive KPI Cards
- Total Sales
- Total Profit
- Total Orders
- Average Sales
- Sales Trend Analysis
- Profit Trend Analysis
- Category & Sub-category Performance
- Region-wise Sales & Profit
- Customer Insights
- Dynamic Filters & Slicers
- Interactive Business Visualizations

---

##  Visualizations

### Sales vs Profit Analysis
![Sales vs Profit](https://github.com/adityajadhav28/Superstore-End-to-End-Project/blob/main/images/Sales%20vs%20Profit.png)

Shows that higher sales do not always lead to higher profit.

---

### Discount vs Profit Analysis
![Discount vs Profit](https://github.com/adityajadhav28/Superstore-End-to-End-Project/blob/main/images/Discount%20vs%20Profit.png)

Higher discounts significantly reduce profit and often cause losses.

---

### Region-wise Profit
![Region Profit](https://github.com/adityajadhav28/Superstore-End-to-End-Project/blob/main/images/Year-wise%20Profit%20by%20region.png)

Some regions generate high sales but low profit, indicating inefficiencies.

---

##  Future Improvements

* Add sales forecasting using Time Series Analysis.
* Publish the Power BI dashboard to the Power BI Service.
* Perform advanced customer segmentation using clustering.
* Optimize machine learning models through hyperparameter tuning.

---

##  Resume Value

This project demonstrates:

* Built a complete end-to-end analytics pipeline.
* Performed business analysis using SQL.
* Conducted data cleaning and EDA using Python.
* Designed an interactive Power BI dashboard.
* Developed predictive machine learning models.
* Generated actionable business insights for decision-making.

---

##  Author

**Aditya Jadhav**

*  GitHub: https://github.com/adityajadhav28
*  LinkedIn: https://www.linkedin.com/in/aditya-jadhav-4a1376258/

---

⭐ If you found this project useful, consider giving it a star!

