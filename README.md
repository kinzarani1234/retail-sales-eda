# 🛍️ Online Retail Sales EDA & Power BI Dashboard

This project performs exploratory data analysis (EDA) on an online retail dataset using Python, and visualizes the insights with a Power BI dashboard.

---

## 📊 Project Overview

- Dataset: Online Retail data (Excel format)
- Objective: Analyze customer behavior, product performance, and geographic trends
- Tools Used:
  - Python (Pandas, Seaborn, Matplotlib)
  - Power BI (Interactive dashboard)

---

## 🔍 Analysis Performed

### 🧹 Data Cleaning
- Removed missing and duplicate records
- Filtered out canceled transactions
- Handled outliers in `Quantity` and `Price`
- Added new columns like `Revenue`, `Month`, and `DayOfWeek`

### 📈 Exploratory Data Analysis
- Top-selling products by quantity and revenue
- Monthly and weekly sales trends
- Loyal customer identification
- RFM segmentation
- Country-wise performance (orders & revenue)

---

## 📊 Power BI Dashboard

### 💡 Pages Included

#### 1️⃣ **Sales Overview**
- KPIs: Total Revenue, Total Invoices, Unique Customers
- Monthly Sales Trend (Line Chart)

#### 2️⃣ **Top Products**
- Top 10 Products by Quantity (Bar Chart)
- Top 10 Products by Revenue (Bar Chart)

#### 3️⃣ **Customer Segments**
- RFM Segmentation (Scatter Plot: Recency vs Frequency)
- Segment Distribution (Bar Chart)
- RFM Table

#### 4️⃣ **Geographical Insights**
- Total Orders by Country (Map)
- Revenue by Country (Map)

---

## 📂 Files Included

| File Name          | Description                            |
|--------------------|----------------------------------------|
| `online_retail_sales.ipynb` | Jupyter Notebook with analysis and plots |
| `retail_sales_eda.pbix` | Power BI dashboard file       |
| `requirements.txt`       | Python dependencies              |
| `README.md`              | Project summary                  |

---

## 📥 How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/online-retail-eda.git
   cd online-retail-eda
