# 📊 Credit Card Financial Weekly Dashboard Report

#🚀 Project Objective

The goal of this project is to develop a **comprehensive credit card weekly dashboard** that provides **real-time insights** into key performance metrics and trends. This enables stakeholders to **monitor** and **analyze credit card operations** effectively.

## 🛠️ Key Features

- **Dynamic Metrics Tracking:** Weekly revenue, transactions, and customer data.
- **DAX Queries:** Custom metrics for age group, income group, and revenue calculations.
- **Visual Insights:** Intuitive charts and graphs for quick analysis.
- **Comparative Analytics:** Week-over-week performance trends.

# 📊 Insights Delivered

# Week 53 (31st Dec):
- **Revenue:** Increased by **28.8%**
- **Total Transactions:** Significant increase observed
- **Customer Count:** Growth in weekly activity

# Year-To-Date (YTD) Overview:
- **Total Revenue:** $57M  
- **Interest Earned:** $8M  
- **Total Transaction Amount:** $46M  
- **Top Contributors:**  
   - Male Customers: $31M  
   - Female Customers: $26M  
- **Card Contributions:** Blue & Silver cards - **93% of transactions**  
- **Top States:** TX, NY & CA (**68% contribution**)  
- **Activation Rate:** 57.5%  
- **Delinquent Rate:** 6.06%  

## 📑 Technical Details

### ⚙️ DAX Queries Used
- **Age Grouping:** Categorizes customers into age brackets.  
- **Income Grouping:** Groups customers based on income levels.  
- **Weekly Revenue Tracking:** Compares current and previous week revenue.  

Example Query:
```DAX
week_num2 = WEEKNUM('public cc_detail'[week_start_date])
Revenue = 'public cc_detail'[annual_fees] + 'public cc_detail'[total_trans_amt] + 'public cc_detail'[interest_earned]

💻 Tools & Technologies Used
Microsoft Power BI
DAX (Data Analysis Expressions)
SQL (Optional, if data preprocessing was involved)
