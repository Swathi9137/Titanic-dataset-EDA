# 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

This project is part of an AI & ML Internship Task (Task 2). It focuses on understanding the Titanic dataset through descriptive statistics and data visualization using Python.

## 📌 Objectives

- Generate summary statistics
- Visualize data distributions using histograms and boxplots
- Identify relationships and patterns using pairplots and correlation heatmaps
- Detect missing values, skewness, and outliers
- Make feature-level observations

## 📂 Files Included

- `titanic_eda.ipynb`: Google Colab notebook with complete EDA code
- `titanic.csv`: Dataset used (from Kaggle)
- `README.md`: Project overview

## 🛠️ Tools & Libraries

- Python (Pandas, Seaborn, Matplotlib)
- Google Colab
- Titanic Dataset from [Kaggle](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

## 📊 Key Visualizations

- Histograms for numerical columns (`Age`, `Fare`)
- Boxplots to detect outliers
- Correlation matrix heatmap
- Pairplot colored by survival

## 🔍 Observations

- Missing values exist in `Age`, `Cabin`, and `Embarked`
- `Fare` contains visible outliers
- `Fare` and `Survived` show a positive correlation
- `Age` and `Fare` distributions are slightly skewed

## ✅ How to Run

1. Open the notebook in [Google Colab]
2. Upload the `titanic.csv` file when prompted
3. Run each cell to view the analysis and plots
