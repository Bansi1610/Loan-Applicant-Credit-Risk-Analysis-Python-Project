# Loan Applicant Credit Risk Analysis using Python & KNN

## 📌 Project Overview

This project analyzes loan applicant data to understand applicant risk segmentation using Python, Exploratory Data Analysis (EDA), data visualization, and a K-Nearest Neighbors (KNN) classification model.

The dataset contains information related to applicant age, total work experience, years in the city, cost-to-request ratio, CIBIL score, overdrafts, and total bounces in the past 12 months.

The project focuses on exploring the data, checking data quality, visualizing important variables, building a KNN classification model, and evaluating model performance across different K values.

---

## 🎯 Project Objective

The main objectives of this project are to:

- Explore and understand loan applicant data
- Check the dataset for null values and basic data quality
- Generate descriptive statistics
- Analyze relationships between applicant characteristics
- Identify the target and feature variables
- Build a KNN classification model
- Evaluate training and testing performance
- Compare model performance for K values from 1 to 14
- Analyze the accuracy of the classification model

---

## 📊 Dataset

The dataset contains **8,995 loan applicant records** with the following variables:

| Variable | Description |
|---|---|
| Age | Age of the loan applicant |
| Total Work Experience | Applicant's total work experience |
| Number of years in city | Number of years the applicant has lived in the city |
| Cost to Request Ratio | Cost-to-request ratio |
| Cibil score | Applicant's CIBIL score |
| Overdrafts past12months | Number of overdrafts in the past 12 months |
| Total bounces past12months | Number of bounces in the past 12 months |

---

## 🔍 Exploratory Data Analysis

The following analysis was performed during the project:

- Dataset loading and inspection
- Null value checking
- Basic information about the dataset
- Descriptive statistical analysis
- Scatter plot between Age and Total Work Experience
- Box plot for Age
- Box plot for CIBIL Score

These visualizations help understand the distribution of applicant characteristics and identify potential patterns and outliers in the dataset.

---

## 🎯 Features & Target

### Target Variable

```text
Total bounces past12months

---

## 🤖 Machine Learning Model

A K-Nearest Neighbors (KNN) classifier was used for the classification task.

The dataset was divided into:

- 80% Training Data
- 20% Testing Data

The model was evaluated using:

- Training Score
- Testing Score
- Accuracy Score

---

## 📈 Model Evaluation

The initial KNN model produced the following results:

- Metric	Score
- Training Score	67.51%
- Testing Score	64.54%
- Accuracy	64.54%

The model was further evaluated using different K values ranging from 1 to 14 to compare training and testing performance and understand the effect of K on model performance.

---

##🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Microsoft Excel

---

##💡 Key Concepts

- Data exploration
- Data quality checking
- Exploratory Data Analysis
- Data visualization
- Feature and target selection
- Train-test split
- KNN classification
- Model evaluation
- Accuracy analysis
- Comparison of different K values

---

## 📁 Structure

Loan-Applicant-Credit-Risk-Analysis-Python
│
├── README.md
├── Loan Applicant Credit Risk Analysis.ipynb
└── Loan Applicant Risk Segmentation Dataset.xlsx

---

##💡Outcome

This project demonstrates the application of Python-based exploratory data analysis and KNN classification to analyze loan applicant information and evaluate risk segmentation performance across different K values.

---

👩‍💻 Author

Bansi Hadiyal

MIS & Reporting Analyst | Data Analytics | SQL | Excel | Tableau

GitHub: https://github.com/Bansi1610
LinkedIn: https://www.linkedin.com/in/bansi-hadiyal
