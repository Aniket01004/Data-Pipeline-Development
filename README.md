# Data-Pipeline-Development

COMPANY: CODTECH IT SOLUTIONS

NAME: ANIKET BHOGE

INTERN ID:CT06DF1221

DOMAIN: DATA SCIENCE

DURATION: 6 WEEKS

MENTOR: NEELA SANTOSH
# 📊 Data Preprocessing ETL Pipeline using Pandas and Scikit-learn

This project is part of the **CODTECH Virtual Internship in Data Science under Task 1**, which focuses on building a simple yet effective **ETL (Extract, Transform, Load)** pipeline using Python. The goal is to automate core data preprocessing steps that are essential in real-world data science workflows using **Pandas** and **Scikit-learn**.

---

## 🚀 Project Objective

The main objective of this task is to demonstrate how to clean and transform raw data into a structured, machine-learning-ready format. The project walks through the complete ETL process using the **Iris dataset**, a popular dataset in the data science community.

This task showcases real-world preprocessing tasks such as handling missing values, encoding categorical variables, and feature scaling — key steps before applying machine learning algorithms.

---

## 🛠 Tools and Libraries Used

- **Python**: Core programming language for implementation
- **Pandas**: For data loading, exploration, and manipulation
- **Scikit-learn**: For preprocessing tasks like scaling and encoding
- **Jupyter Notebook**: Used for a clean, step-by-step walkthrough with code and output

---

## 📂 Project Structure

- `task_1.ipynb`: The Jupyter Notebook containing the complete ETL pipeline
- `iris_processed_features.csv`: Output file containing transformed feature data
- `iris_target.csv`: Target labels extracted from the dataset
- `iris_preprocessor.pkl`: Saved Scikit-learn pipeline for reuse
- `README.md`: Project documentation file

---

## 🔄 ETL Process Overview

### 1. Extract
- Load the **Iris dataset**
- Perform basic data inspection and validation

### 2. Transform
- Normalize numeric columns (`sepal_length`, `sepal_width`, etc.) using `StandardScaler`
- No missing values or categorical features in Iris, so basic scaling is applied
- Pipeline built using Scikit-learn’s `ColumnTransformer`

### 3. Load
- The cleaned and transformed features are saved to a new CSV file
- The target column (`Species`) is saved separately
- The preprocessing pipeline is stored using `joblib` for future use

---

## 💡 Key Features

- Entire ETL process is implemented in a **single notebook** for simplicity
- **Beginner-friendly** and well-commented code
- Demonstrates best practices for preprocessing workflows in data science
- Can be **adapted easily** for other datasets with minor modifications

---

## 📌 How to Use

1. Clone or download this repository
2. Make sure you have `pandas`, `scikit-learn`, and `joblib` installed:
   ```bash
   pip install pandas scikit-learn joblib
3. Open the notebook:
   jupyter notebook iris_etl_pipeline.ipynb
4. Run each cell step by step to follow the ETL process


📚 Learning Outcomes
Through this task, I gained hands-on experience in:

1. Automating end-to-end data preprocessing workflows

2. Using Scikit-learn tools like StandardScaler and ColumnTransformer

3. Structuring ETL pipelines for real-world datasets

4. Saving transformed datasets and preprocessing pipelines for reuse


