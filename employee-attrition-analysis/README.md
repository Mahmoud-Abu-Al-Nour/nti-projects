# Employee Attrition Analysis

> An end-to-end HR Analytics project that explores employee attrition using the IBM HR Analytics Employee Attrition dataset. The project follows the complete data analytics pipeline—from business understanding and data quality assessment to feature engineering, exploratory data analysis (EDA), and feature selection—to generate actionable insights for Human Resources decision-making.

---

# Table of Contents

- Business Scenario
- Business Objectives
- Business Questions
- Dataset
- Project Workflow
- Project Structure
- Technologies
- Generated Datasets
- Current Project Status
- Deliverables
- Expected Business Value
- Future Improvements
- Author

---

# Business Scenario

Employee attrition is one of the most significant challenges facing organizations. High turnover increases recruitment costs, reduces productivity, causes knowledge loss, and negatively impacts employee morale.

As a Data Analyst in IBM's Human Resources department, the objective is to analyze employee data, identify the factors contributing to employee attrition, and provide actionable recommendations that help HR improve employee retention.

---

# Business Objectives

The primary objectives of this project are to:

- Understand employee attrition patterns.
- Identify the main drivers of employee turnover.
- Discover meaningful relationships between employee characteristics and attrition.
- Generate business insights from HR data.
- Support evidence-based HR decision-making.
- Recommend practical strategies to improve employee retention.

---

# Business Questions

This project investigates several key business questions, including:

- Which employees are most likely to leave the company?
- Does overtime increase employee attrition?
- Does monthly income influence employee turnover?
- Which departments experience the highest attrition?
- Does job satisfaction affect employee retention?
- Which employee groups should HR consider high-risk?
- Are promotions associated with lower attrition?
- Does work-life balance influence employee retention?

Additional business questions emerged during the exploratory data analysis.

---

# Dataset

### Dataset Name

IBM HR Analytics Employee Attrition & Performance

The dataset contains employee demographic information, work-related attributes, satisfaction scores, compensation, career progression, and an attrition indicator.

### Target Variable

**Attrition**

- Yes → Employee left the company
- No → Employee stayed with the company

All analyses, hypotheses, and recommendations are centered around this target variable.

---

# Project Workflow

The project follows a structured Business Analytics workflow.

## Phase 1 — Business Understanding

- Business Scenario
- Business Objectives
- Stakeholders
- Business Questions
- Success Criteria

---

## Phase 2 — Dataset Understanding

- Dataset Overview
- Feature Description
- Target Variable
- Data Types
- Business Meaning of Features

---

## Phase 3 — Data Quality Assessment

- Missing Values
- Duplicate Records
- Duplicate Employee IDs
- Invalid Values
- Inconsistent Values
- Constant Features
- Outlier Detection
- Data Validation

---

## Phase 4 — Data Cleaning

- Missing Value Treatment
- Duplicate Removal
- Data Standardization
- Constant Feature Removal
- Outlier Handling
- Data Validation

---

## Phase 5 — Feature Engineering

Business-driven features were created to improve analytical value, including:

- Income per Working Year
- Promotion Rate
- Experience Level
- Employee Tenure Group
- High Income Indicator

---

## Phase 6 — Data Preparation

- Categorical Encoding
- Feature Scaling

---

## Phase 7 — Exploratory Data Analysis (EDA)

Each business question follows a consistent analytical framework:

1. Business Question
2. Hypothesis
3. Visualization
4. Observation
5. Interpretation
6. Business Insight
7. Recommendation

---

## Phase 8 — Feature Selection

Three complementary feature selection techniques were applied:

- Pearson Correlation
- Chi-Square Test
- Mutual Information

---

## Phase 9 — Machine Learning *(Coming Soon)*

The next stage will include:

- Train/Test Split
- Classification Models
- Model Evaluation
- Model Comparison
- Business Recommendations

---

# Project Structure

```text
employee-attrition-analysis/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_business_understanding.ipynb
│   ├── 02_data_quality_assessment.ipynb
│   ├── 03_data_cleaning.ipynb
│   ├── 04_feature_engineering_and_eda.ipynb
│   └── 05_machine_learning.ipynb (Coming Soon)
│
├── reports/
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

# Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn
- Jupyter Notebook
- Git
- GitHub

---

# Generated Datasets

| Dataset | Description |
|----------|-------------|
| **employee_attrition_cleaned.csv** | Cleaned dataset after data cleaning and feature engineering. |
| **employee_attrition_features_selected.csv** | Final dataset containing the selected features and the target variable, ready for machine learning. |

---

# Deliverables

The project currently includes:

- Cleaned Dataset
- Feature-Selected Dataset
- Business Analysis Notebooks
- Feature Engineering
- Exploratory Data Analysis
- Feature Selection
- Business Insights
- HR Recommendations

---

# Key Project Highlights

- Identified and resolved **13 data quality issues**.
- Engineered **five business-driven features**.
- Answered multiple HR business questions using EDA.
- Applied three feature selection techniques:
  - Pearson Correlation
  - Chi-Square Test
  - Mutual Information
- Generated a machine-learning-ready dataset for future modeling.

---

# Expected Business Value

The insights generated from this project help Human Resources teams:

- Reduce employee turnover.
- Improve employee satisfaction.
- Identify high-risk employee groups.
- Optimize promotion and compensation strategies.
- Support evidence-based HR decisions.
- Reduce recruitment and training costs.

---

# Future Improvements

The next phase of this project will include:

- Employee Attrition Prediction using Machine Learning
- Hyperparameter Tuning
- Explainable AI (SHAP / LIME)
- Interactive Power BI Dashboard
- Employee Attrition Risk Prediction API
- HR Decision Support Dashboard

---

# Author

**Mahmoud Abu Al-Nour**

AI Engineer| Data science

GitHub: https://github.com/Mahmoud-Abu-Al-Nour