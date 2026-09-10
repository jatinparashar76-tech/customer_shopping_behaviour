#  Customer Shopping Behavior Analysis

##  Project Overview
This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories. The goal is to uncover insights into customer preferences, spending patterns, and business performance to support data-driven decision-making.

---

##  Objectives
- Understand customer purchasing patterns  
- Identify high-value customers and segments  
- Analyze product performance and trends  
- Evaluate the impact of discounts and subscriptions  
- Provide actionable business recommendations  

---

##  Dataset Information
- **Total Records:** 3,900  
- **Total Features:** 18  

### Key Features:
- **Customer Info:** Age, Gender, Location, Subscription Status  
- **Purchase Details:** Item Purchased, Category, Amount, Season, Size, Color  
- **Behavioral Data:** Discount Applied, Previous Purchases, Frequency, Review Rating, Shipping Type  

---

##  Data Preprocessing (Python)
- Handled missing values in `Review Rating` using median imputation  
- Renamed columns for better readability (snake_case)  
- Created new features:
  - `age_group`
  - `purchase_frequency_days`  
- Removed redundant columns (`promo_code_used`)  
- Loaded cleaned data into PostgreSQL for further analysis  

---

##  SQL Analysis (PostgreSQL)
Performed business-focused queries to extract insights:

- Revenue analysis by gender  
- High-spending customers using discounts  
- Top-rated products  
- Shipping type comparison (Standard vs Express)  
- Subscribers vs Non-subscribers analysis  
- Discount dependency by products  
- Customer segmentation (New, Returning, Loyal)  
- Top 3 products per category  
- Repeat buyers vs subscription trends  
- Revenue contribution by age group  

---

##  Power BI Dashboard
Developed an interactive dashboard to visualize:
- Total revenue   
- Sales by category and product  
- Customer demographics  
- Payment methods and shipping insights  
- Filters for dynamic analysis (Season, Gender, Category)  

---

##  Key Insights
- Certain categories dominate overall revenue  
- Loyal customers contribute significantly to sales  
- Discounts increase sales but need optimization  
- Subscribers show higher average spending  
- Younger and middle-age groups drive most purchases  

---

##  Business Recommendations
- Introduce loyalty programs for repeat customers  
- Promote subscription benefits to increase retention  
- Optimize discount strategies to maintain profit margins  
- Focus marketing on high-performing products  
- Target high-revenue customer segments  

---

##  Tech Stack
- **Python** (Pandas, Data Cleaning, EDA)  
- **PostgreSQL** (SQL Analysis)  
- **Power BI** (Data Visualization & Dashboard)  

---

##  Project Workflow
1. Data Collection  
2. Data Cleaning & Preprocessing  
3. Exploratory Data Analysis  
4. SQL-Based Business Analysis  
5. Dashboard Creation  
6. Insights & Recommendations  

---

##  How to Run
1. Clone the repository  
```bash
git clone https://github.com/your-username/Customer-Shopping-Behaviour-Data-Analytics-Project.git
