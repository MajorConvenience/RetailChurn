# RetailChurn
# 📊 Project Title: Retail Customer Churn Analysis & Dashboard

## 📝 Overview
This project analyzes customer churn for a retail subscription service using the **Telco Customer Churn Dataset**.  
The goal is to identify at-risk customers, uncover churn drivers, and provide actionable insights for retention strategies.

## 🎯 Business Problem
Customer churn significantly impacts recurring revenue. For retail and subscription-based businesses, retaining existing customers is more cost-effective than acquiring new ones.  
This project helps stakeholders identify **who is leaving, why they are leaving, and how to retain them**.

## 📂 Dataset
- **Source:** [Kaggle – Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)  
- **Size:** 7,043 customers × 21 columns  
- **Description:** Includes demographics (gender, age, partner, dependents), services used (internet, phone, streaming), account info (tenure, contract type, payment method), and churn label (Yes/No).  

## 🛠️ Tools & Technologies
- **Programming:** SQL (MySQL), Python (pandas, matplotlib, seaborn)
- **Visualization:** Power BI (dashboard)  
- **Other Tools:** Excel for initial exploration  

## 🔑 Key Skills Demonstrated
- SQL joins, aggregations, and churn rate calculations  
- Data cleaning & EDA with Python  
- Visualization of churn drivers (tenure, contract type, payment method)  
- Business KPI dashboard design in Power BI  
- Actionable business storytelling  

## 📊 Methodology
1. **Data Collection** – Downloaded Kaggle dataset in CSV format.  
2. **Data Cleaning** – Handled missing values in `TotalCharges`, standardized categorical fields.  
3. **SQL Analysis** – Calculated churn % by demographics, tenure, and payment method.  
4. **Python EDA** – Explored correlations between customer features and churn rate.  
5. **Dashboard Creation** – Built interactive Power BI dashboard with filters for contract type, payment method, and service usage.  

## 📈 Key KPIs
- **Churn Rate (% of customers leaving)**  
- **Average Tenure of Churned vs. Retained Customers**  
- **Churn by Contract Type (Month-to-Month vs. Yearly)**  
- **Churn by Payment Method (Credit Card vs. Electronic Check)**  

## 📌 Results & Insights
- Customers with **month-to-month contracts** are **3× more likely to churn** compared to long-term contracts.  
- Customers using **electronic check payments** have the **highest churn rate (45%)**.  
- Average tenure of churned customers is **~19 months**, vs. **~38 months** for retained customers.  
- Longer commitments and auto-pay methods correlate with **higher retention rates**.  

## 📷 Screenshots
### Power BI Dashboard  
![Churn Dashboard](./dashboards/churn_dashboard.png)  

---

## 🚀 How to Run the Project
1. Clone the repository  
   ```bash
   git clone https://github.com/yourusername/Retail_Customer_Churn.git
