# 📊 Task 2 & Task 3: Exploratory Data Analysis (EDA) and Data Visualization

## 🎯 Aim
To explore the dataset, understand its structure, detect patterns and data issues using Exploratory Data Analysis (EDA), and to represent the data using visual charts for better understanding and decision making.

---

## 🧰 Tools Used
- Python
- Pandas
- Matplotlib

---

## 📁 Dataset Description
A student dataset containing:
- Age (Numeric)
- Marks (Numeric)
- Gender (Categorical)
- Student Name (Categorical)

This dataset is used to analyze student performance and visualize comparisons.

---

# ✅ TASK 2: Exploratory Data Analysis (EDA)

## 🔍 Purpose of EDA
EDA is used to understand the data before applying any models. It helps to find:
- Data types and structure
- Missing values
- Trends and patterns
- Possible data problems

---

## 📌 Steps Performed

### 1. Data Loading
The dataset is created using Python dictionary and converted into a Pandas DataFrame.

### 2. Data Structure Analysis
- `head()` is used to view first few rows
- `info()` is used to check data types
- `describe()` is used to get statistical summary

### 3. Data Quality Check
- `isnull().sum()` is used to detect missing values

### 4. Pattern Identification
- Scatter plot between Age and Marks is used to find relationship

---

## ✅ Observations from EDA
- No missing values found
