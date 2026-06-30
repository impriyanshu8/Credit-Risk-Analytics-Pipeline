# 💳 Credit Risk Analytics Pipeline using AWS S3, Python & Power BI

## 📖 Project Overview

This project demonstrates an end-to-end data analytics pipeline for analyzing customer credit card default behavior using the UCI Credit Card dataset. The project follows an industry-oriented workflow by storing raw data on Amazon S3, performing ETL (Extract, Transform, Load) operations using Python, conducting Exploratory Data Analysis (EDA), engineering meaningful business features, and developing an interactive Power BI dashboard for credit risk analysis.

The objective of this project is to simulate a real-world financial analytics workflow similar to those used in banking and financial institutions for customer behavior analysis and risk assessment.

---

# 🎯 Objectives

* Store raw datasets in AWS S3.
* Build a Python-based ETL pipeline.
* Perform comprehensive data cleaning and preprocessing.
* Conduct Exploratory Data Analysis (EDA).
* Engineer business-oriented features for analysis.
* Build an interactive Power BI dashboard.
* Generate actionable business insights regarding customer credit behavior and default risk.

---

# 🏗️ Project Architecture

```
                 Kaggle Dataset
                        │
                        ▼
                AWS S3 (Raw Data)
                        │
                        ▼
          Python ETL Pipeline (Extract)
                        │
                        ▼
            Data Cleaning & Transformation
                        │
                        ▼
            Feature Engineering & Validation
                        │
                        ▼
         Cleaned Dataset Stored in AWS S3
                        │
                        ▼
         Exploratory Data Analysis (EDA)
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
│
├── etl/
│   ├── extract.py
│   ├── transform.py
│   └── load.py
│
├── notebooks/
│   └── credit_risk_eda.ipynb
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

# ☁️ AWS S3 Integration

Amazon S3 is used as the cloud storage layer.

### Bucket Structure

```
credit-risk-data/

raw/
    UCI_Credit_Card.csv

cleaned/
    cleaned_credit_data.csv
```

The ETL pipeline extracts the raw dataset from Amazon S3, performs all preprocessing tasks, and uploads the cleaned dataset back to the S3 bucket.

---

# ⚙️ ETL Pipeline

## Extract

* Read raw dataset from Amazon S3
* Validate file integrity

## Transform

* Handle missing values
* Remove duplicate records
* Correct inconsistent data
* Convert data types
* Rename columns
* Feature engineering
* Data validation

## Load

* Store cleaned dataset
* Upload processed dataset to Amazon S3

---

# 📈 Exploratory Data Analysis (EDA)

The project includes extensive exploratory analysis covering:

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

---

# 🔧 Feature Engineering

Additional analytical features include:

* Total Bill Amount
* Total Payment Amount
* Average Bill Amount
* Average Payment Amount
* Credit Utilization Ratio
* Payment Ratio
* Number of Delayed Payments
* High-Risk Customer Indicator

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
* Amazon AWS S3
* Power BI
* Git
* GitHub

---

# 🚀 Future Enhancements

* SQL Data Warehouse Integration
* Automated ETL Scheduling
* Machine Learning-based Default Prediction
* Cloud Data Warehouse Integration
* Interactive Reporting Automation

---

# 📚 Learning Outcomes

Through this project, I gained practical experience in:

* Cloud-based data storage using AWS S3
* Building ETL pipelines
* Data cleaning and preprocessing
* Exploratory Data Analysis
* Feature engineering
* Financial data analytics
* Dashboard development using Power BI
* End-to-end analytics workflow

---

# 👨‍💻 Author

**Priyanshu Yadav**

