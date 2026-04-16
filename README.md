# 💳 Credit Card Data Analysis (Python Case Study)

## 📌 Project Overview
This project focuses on analyzing credit card customer data to understand spending behavior, repayment patterns, profitability, and product-level performance.

The objective is to perform data cleaning, exploratory data analysis (EDA), profitability calculation, and trend analysis to support strategic decision-making in the credit card industry.

This case study simulates real-world banking analytics problems such as fraud monitoring, profitability analysis, customer segmentation, and product performance tracking.

---

## 🎯 Business Problem
PSPD Bank operates across multiple countries and wants to:

- Identify high-spending customers
- Analyze repayment behavior
- Calculate monthly profitability
- Detect customer segments contributing most to revenue
- Understand city-wise and product-wise performance
- Enable dynamic reporting for top customers

---

## 📂 Dataset Description
The dataset consists of three sheets:

### 1️⃣ Customer Acquisition
Contains customer-level details:
- Customer ID  
- Name  
- Age  
- City  
- Product (Gold / Silver / Platinum)  
- Credit Limit  

### 2️⃣ Spend (Transaction Data)
Contains credit card transaction details:
- Customer  
- Month  
- Type (Product category such as Air Ticket, Petrol, Food, etc.)  
- Amount  

### 3️⃣ Repayment
Contains repayment transaction details:
- Customer  
- Month  
- Amount  

---

## 🛠️ Tools & Technologies Used
- Python  
- Pandas – Data manipulation & aggregation  
- NumPy – Numerical operations  
- Matplotlib – Data visualization  
- Jupyter Notebook  

---

## 🧹 Data Cleaning & Preprocessing
The following preprocessing steps were applied:

- Replaced age < 18 with mean age  
- Capped spend amount exceeding credit limit to 50% of limit  
- Capped repayment amount exceeding limit to maximum credit limit  
- Extracted Year and Month from transaction dates  
- Created Age Groups for demographic analysis  
- Handled inconsistent category labels  

---

## 📊 Analysis Performed

### ✔ Customer & Category Analysis
- Counted distinct customers  
- Identified distinct transaction categories  
- Identified top 5 product types by total spend  
- Identified top 10 customers by repayment amount  

### ✔ Monthly & Profitability Analysis
- Calculated average monthly spend  
- Calculated average monthly repayment  
- Computed monthly bank profit using 2.9% interest rate  
- Calculated interest only on positive balances  

### ✔ City & Demographic Analysis
- Identified city with maximum total spend  
- Analyzed age group contributing highest spend  
- Calculated city-wise yearly spend by product  

### ✔ Trend & Seasonality Analysis
- Monthly spend comparison city-wise  
- Yearly spend comparison for Air Ticket category  
- Monthly spend comparison across products to identify seasonality  

### ✔ Dynamic Reporting Function
Developed a reusable Python function to:

- Identify Top 10 customers by repayment  
- Filter by product type (Gold / Silver / Platinum)  
- Filter by time period (Yearly / Monthly)  
- Segment results city-wise  

---

## 📈 Key Insights
- A small group of customers contributes significantly to repayment revenue  
- Certain cities dominate credit card spending  
- Product category spending shows seasonal variation  
- Bank profitability depends heavily on repayment patterns  
- Premium card holders (Gold/Platinum) contribute higher transaction values  

---

## 📊 Sample Visualizations Included
- Monthly spend trends by city  
- Yearly spend on Air Tickets  
- Product-level monthly seasonality  
- City-wise yearly product performance  

---



---

### 📌 Author
Shashikant Shukla  
Aspiring Data Analyst | Python | SQL | Power BI  

