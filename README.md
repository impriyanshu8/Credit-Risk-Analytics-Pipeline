# 💳 Credit Risk Analytics Pipeline using Python & Power BI

## 📖 Project Overview

This project demonstrates an end-to-end data analytics workflow for analyzing customer credit card default behavior using the UCI Credit Card dataset. The entire workflow — data extraction, cleaning, transformation, exploratory data analysis (EDA), feature engineering, and KPI calculation — is implemented in a single Jupyter Notebook, followed by an interactive Power BI dashboard for credit risk analysis.

The objective of this project is to simulate a real-world financial analytics workflow similar to those used in banking and financial institutions for customer behavior analysis and risk assessment.

---

# 🎯 Objectives

* Build a Python-based ETL workflow within a single notebook.
* Perform comprehensive data cleaning and preprocessing.
* Conduct Exploratory Data Analysis (EDA).
* Engineer business-oriented features for analysis.
* Calculate key business KPIs for credit risk.
* Build an interactive Power BI dashboard.
* Generate actionable business insights regarding customer credit behavior and default risk.

---

# 🏗️ Project Architecture

```
                 Kaggle Dataset
                        │
                        ▼
              Raw Data (Local/CSV)
                        │
                        ▼
        Python Notebook: Extract & Load
                        │
                        ▼
            Data Cleaning & Transformation
                        │
                        ▼
            Feature Engineering & KPIs
                        │
                        ▼
         Exploratory Data Analysis (EDA)
                        │
                        ▼
            Cleaned Dataset (CSV Export)
                        │
                        ▼
          Interactive Power BI Dashboard
```

---

# 📂 Project Structure

```
credit-risk-analytics/

│
├── data/
│   ├── UCI_Credit_Card.csv
│   └── cleaned_credit_data.csv
│
├── notebooks/
│   └── credit_risk_analysis.ipynb
│
├── dashboard/
│   └── Credit_Risk_Dashboard.pbix
│
├── reports/
│
├── images/
│
├── requirements.txt
│
└── README.md
```

---

# 📊 Dataset Information

Dataset: **UCI Credit Card Default Dataset**

The dataset contains information about credit card customers including:

* Customer demographics
* Credit limits
* Bill statements
* Previous payment history
* Payment amounts
* Default payment status

### Dataset Size

* Approximately 30,000 customer records
* 25 features

---

# ⚙️ Notebook Workflow

All steps below are performed within a single notebook: `notebooks/credit_risk_analysis.ipynb`

## 1. Extract & Load

* Read raw dataset from local storage
* Validate file integrity and structure

## 2. Data Cleaning & Transformation

* Handle missing values
* Remove duplicate records
* Correct inconsistent data
* Convert data types
* Rename columns for clarity

## 3. Feature Engineering

* Total Bill Amount
* Total Payment Amount
* Average Bill Amount
* Average Payment Amount
* Credit Utilization Ratio
* Payment Ratio
* Number of Delayed Payments
* High-Risk Customer Indicator

## 4. KPI Calculation

* Overall Default Rate
* Average Credit Limit
* Average Credit Utilization
* Average Payment Ratio
* High-Risk Customer Percentage
* Segment-wise Default Rates (by age, gender, education, marriage)

## 5. Exploratory Data Analysis (EDA)

### Dataset Overview

* Dataset dimensions
* Data types
* Missing values
* Duplicate records
* Descriptive statistics

### Univariate Analysis

* Age Distribution
* Gender Distribution
* Education Level
* Marital Status
* Credit Limit Distribution
* Default Distribution

### Bivariate Analysis

* Age vs Default
* Credit Limit vs Default
* Education vs Default
* Gender vs Default
* Marriage vs Default

### Financial Analysis

* Bill Amount Analysis
* Payment Amount Analysis
* Payment Delay Analysis
* Credit Utilization Analysis

### Correlation Analysis

* Correlation Matrix
* Feature Relationships

### Outlier Detection

* Credit Limit
* Bill Amount
* Payment Amount

## 6. Export

* Cleaned and feature-engineered dataset exported as CSV for use in Power BI

---

# 📊 Power BI Dashboard

The dashboard consists of multiple analytical pages.

### Executive Dashboard

* Total Customers
* Average Credit Limit
* Default Rate
* Average Customer Age

### Customer Analytics

* Gender Analysis
* Education Distribution
* Marital Status
* Age Groups

### Credit Analysis

* Credit Limit Distribution
* Bill Amount Analysis
* Payment Analysis

### Risk Analysis

* Customer Default Analysis
* Payment Behaviour
* Credit Utilization
* Customer Segmentation

---

# 📌 Business Insights

The dashboard enables analysis of:

* Customer demographic patterns
* Credit utilization trends
* Payment behaviour
* Default distribution
* High-risk customer identification
* Credit exposure
* Customer segmentation

---

# 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook
* Power BI
* Git
* GitHub

---

# 🚀 Future Enhancements

* Cloud Data Warehouse Integration (AWS S3 / Azure / GCP)
* SQL Data Warehouse Integration
* Automated ETL Scheduling
* Machine Learning-based Default Prediction
* Interactive Reporting Automation

---

# 📚 Learning Outcomes

Through this project, I gained practical experience in:

* Building an end-to-end ETL workflow in Python
* Data cleaning and preprocessing
* Exploratory Data Analysis
* Feature engineering
* KPI design and calculation for financial analytics
* Financial data analytics
* Dashboard development using Power BI
* End-to-end analytics workflow

---

# 👨‍💻 Author

**Priyanshu Yadav**
