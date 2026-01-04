# Survey Data Cleaning and Feature Engineering

## 🧩 Project Overview
This project focuses on end-to-end **data wrangling, feature engineering, and preprocessing** using developer survey data. The goal is to transform raw survey data into a clean, structured, and analysis-ready dataset by handling missing values, standardizing categories, scaling compensation data, and engineering new meaningful features.

This workflow demonstrates essential data-analyst skills including:
data preparation, cleaning, transformation, encoding, and exploratory interpretation.

---

## 🎯 Objectives

- Identify and remove duplicate records  
- Detect and handle missing values (numeric + categorical)
- Standardize inconsistent text values (Country, Employment etc.)
- Group and simplify complex categories
- Apply one-hot encoding to categorical fields
- Normalize and log-transform compensation data
- Create a new **ExperienceLevel** feature from `YearsCodePro`
- Visualize distributions and transformed features

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

## 📊 Key Data Cleaning & Transformation Steps

### ✔ Duplicate Handling
- Identified duplicate rows
- Removed duplicates to prevent biased analysis

### ✔ Missing Value Treatment
- Numeric columns → imputed using **median**
- Categorical columns → imputed using **mode**

### ✔ Category Standardization
- Cleaned inconsistent values in fields like **Country** and **Employment**
- Applied mapping and text normalization

### ✔ Employment Grouping + Encoding
- Grouped multiple employment combinations into meaningful categories
- Applied **one-hot encoding** to `Employment_Grouped`

### ✔ Compensation Feature Scaling
- Used **Min-Max normalization (0–1 range)**
- Applied **log-transformation** to reduce skewness
- Compared distributions using histograms

### ✔ Experience Level Feature Engineering
Created `ExperienceLevel` from `YearsCodePro` with groups:

- Beginner (0–1 yrs)
- Junior (2–4 yrs)
- Mid-Level (5–9 yrs)
- Senior (10–14 yrs)
- Expert (15+ yrs)
- Unknown (missing values)

---


## 🎓 Learning Outcomes

This project demonstrates practical data-analyst capabilities:

- Data wrangling & preprocessing
- Handling real-world messy survey data
- Encoding, normalization, and transformation
- Feature engineering for analysis
- Interpreting and explaining results

---

## 👤 Author

**Vidya Vishnuvihar Geetha**  
Aspiring Data Analyst — United Kingdom (Scotland)

---



## 🏁 Conclusion

This project converts raw survey data into a clean, structured, and insight-ready dataset through systematic data wrangling and feature engineering — a core skillset for real-world data analytics.
