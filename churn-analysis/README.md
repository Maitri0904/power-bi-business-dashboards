# 📊 Customer Churn Analysis Dashboard (Power BI)

## 📌 Project Overview
This project focuses on analyzing **customer churn behavior** using telecom customer data.  
The goal is to identify **who is churning, when they churn, and why they churn**, and to provide **data-driven business insights** that help improve customer retention.

The analysis is implemented using **Power BI**, with advanced KPIs, interactive dashboards, and dynamic tooltips designed from a **business analyst perspective**.

---

## 🗂 Dataset Information
- **Dataset Provider:** SIEKET Systems  
- **Industry:** Telecom
- **Data Type:** Customer-level transactional and service data
- **Records:** 7,043 customers
- **Target Variable:** `Churn` (0 = Retained, 1 = Churned)

---

## 📁 Key Data Columns
- Customer Demographics:  
  `gender`, `SeniorCitizen`, `Partner`, `Dependents`
- Tenure & Lifecycle:  
  `tenure`, `Tenure Group` (New, Early, Mid, Loyal)
- Services:  
  `PhoneService`, `InternetService`, `OnlineSecurity`, `OnlineBackup`,  
  `DeviceProtection`, `TechSupport`, `StreamingTV`, `StreamingMovies`
- Contracts & Payments:  
  `Contract`, `PaperlessBilling`, `Payment Type`, `Payment Method`
- Revenue:  
  `MonthlyCharges`, `TotalCharges`
- Engineered Feature:  
  `Service Count` (Number of active services per customer)

---

## 📊 Dashboards Included

### 1️⃣ Churn Rate Overview
**Purpose:** Overall health check of customer retention  
- Total Customers
- Churn Rate (%)
- Average Total Charges
- Total Churned Customers  
**Key Insight:** Churn decreases as tenure increases.

---

### 2️⃣ Customer Demographics Analysis
**Purpose:** Identify *who* is more likely to churn  
- Churn Rate by Gender
- Churn Rate by Senior Citizen
- Churn Rate by Partner Status
- Churn Rate by Dependents  
**Key Insight:** Customers without partners or dependents show higher churn.

---

### 3️⃣ Customer Tenure Analysis
**Purpose:** Identify *when* churn happens  
- Churn Rate by Tenure Group
- Average Tenure of Churned Customers
- Retention Rate (%)
- Service Usage by Tenure Group  
**Key Insight:** New customers (0–12 months) have the highest churn risk.

---

### 4️⃣ Churn Analysis by Services & Contracts
**Purpose:** Identify *why* customers churn  
- Churn Rate by Contract Type
- Churn Rate by Payment Type
- Monthly Charges vs Service Count
- Customer Distribution by Service Count  
**Key Insight:** Month-to-month contracts and manual payments drive higher churn.

---

### 5️⃣ Service Comparison Dashboard
**Purpose:** Analyze service adoption patterns  
- Online Security Usage %
- Tech Support Usage %
- Streaming TV & Movies Usage %
- Device Protection & Backup Usage %  
**Key Insight:** Entertainment services are widely adopted, while security and support services are underutilized.

---

## 🧠 Business Insights
- **27% overall churn rate** indicates strong retention with improvement opportunities.
- **New customers are the most vulnerable segment**.
- **Customers with more services churn less**, confirming service bundling effectiveness.
- **Manual payment users and month-to-month contracts** show higher churn.
- **Security and support services** are major upsell opportunities.

---

## 🛠 Tools & Technologies
- **Power BI**
- **DAX (Measures & KPIs)**
- **Data Modeling & Feature Engineering**
- **Interactive Filters & Dynamic Tooltips**

---

## 🎯 Business Value
This project helps:
- Reduce churn through early intervention
- Improve product bundling strategies
- Optimize pricing and contract offerings
- Support data-driven decision making for leadership

---

## 📌 Author
**Maitri Chopda**  
Business Analyst | Data Analytics | Power BI  

---

⭐ If you find this project useful, feel free to star the repository!
