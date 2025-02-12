# Data Cleaning and Analysis Project

## 📌 Project Overview

This project focuses on cleaning, transforming, and analyzing an employee sales dataset. The raw data contained missing values, incorrect data types, and required feature engineering to extract meaningful insights.

## 🔧 Steps Taken

### 1️⃣ Data Collection

- The dataset was created to include missing values and inconsistencies to simulate real-world scenarios.
- It contains employee information, sales records, and performance ratings.

### 2️⃣ Handling Missing Values

- Identified missing values using `.isnull().sum()`.
- Filled missing salary values with the median salary.
- Dropped columns where more than 50% of the data was missing.

### 3️⃣ Data Type Conversion

- Converted `Date_of_Birth` to datetime format.
- Ensured `Salary` was stored as a float.

### 4️⃣ Feature Engineering

- **Calculated Employee Age** by subtracting `Date_of_Birth` from the current date.
- **Created a 'Status' Column** based on `Performance_Rating`:
  - "Excellent" → "Good"
  - "Good" → "Average"
  - "Average" → "Needs Improvement"

### 5️⃣ Data Analysis

- **Total sales per employee** were computed.
- **Employee age distribution** was analyzed.
- **Pivot table** was created to display total sales per region and product.

## 📚 Technologies Used

- Python 🐍
- Pandas 📊
- NumPy 🔢
- Jupyter Notebook 📒



## 📌 Conclusion

This project demonstrates essential data cleaning techniques, feature engineering, and exploratory data analysis. The cleaned dataset is now ready for further machine learning or business intelligence applications.

---

📢 Feel free to contribute or share feedback! 😊

