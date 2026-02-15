# ARTI 308 – Machine Learning  
## Lab 3: Exploratory Data Analysis (EDA) on Chocolate Sales Dataset

---

## 📌 Project Title
Exploratory Data Analysis (EDA) on Chocolate Sales Dataset

Course: ARTI308 – Machine Learning

---

## 📖 Problem Statement

The objective of this lab is to perform **Exploratory Data Analysis (EDA)** on a real-world chocolate sales dataset.

In Machine Learning, data understanding and cleaning represent approximately **70–80% of the project work**. Before building any model, the dataset must be properly inspected, cleaned, and analyzed.

This project focuses on:

- Cleaning and formatting raw data (dates and currency symbols)
- Identifying missing values and duplicates
- Understanding product sales distribution
- Analyzing revenue patterns
- Studying the relationship between shipping volume and revenue
- Tracking monthly revenue trends for business insights

---

## 📂 Dataset Description

The dataset used in this project:

**Chocolate_Sales.csv**

It contains records of chocolate product sales including:

- Product names
- Amount (Revenue)
- Boxes shipped
- Sales dates
- Other relevant business-related attributes

Each row represents a sales transaction.

---

## 🛠 Tools & Libraries Used

The following tools and libraries were used:

- Python
- Pandas (Data cleaning and manipulation)
- NumPy (Numerical operations)
- Matplotlib (Data visualization)
- Seaborn (Advanced visualizations)

---

## 🔎 Exploratory Data Analysis Steps

The following steps were performed in the Jupyter Notebook:

1. Loaded the dataset using Pandas
2. Inspected data structure using:
   - `head()`
   - `info()`
   - `describe()`
3. Cleaned the 'Amount' column:
   - Removed currency symbols
   - Converted values to numeric format
4. Checked for:
   - Missing values
   - Duplicate records
5. Performed correlation analysis
6. Visualized:
   - Revenue distribution by product
   - Monthly revenue trends
   - Relationship between boxes shipped and revenue
7. Generated business insights based on patterns observed

---

## 📊 Key Findings

- The 'Amount' column was successfully cleaned and converted to numeric format.
- The product **"Smooth Sliky Salty"** was identified as the top-performing product in terms of revenue.
- A positive correlation was obse

