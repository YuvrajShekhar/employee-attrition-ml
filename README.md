# Predicting Employee Attrition Using Machine Learning  
### Phase 2 – Development Draft

## Project Overview
This repository contains the Phase 2 development draft for a Computer Science project focused on predicting employee attrition using supervised machine learning techniques.

The project investigates whether employee attrition can be modeled as a binary classification problem using structured human resources data. This repository represents the current development status and **does not** contain the final implementation.

---

## Problem Description
Employee attrition has significant organizational and economic implications. From a computer science perspective, attrition prediction can be formulated as a supervised learning task, where historical employee data is used to predict whether an employee is likely to leave an organization.

The objective of this project is to explore baseline and ensemble machine learning models, evaluate their suitability for the task, and establish a foundation for further refinement in the final project phase.

---

## Dataset
The project uses the **IBM HR Analytics Employee Attrition & Performance** dataset, which contains demographic, job-related, and satisfaction-related attributes for employees.

**Dataset source:**  
https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset

The dataset is **not included** in this repository due to licensing considerations. Users should download it directly from Kaggle.

---

## Methods and Tools
- **Programming Language:** Python  
- **Environment:** Jupyter Notebook (Google Colab)  
- **Libraries:**
  - pandas
  - NumPy
  - scikit-learn
  - matplotlib
  - seaborn

### Machine Learning Models Explored
- Logistic Regression
- Decision Tree
- Random Forest

These models are used to establish baseline performance and guide further development decisions.

---

## Repository Structure
```text
employee-attrition-ml/
│
├── notebooks/
│   └── Employee_Attrition_Analysis_progress.ipynb
│
├── data/
│   ├── HR-Employee-Attrition_data.csv
│   ├── readme.md
│
├── requirements.txt
│
└── README.md
