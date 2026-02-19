# Predicting Employee Attrition Using Machine Learning  
### Final Research Implementation – Phase 3

## Project Overview
This repository contains the **final implementation** of a Computer Science research project focused on predicting employee attrition using supervised machine learning techniques.

The project formulates employee attrition as a binary classification problem and evaluates multiple machine learning models to determine their predictive effectiveness.

This repository includes:

- Complete data preprocessing pipeline  
- Exploratory Data Analysis (EDA)  
- Model implementation and evaluation  
- Reproducible Python code  
- Documentation aligned with the final research report

---

## Research Objective

The objective of this study is to:

- Determine whether supervised machine learning models can effectively predict employee attrition  
- Compare linear and ensemble-based classification algorithms  
- Analyze the trade-off between predictive performance and interpretability  

The final research report (submitted separately in PDF format) provides theoretical background, literature review, methodology, empirical results, and critical reflection.

---

## Dataset
The project uses the **IBM HR Analytics Employee Attrition & Performance** dataset, which contains demographic, job-related, and satisfaction-related attributes for employees.

**Dataset source:**  
https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset

The dataset is **not included** in this repository due to licensing considerations. Users should download it directly from Kaggle.

---

## Machine Learning Models Implemented

The following supervised classification models were implemented and evaluated:

- Logistic Regression (baseline model)  
- Decision Tree Classifier  
- Random Forest Classifier (ensemble method)  

Model performance was evaluated using:

- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion matrices  

The Random Forest model achieved the strongest overall predictive performance, consistent with ensemble learning theory.

---

## Tools and Technologies

- **Programming Language:** Python  
- **Environment:** Google Colab / Jupyter Notebook  
- **Libraries:**
  - pandas  
  - NumPy  
  - scikit-learn  
  - matplotlib  
  - seaborn  

All models were implemented using the scikit-learn framework.

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
