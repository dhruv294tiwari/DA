# Exploratory Data Analysis (EDA) – Employee HR Dataset

## 📌 Project Overview
This project performs an in-depth **Exploratory Data Analysis (EDA)** on an employee HR dataset with a strong focus on **data cleaning, missing value treatment, and feature engineering**.

The objective is to transform raw, inconsistent employee data into a clean, analysis-ready dataset suitable for business intelligence and analytics.

---

## 📂 Dataset Description

### 1️⃣ Raw Dataset
- **File:** `employee_dataset2.csv`
- Contains employee-level data with multiple missing and inconsistent values.
- Columns include:
  - Employee details
  - Department
  - Salary
  - Joining date
  - Performance and promotion indicators

### 2️⃣ Cleaned Dataset
- **File:** `upd_employee_data2.csv`
- All missing values handled
- New analytical features added
- Ready for BI dashboards or further analysis

---

## 🎯 Objectives
- Identify and handle missing data systematically
- Standardize categorical and numerical variables
- Perform feature engineering for time-based analysis
- Prepare high-quality data for downstream analytics

---

## 🛠️ Tools & Technologies
- **Python**
- **Pandas**
- **NumPy**
- **Jupyter Notebook**

---

## 🔎 Key Steps Performed

### ✔ Data Inspection
- Reviewed dataset structure using `info()` and `describe()`
- Identified missing and inconsistent values

### ✔ Missing Value Treatment
- Filled categorical nulls with logical labels (`Unknown`)
- Imputed numerical columns using statistical techniques
- Ensured no null values remain in the final dataset

### ✔ Feature Engineering
- Created `Years_at_Company`
- Extracted `Join_Year` from joining date
- Interpreted promotion indicators for analysis

### ✔ Data Validation
- Verified data types
- Checked for consistency across columns
- Ensured dataset readiness for visualization tools

---

