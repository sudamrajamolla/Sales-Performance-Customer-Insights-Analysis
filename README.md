# 📊 Sales Performance and Customer Insights Analysis

## 📌 Project Overview
This project analyzes the **SuperStore Orders dataset** to uncover sales trends, category-wise performance, regional contribution, and high-value customers.  
The goal is to transform raw retail sales data into **actionable business insights** using Python-based data analysis and visualization.

---

## 🎯 Problem Statement
To analyze the **SuperStore Orders dataset** in order to identify sales trends, evaluate category and regional performance, and identify high-value customers for data-driven business decision-making.

---

## 📂 Dataset
- **Name:** SuperStore Orders Dataset  
- **Records:** 51,290 rows  
- **Time Period:** 2011 – 2014  
- **Type:** Retail transactional data  

### Key Columns
- `order_date`, `ship_date`
- `sales`, `profit`, `discount`, `quantity`
- `category`, `sub_category`
- `region`, `market`
- `customer_name`

---

## 🛠 Tools & Technologies
- **Python**
- **Pandas** – Data manipulation and analysis
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualizations
- **Google Colab** – Development environment

---



## 🔄 Project Workflow

### 1️⃣ Data Loading 
(Data source = https://www.kaggle.com/datasets/aditisaxena20/superstore-sales-dataset)
- Loaded CSV dataset with proper encoding handling (`latin1`)
- Verified dataset structure and data types

### 2️⃣ Data Cleaning & Preparation
- Converted `order_date` to datetime format
- Converted `sales` from string to numeric
- Removed duplicate records
- Checked and confirmed no missing values
- Created new derived columns:
  - `year`
  - `month`
  - `profit_margin`

### 3️⃣ Exploratory Data Analysis (EDA)
Performed detailed analysis to answer business questions:

#### 📈 Sales Trend Analysis
- Monthly sales trend across years (2011–2014)
- Identified seasonality and year-over-year growth

#### 📊 Category Performance
- Sales by category
- Profit by category

#### 🌍 Regional Performance
- Sales distribution across regions
- Identification of high and low-performing regions

#### 👥 Customer Analysis
- Top 10 customers by total sales
- Revenue concentration analysis

#### 🔥 Profitability Analysis
- Heatmap of profit by category and region
- Identified profitable and underperforming combinations

---

## 📌 Key Insights
- Sales show consistent growth with strong year-end seasonality
- Technology is the highest-performing category in both sales and profit
- Office Supplies show stable profit margins
- Sales are unevenly distributed across regions
- A small group of customers contributes significantly to total revenue

---

## 📊 Visualizations
The project includes the following visualizations:
- Monthly Sales Trend Line Chart
- Sales by Category Bar Chart
- Profit by Category Bar Chart
- Regional Sales Distribution Pie Chart
- Top 10 Customers by Sales Bar Chart
- Profit by Category and Region Heatmap

---

## 📈 Business Impact
The insights derived from this analysis can help:
- Optimize product and category strategies
- Improve regional sales planning
- Focus on high-value customer retention
- Support data-driven business decisions

---

## 👤 Author
**Sudam Rajamolla**  
sudamrajamolla1@gmail.com

Data Analyst Aspirant  

---

## 📌 Note
This project focuses on **exploratory data analysis and visualization**, demonstrating practical data analyst skills such as data cleaning, trend analysis, and insight generation.
