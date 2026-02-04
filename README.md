# Exploratory Data Analysis (EDA) – Employee Dataset

## 📌 Project Overview
This project performs an **Exploratory Data Analysis (EDA)** on an employee dataset to understand workforce structure, salary distribution, department-wise trends, and time-based patterns using employee joining dates.

The analysis focuses on cleaning the data, extracting useful features, and generating meaningful insights that can help in **HR analytics and decision-making**.

---

## 📂 Dataset Description

### 1️⃣ Original Dataset
- **File:** `employee_data.csv`
- Contains raw employee information such as:
  - Employee ID
  - Department
  - Salary
  - Joining Date
  - Other employee attributes

### 2️⃣ Updated Dataset
- **File:** `upgraded employee_data.csv`
- Enhanced version with:
  - Cleaned values
  - Date-time transformations
  - Derived features (Year, Month of joining)

---

## 🧠 Objectives of the Analysis
- Understand the structure and quality of employee data
- Check for missing and duplicate records
- Analyze salary distribution across departments
- Extract time-based insights from joining dates
- Perform department-wise statistical analysis
- Build a foundation for future HR dashboards or predictive models

---

## 🛠️ Tools & Technologies Used
- **Python**
- **Pandas** – data manipulation
- **NumPy** – numerical operations
- **Seaborn** – data visualization
- **Jupyter Notebook**

---

## 🔎 Key Steps Performed

### ✔ Data Loading
- Imported employee data using pandas
- Inspected dataset using `head()`, `shape`, and `info()`

### ✔ Data Cleaning
- Checked for missing values using `dropna()`
- Verified duplicate records
- Converted `Joining_Date` to datetime format

### ✔ Feature Engineering
- Extracted:
  - **Year of Joining**
  - **Month of Joining**
- Created new columns for time-based analysis

### ✔ Department-Wise Analysis
- Employee count per department
- Average salary by department
- Group-based aggregation using `groupby()`

---

## 📊 Sample Insights
- Certain departments show significantly higher average salaries
- Joining trends vary across months and years
- Clean dataset with minimal duplication issues
- Strong foundation for further visualization or dashboarding

*(Exact insights may vary depending on dataset values.)*

---
