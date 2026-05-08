# FUTURE_DS_02
Customer Retention &amp; Churn Analysis
# 📊 Customer Retention & Churn Analysis Using Python

## 📌 Project Overview

This project focuses on analyzing customer churn and retention patterns using the Telco Customer Churn dataset.

The main objective is to identify:

* Why customers leave the platform
* Which customer segments are most likely to churn
* Key retention drivers
* Revenue impact of churn
* Business recommendations to reduce customer churn

This project simulates a real-world SaaS/subscription business analytics case study.

---

# 🗂️ Dataset Used

Dataset: `WA_Fn-UseC_-Telco-Customer-Churn.csv`

The dataset contains:

* Customer demographics
* Subscription details
* Internet services
* Contract information
* Payment methods
* Monthly charges
* Churn status

---

# 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

# 🎯 Project Objectives

* Perform customer churn analysis
* Identify retention drivers
* Analyze customer lifetime patterns
* Detect high-risk customer segments
* Evaluate revenue loss due to churn
* Generate actionable business insights

---

# 🧹 Data Cleaning

The following preprocessing steps were performed:

* Handled missing values
* Converted `TotalCharges` to numeric format
* Created `Churn_Flag` column
* Cleaned and prepared dataset for analysis

---

# 📈 Exploratory Data Analysis (EDA)

The following analyses were performed:

* Churn distribution analysis
* Monthly charges analysis
* Customer tenure analysis
* Correlation analysis
* Contract type analysis
* Payment method analysis
* Customer segmentation
* Cohort analysis

---

# 🔍 Key Insights

## 1️⃣ Month-to-Month Customers Have Highest Churn

Customers with month-to-month contracts show significantly higher churn compared to yearly subscribers.

## 2️⃣ Higher Monthly Charges Increase Churn Risk

Customers paying higher monthly charges are more likely to leave the platform.

## 3️⃣ Early Lifecycle Customers Are Most Vulnerable

Most customers churn during the initial months of subscription.

## 4️⃣ Fiber Optic Users Show Higher Churn

Fiber optic internet customers demonstrate higher churn probability.

## 5️⃣ Lack of Tech Support Increases Churn

Customers without technical support services churn more frequently.

---

# 💰 Revenue Analysis

The project also analyzed:

* Total monthly revenue
* Revenue lost due to churn
* Average customer lifetime
* Customer lifetime trends

---

# ✅ Business Recommendations

## 🔹 Improve Customer Onboarding

Focus on the first 3–6 months of customer experience.

## 🔹 Promote Long-Term Contracts

Provide discounts and loyalty benefits for yearly subscriptions.

## 🔹 Target High-Risk Customers

Create retention campaigns for:

* Month-to-month users
* High monthly charge customers
* Fiber optic users

## 🔹 Improve Technical Support

Enhance support quality and response time to improve retention.

## 🔹 Use Predictive Analytics

Implement churn prediction models for proactive customer retention.

---

# 🚀 Skills Demonstrated

* Data Cleaning
* Data Analysis
* Customer Analytics
* Churn Analysis
* Cohort Analysis
* Data Visualization
* Business Intelligence
* Machine Learning
* Business Recommendations

---

# 📌 Final Outcome

This project demonstrates how data analytics can help subscription-based businesses:

* Reduce churn
* Improve retention
* Increase customer lifetime value
* Make data-driven business decisions

---

# 📊 Dashboard Features

The final dashboard includes:

* Churn distribution charts
* Contract churn analysis
* Monthly charges comparison
* Customer tenure distribution
* Correlation heatmap
* Cohort analysis
* KPI summary

---

# 📷 Dashboard Preview

![Dashboard](Fianl_Report/dashboard.png)

---

# 📁 Project Structure

```text id="8w81m0"
FUTURE_DS_02/
│
├── Data/
│   ├── Telco-Customer-Churn.csv
│   └── cleaned-Telco-Customer-Churn.csv
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_exploratory_data_analysis.ipynb
│   ├── 03_churn_analysis.ipynb
│   ├── 04_cohort_analysis.ipynb
│   ├── 05_customer_segmentation.ipynb
│   ├── 06_retention_drivers.ipynb
│   ├── 07_revenue_analysis.ipynb
│   └── 08_dashboard.ipynb
│
├── Final_Report/
│   ├── dashboard.png
│   └── Report.pdf
```

---

# ⚡ Installation

Install dependencies:

```bash id="bdqft7"
pip install numpy pandas matplotlib seaborn
```

