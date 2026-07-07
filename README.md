# Customer Purchase Behavior Analysis and Data Preprocessing

## Project Overview

This project demonstrates a complete data preprocessing and exploratory data analysis (EDA) workflow for customer purchase behavior data collected from multiple sources. The objective is to clean, transform, analyze, and prepare the dataset for future machine learning applications such as customer purchase prediction.

The project combines data from CSV, JSON, SQL database, and REST API sources and applies various preprocessing techniques including missing value handling, outlier detection, feature engineering, encoding, scaling, and transformation.

---

## Problem Statement

A consumer insights company has provided customer purchase behavior data collected from multiple sources.

The objective is to:

- Import data from different sources
- Merge datasets into a single dataset
- Perform data cleaning
- Handle missing values
- Detect and treat outliers
- Perform exploratory data analysis (EDA)
- Apply feature engineering
- Encode categorical variables
- Scale numerical variables
- Generate a final machine learning-ready dataset

---

## Dataset Sources

The project uses data from the following sources:

- Customers Dataset (CSV)
- Transactions Dataset (JSON)
- Products Database (SQLite)
- DummyJSON Users API

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SQLite3
- Requests
- Scikit-learn
- SciPy
- YData Profiling

---

## Project Workflow

### Part A – Theory

- Data Analysis
- Data Science Project Lifecycle
- Machine Learning Problem Statement
- Tensor Basics with NumPy

---

### Part B – Data Acquisition

- Import CSV file
- Import JSON file
- Import SQL Database
- Fetch data from REST API
- Merge multiple datasets

---

### Part C – Data Understanding

- Dataset Overview
- Data Types
- Summary Statistics
- Missing Value Analysis
- Duplicate Detection
- Correlation Analysis
- Heatmap
- Histogram
- Boxplots
- Pandas Profiling Report

---

### Part D – Missing Value Handling

Implemented multiple missing value imputation techniques:

- Mean Imputation
- Median Imputation
- Most Frequent Imputation
- Missing Indicator
- Random Sample Imputation
- KNN Imputer
- MICE (Iterative Imputer)
- Complete Case Analysis

---

### Part E – Outlier Detection and Treatment

Applied multiple outlier handling techniques:

- Z-Score Method
- Interquartile Range (IQR)
- Percentile Method
- Winsorization

---

### Part F – Feature Engineering

Performed:

- Date Feature Extraction
- Label Encoding
- One-Hot Encoding
- Ordinal Encoding
- Numerical Binning
- Binarization
- Standard Scaling
- Min-Max Scaling
- Robust Scaling
- MaxAbs Scaling
- Function Transformer
- Power Transformer (Box-Cox & Yeo-Johnson)
- Column Transformer
- New Feature Construction

---

## Visualizations

The project includes:

- Correlation Heatmap
- Histograms
- Boxplots
- Missing Value Heatmap
- Income Distribution
- Winsorized Distribution
- Income Group Count Plot
- Binary Income Distribution
- Scaled Feature Comparison

---

## Python Libraries

- pandas
- numpy
- matplotlib
- seaborn
- sqlite3
- requests
- scipy
- scikit-learn
- ydata-profiling

---

## Output Files

- merged_customer_dataset.csv
- processed_customer_data.csv
- Merged_Dataset_Report.html

---

## Learning Outcomes

After completing this project, the following concepts were learned:

- Data Collection from Multiple Sources
- Data Integration
- Data Cleaning
- Missing Value Handling
- Outlier Detection
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Feature Encoding
- Feature Scaling
- Feature Transformation
- Data Preparation for Machine Learning

---

## Conclusion

This project successfully demonstrates an end-to-end data preprocessing pipeline using customer purchase behavior data. Multiple datasets were integrated from CSV, JSON, SQL database, and REST API sources. Various preprocessing techniques including missing value imputation, outlier treatment, encoding, feature scaling, and feature engineering were applied to improve data quality. The final processed dataset is clean, consistent, and suitable for machine learning model development.

---

## Repository Structure

```
Customer-Purchase-Behavior-Analysis/
│
├── DataPreprocessing.ipynb
├── customers.csv
├── transactions.json
├── products.sql
├── merged_customer_dataset.csv
├── processed_customer_data.csv
├── Merged_Dataset_Report.html
├── README.md
└── images/
```

---

## Author

**Nandani Rajput**

B.Tech Computer Science Engineering

GLS University

Ahmedabad, Gujarat
