# 🧑‍💼 Employee Attrition Classification

This capstone project predicts whether an employee will leave the organization using a synthetically generated IBM HR dataset. The goal is to help companies identify potential attrition risks and reduce turnover.

---

## 📌 Objective

To build a machine learning model that predicts employee attrition based on HR factors like job role, satisfaction level, salary, age, and more.

---

## 📊 Dataset Overview

**Source**: IBM Synthetic HR Dataset  
Target variable: `Attrition` (Yes/No)

Key features include:
- Age, Gender, Department
- Job Role, Job Satisfaction
- Monthly Income, OverTime
- Work-Life Balance, Environment Satisfaction

---

## 🔍 Workflow

### 📋 Data Preprocessing
- Dropped non-informative columns
- Converted categorical data using dummy variables
- Scaled numerical features
- Transformed target labels (Yes → 1, No → 0)

### 📊 Data Visualization
- Attrition rate distribution
- Job role vs attrition
- Monthly income vs attrition
- Heatmaps and pairplots for correlation

### 🧠 Models Used
- Logistic Regression
- Random Forest (with GridSearchCV for tuning)

### 🧪 Evaluation Metrics
- Accuracy Score
- Confusion Matrix
- Classification Report

---

## 🧰 Tech Stack

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn

---

## 🚀 Getting Started

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/employee-attrition-classification.git
   cd employee-attrition-classification
