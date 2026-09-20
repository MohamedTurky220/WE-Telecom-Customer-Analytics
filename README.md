# 📊 WE Telecom Customer Analytics

An end-to-end Telecom Customer Analytics project developed as part of the **Advanced Data Analysis Track at the National Telecommunication Institute (NTI)**.

The project focuses on understanding customer behavior, analyzing customer churn, generating business insights, and applying Machine Learning for churn prediction.

---

## 🚀 Project Overview

The project follows an end-to-end data analytics workflow:

**Python → Power BI → Machine Learning → Streamlit**

### 🔹 1. Data Cleaning, Preprocessing & EDA — Python

We started by cleaning and preparing the telecom customer dataset for analysis and modeling.

The analysis included:

- Data cleaning and preprocessing
- Handling data quality issues
- Exploratory Data Analysis (EDA)
- Identifying customer behavior patterns
- Exploring factors related to customer churn

### 🔹 2. Data Modeling & Visualization — Power BI

The cleaned data was transformed into an interactive **4-page Power BI dashboard** designed to provide both customer-level and business-level insights.

#### 📌 Overview

Provides a high-level view of the customer analytics project and key information.

#### 👥 Customers Overview

Analyzes the customer base across:

- Contract Type
- Payment Method
- Gender
- Internet Service
- Top 5 Cities
- Customer Tenure

#### 💰 Business Insights

Focuses on revenue and customer value, including:

- Average Monthly Charges
- Revenue at Risk
- Revenue Contribution
- Revenue by Contract Type
- Revenue at Risk by Internet Service
- Revenue at Risk by Contract
- Average Monthly Charges by Tenure Group

#### 📉 Churn Analysis

Provides an in-depth analysis of customer churn across:

- Payment Method
- Contract Type
- Internet Service
- Tenure
- Online Security
- Tech Support
- Monthly Charges

---

## 🤖 Machine Learning

After completing the data analysis and Power BI visualization, Machine Learning models were developed and evaluated for **customer churn prediction**.

The project includes:

- Logistic Regression
- Decision Tree
- Random Forest
- Model evaluation
- Churn prediction
- Feature analysis

The selected model is **Logistic Regression**.

### 📈 Model Performance

The selected model achieved:

- **Accuracy:** 73.9%
- **Recall (Churn):** 77.5%
- **F1-Score:** 61.2%
- **ROC-AUC:** 84.5%

---

## 🌐 Streamlit ML Prediction App

A Streamlit application was developed to demonstrate the Machine Learning model.

The application allows users to enter customer information and receive:

- Predicted churn probability
- Customer risk level
- Prediction result

### 🔗 Live Application

**Telco Customer Churn Predictor — Mohamed Turky**

https://mohamed-turky-telco-churn.streamlit.app

---

## 🛠️ Technologies Used

### Data Analysis
- Python
- Pandas
- NumPy
- Jupyter Notebook

### Data Visualization & Business Intelligence
- Power BI

### Machine Learning
- Scikit-learn
- Logistic Regression
- Decision Tree
- Random Forest

### Deployment
- Streamlit
- GitHub

---

## 📁 Repository Structure

```text
WE-Telecom-Customer-Analytics/
│
├── Dashboard/
│   ├── telco_customer_churn_Dashboard.pbix
│   └── Screenshots/
│       ├── Overview.png
│       ├── Customers_Overview.png
│       ├── Business_Insights.png
│       └── Churn_Analysis.png
│
├── Machine Learning/
│   ├── Tele_Customer_Cleaned.ipynb
│   ├── app.py
│   ├── churn_best_model.pkl
│   ├── churn_best_model_name.pkl
│   ├── churn_model.pkl
│   ├── churn_model_columns.pkl
│   ├── churn_scaler.pkl
│   └── encoders.pkl
│
├── Dataset/
│   ├── We_Telco_Customer_Churn.csv
│   └── telco_customer_churn_cleaned.csv
│
├── Documentation/
│   └── Graduation_Project_Documentation.pdf
│
├── Presentation/
│   └── WE_Telecom_Customer_Churn_Final_Presentation.html
│
└── requirements.txt