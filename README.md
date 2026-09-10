# 🛍️ Customer Shopping Behavior Analysis

## 📌 Project Overview

This project analyzes **customer shopping behavior** using transactional data from **3,900 purchases** across multiple product categories. The objective is to understand customer preferences, purchasing patterns, spending behavior, and business performance.

The project combines **Python, PostgreSQL, and Power BI** to perform data cleaning, exploratory analysis, business-focused SQL analysis, and interactive data visualization.

---

## 🎯 Objectives

* Understand customer purchasing patterns
* Identify high-value customers and customer segments
* Analyze product performance and sales trends
* Evaluate the impact of discounts and subscriptions
* Compare customer behavior across demographics
* Generate actionable business recommendations
* Build an interactive dashboard for decision-making

---

## 📊 Dataset Information

| Attribute      | Details                      |
| -------------- | ---------------------------- |
| Total Records  | 3,900                        |
| Total Features | 18                           |
| Data Type      | Customer Transactional Data  |
| Analysis Tools | Python, PostgreSQL, Power BI |

### 🔑 Key Features

**Customer Information**

* Age
* Gender
* Location
* Subscription Status

**Purchase Details**

* Item Purchased
* Category
* Amount
* Season
* Size
* Color

**Behavioral Information**

* Discount Applied
* Previous Purchases
* Purchase Frequency
* Review Rating
* Shipping Type

---

## 🧹 Data Preprocessing Using Python

Python was used to clean and prepare the dataset for analysis.

### Preprocessing Steps

* Handled missing values in `Review Rating` using **median imputation**
* Renamed columns using **snake_case** for better readability
* Created new features:

  * `age_group`
  * `purchase_frequency_days`
* Removed redundant column:

  * `promo_code_used`
* Performed data validation and transformation
* Loaded the cleaned dataset into **PostgreSQL**

---

## 🐍 Python Analysis

Python was used for data cleaning, preprocessing, feature creation, and exploratory data analysis.

### Key Activities

* Data inspection
* Missing-value treatment
* Feature engineering
* Data transformation
* Exploratory analysis
* Preparation of data for SQL and Power BI

---

## 🗄️ SQL Analysis — PostgreSQL

After preprocessing, the cleaned data was loaded into PostgreSQL for business-focused analysis.

### 🔍 Analysis Performed

* Revenue analysis by gender
* Identification of high-spending customers using discounts
* Top-rated products analysis
* Standard vs Express shipping comparison
* Subscribers vs Non-subscribers analysis
* Product discount dependency analysis
* Customer segmentation:

  * New Customers
  * Returning Customers
  * Loyal Customers
* Top 3 products within each category
* Repeat buyers vs subscription trends
* Revenue contribution by age group

---

## 📈 Power BI Dashboard

An interactive **Power BI dashboard** was created to transform the analysis into meaningful business insights.

### Dashboard Includes

* 💰 Total Revenue
* 🛒 Sales by Category
* 📦 Product Performance
* 👥 Customer Demographics
* 💳 Payment Method Analysis
* 🚚 Shipping Insights
* 📊 Customer Segmentation
* 🔄 Subscription Analysis
* 🎯 Interactive Filters

### Available Filters

* Season
* Gender
* Category

These filters allow users to dynamically explore customer behavior and business performance.

---

## 🛠️ Technologies Used

| Technology     | Purpose                       |
| -------------- | ----------------------------- |
| 🐍 Python      | Data Cleaning & Preprocessing |
| 🗄️ PostgreSQL | SQL Analysis                  |
| 📊 Power BI    | Dashboard & Visualization     |
| 📁 CSV/Excel   | Data Source                   |

---

## 🔄 Project Workflow

```text
Raw Dataset
     ↓
Data Cleaning & Preprocessing
     ↓
Feature Engineering
     ↓
Exploratory Data Analysis
     ↓
PostgreSQL Database
     ↓
SQL Business Analysis
     ↓
Power BI Dashboard
     ↓
Business Insights & Recommendations
```

---

## 💡 Business Insights

The analysis helps businesses understand:

* Which customer segments generate the most revenue
* Which products and categories perform best
* How discounts influence customer spending
* Whether subscribers show different purchasing behavior
* Which age groups contribute most to revenue
* How shipping preferences vary among customers
* Which customers have high-value purchasing behavior

---

## 🚀 Business Recommendations

Based on the analysis, businesses can:

* Develop targeted offers for high-value customers
* Improve customer retention through subscription programs
* Optimize discount strategies
* Promote top-performing products
* Create personalized marketing campaigns
* Focus on high-revenue customer segments
* Improve shipping strategies based on customer preferences

---

## 📂 Project Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── 📁 Dataset/
│   └── customer_shopping_behavior.csv
│
├── 📁 Python/
│   └── data_analysis.ipynb
│
├── 📁 SQL/
│   └── customer_analysis.sql
│
├── 📁 PowerBI/
│   └── customer_shopping_behavior.pbix
│
├── 📁 Screenshots/
│   └── dashboard.png
│
└── README.md
```

---

## 🎯 Skills Demonstrated

* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Python for Data Analytics
* PostgreSQL
* SQL Queries
* Customer Segmentation
* Business Analysis
* Power BI
* Data Visualization
* Dashboard Development
* Data-Driven Decision Making

---



⭐ **If you find this project useful, consider giving the repository a star!**

