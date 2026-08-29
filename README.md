# 📊 Amazon Sales Performance Analysis

## 📌 Project Overview
This project provides a comprehensive Data Analysis (EDA), Cleaning, Preprocessing, and Interactive Visualization of **50,000 Amazon sales transactions**. The objective is to extract business metrics regarding total revenue, profitability, customer purchasing channels, and regional demand distribution.

---

## 🛠️ Tech Stack & Libraries
- **Language:** Python 🐍
- **Data Manipulation:** `pandas`, `numpy`
- **Interactive Visualization:** `plotly.express`, `plotly.graph_objects`
- **Static Plotting:** `seaborn`, `matplotlib`

---

## 🔄 Data Pipeline & Workflow

### 1. Data Cleaning
- Checked dataset dimensions and data types (`50,000 rows, 14 columns`).
- Handled and verified zero missing values (`non-null`).
- Verified duplicate records to ensure metrics accuracy.
- Converted date strings into pandas `datetime64` format.

### 2. Feature Engineering & Preprocessing
- Extracted temporal features (`Year`, `Month`, `Day_Name`) from order dates for time-series aggregation.
- Calculated financial indicators including total revenue and gross profit.

### 3. Exploratory Data Analysis (EDA) & Visualization
Created **8 interactive visualizations** using Plotly Express:
1. **Total Revenue Over Time** (Line Chart)
2. **Total Revenue by Product Category** (Horizontal Bar Chart)
3. **Total Profit by Customer Region** (Bar Chart)
4. **Payment Methods Distribution** (Pie Chart)
5. **Average Customer Rating by Category** (Bar Chart)
6. **Monthly Revenue Trend** (Bar Chart)
7. **Discount Percent vs. Quantity Sold** (Scatter Plot)
8. **Yearly Profit by Customer Region** (Grouped Bar Chart)

---

## 📈 Key Business Insights
- **Revenue Drivers:** Specific product categories account for the highest share of total revenue.
- **Regional Demand:** Profitable regions identified to help target future marketing efforts.
- **Payment Preferences:** Preferred payment methods highlighted to optimize customer checkout experiences.
- **Discount Impact:** Analyzed the relationship between discount percentages and total units sold.

---

## 📁 Repository Structure
```text
├── Amazon_Sales_Analysis.ipynb   # Jupyter Notebook containing full Python code
├── README.md                      # Project documentation and summary
