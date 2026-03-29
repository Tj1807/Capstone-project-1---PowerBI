# Capstone-project-1---PowerBI



---

# 🚗 Car Sales Performance Dashboard

## Power BI Capstone Project – Data Analytics

## Author: Tejaswi Shekar
## Duration: March 2026
## Program: PGDA – Data Science, Imarticus Learning, Bengaluru

---

## 📌 Project Overview

### This project analyzes "7 years (2018–2024)" of car sales data to uncover trends, optimize business performance, and provide actionable insights using Power Bi.

### The goal is to help decision-makers understand sales patterns, identify top performers, and improve profitability.

---

## 🎯 Problem Statement

### Analyze historical car sales data to:

### 1. Track Year-over-Year (YoY) profit trends
### 2. Identify top-performing salespeople and customers
### 3. Understand seasonality and regional patterns
### 4. Generate data-driven recommendations

## 📊 Dataset Source:

### Kaggle – USA Car Sales Dataset (2018–2024):


---

## 🧹 Data Cleaning & Modeling

### 🔧 Power Query Transformations

### 1. Removed duplicate rows using unique Row ID
### 2. Standardized date formats (MM/DD/YYYY)
### 3. Created age groups:

  ### 18–30
  ### 31–45
  ### 46–60
  ### 60+
  <img width="1918" height="988" alt="image" src="https://github.com/user-attachments/assets/3a4abe90-f3db-4eea-ae81-9386165bde6c" />

### Validated numeric columns (Price, Profit, Discount)
<img width="1183" height="721" alt="image" src="https://github.com/user-attachments/assets/de53e65d-a271-4e4c-9513-dbae578670cb" />



## 🧱 Data Model

### Built a Star Schema:

  ### 1 Fact Table (Sales)
  ### 5 Dimension Tables
  <img width="1918" height="988" alt="image" src="https://github.com/user-attachments/assets/8fbe9d8b-bc42-41c0-b717-f50b6971a9b2" />


---

## 📊 Key DAX Measures

### 1. Total Sales → Revenue aggregation
<img width="648" height="32" alt="image" src="https://github.com/user-attachments/assets/e121ae9e-1a0a-4a4f-817c-f875c70c06f2" />

### 2. Total Profit → Overall earnings
<img width="342" height="33" alt="image" src="https://github.com/user-attachments/assets/c420dab2-2f31-41ac-8be0-59d355e13a40" />

### 3. YoY Growth → Profit change over years
<img width="456" height="121" alt="image" src="https://github.com/user-attachments/assets/742b8846-df21-45b6-82bf-16255a49dcf8" />

### 4. Profit Margin % → Profitability ratio
<img width="525" height="32" alt="image" src="https://github.com/user-attachments/assets/330093ee-ed36-46ef-afd6-56d788f5d479" />

### 5. Average Discount % → Promotion effectiveness
<img width="395" height="33" alt="image" src="https://github.com/user-attachments/assets/766065bc-7e2b-4d69-84ae-34cde5ec7826" />

### 6. DateMaster Table → Calendar intelligence
<img width="607" height="407" alt="image" src="https://github.com/user-attachments/assets/32baa050-6754-4714-8029-be58969c1518" />


---

## 📈 Dashboards & Insights

### 1️⃣ Sales Overview

#### 💰 Total Sales: $489M
#### 📈 Total Profit: $45.6M
#### 📊 Profit Margin: 9.32%
#### 📉 YoY Growth: -1.6%

<img width="1381" height="737" alt="image" src="https://github.com/user-attachments/assets/9b1b048c-f73c-4d20-82d5-e039b9466dbc" />


## Key Insight:

### Losses reduced from $188K → $120K (36% improvement)
<img width="1370" height="492" alt="image" src="https://github.com/user-attachments/assets/174d4d23-70cd-4941-a37f-52aeb67e39f5" />

---

### 2️⃣ Salesperson Performance

#### Top performers based on revenue, margin, and units sold:

#### 1. Chris Johnson – $13.3M
#### 2. David Mullen – $12.7M
#### 3. Samantha Cooper – $11.1M

### 📌 Interactive filters enable trend analysis across:

#### 1. Revenue
#### 2. Profit
#### 3. Margin
#### 4. Units sold

<img width="1392" height="737" alt="image" src="https://github.com/user-attachments/assets/aef912c3-fb81-45b2-92eb-97b4491bc521" />


---

### 3️⃣ Customer Analytics

#### 1. 👥 Largest Age Group: 31–45 (34%)
#### 2. 📊 Gender Split:

  #### Male: 50.4%
  #### Female: 49.6%

### Top Customer:

#### Jennifer Jones – $1.28M across 9 

<img width="1403" height="737" alt="image" src="https://github.com/user-attachments/assets/36b797b5-46bc-44df-bc99-adcfadbb6923" />


---

## 💡 Strategic Recommendations

### 1. 🎯 Target **31–45 age group** (largest segment)
### 2. 🏆 Reward top-performing salespeople
### 3. 🔍 Investigate **YoY decline (-1.6%)**
### 4. 📦 Increase inventory for **Ford / Explorer**

---

## 🔮 Future Enhancements

### 1. 📈 **Sales Forecasting**

  #### ARIMA / Prophet models

### 2. 👥 **Customer Segmentation**

  #### RFM clustering

### 3. 💰 **Predictive Pricing**

  #### Dynamic pricing optimization

---

## ✅ Conclusion

### Successfully built an interactive dashboard analyzing:

#### 1. $489M sales data
#### 2. 7 years of performance trends
#### 3. Actionable insights for business growth and decision-making

---

## 🛠️ Tech Stack

### 1. Power BI
### 2. DAX
### 3. Power Query
### 4. Data Modeling (Star Schema)


