# ARTI 308 – Machine Learning  
## Lab 2: Identifying ML Problems, Selecting Open Datasets, and Designing a Methodology

---

## 📌 Lab Objective

The goal of this lab was to:

- Identify the type of a Machine Learning problem  
- Select a suitable open-source dataset  
- Define the target variable (if supervised)  
- Write a clear problem statement  
- Load and inspect the dataset using Python  
- Design a methodology diagram representing the ML workflow  

---

## 📂 Dataset Selection

For this lab, a **House Prices dataset** was selected from an open-source platform.

The dataset is in **CSV format** and contains tabular data where:

- Each row represents a house  
- Each column represents a feature (such as size, location, etc.)  

This dataset is suitable for a machine learning prediction task.

---

## 🎯 Machine Learning Problem Type

This is a **Supervised Learning – Regression** problem.

Regression is used because the goal is to **predict a numerical value**, which is:

> **House Price**

---

## 🏷️ Target Variable

The target variable in this dataset is:

**Price (House Price)**

The model is expected to learn how different features affect the house price.

---

## 🧠 Problem Statement

The objective of this project is to predict house prices based on available features such as house size, location, and other characteristics.

The machine learning model will learn the relationship between the input features and the house price from the dataset.

---

## 🐍 Jupyter Notebook Work

In the Jupyter Notebook (`lab2_house_prices.ipynb`), the following steps were performed:

1. Imported the Pandas library
2. Loaded the dataset (`data.csv`)
3. Displayed the dataset shape (rows and columns)
4. Previewed the first few rows of the dataset
5. Displayed column names
6. Checked data types and missing values
7. Generated basic statistical summaries

This step was done to understand the structure of the dataset before applying any machine learning techniques.

---

## 🗺️ Methodology Diagram

A methodology diagram was created to visually represent the machine learning workflow:

1. Dataset Selection  
2. Data Loading  
3. Data Preprocessing  
4. Train/Test Split  
5. Model Training  
6. Model Evaluation  
7. Results  

The diagram is included in this repository as:

`methodology_diagram.png`

---

## 📁 Repository Contents

- `README.md` – Lab description and explanation  
- `data.csv` – House Prices dataset  
- `lab2_house_prices.ipynb` – Jupyter Notebook  
- `methodology_diagram.png` – Workflow diagram  

---

## 🚀 GitHub Submission

This repository was created and uploaded to GitHub following the instructions provided in the Git & GitHub manual :contentReference[oaicite:1]{index=1}.

The repository includes all required files and is accessible for grading.

---

## ✅ Conclusion

Through this lab, I learned how to:

- Identify machine learning problem types  
- Select an appropriate dataset  
- Define a clear ML objective  
- Inspect data using Python  
- Organize a complete ML workflow  

This lab focused on understanding the structure of a machine learning project rather than implementing a full model.
