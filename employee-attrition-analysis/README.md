# Employee Attrition Analysis

> A complete Business Data Analytics project that investigates employee attrition using the IBM HR Analytics Employee Attrition dataset. This project follows the full analytics lifecycle—from understanding the business problem to delivering actionable business recommendations for Human Resources management.

---

# Business Scenario

Employee attrition is one of the most significant challenges facing organizations. High turnover leads to increased recruitment costs, loss of organizational knowledge, reduced productivity, and lower employee morale.

As a Data Analyst in IBM's Human Resources department, the objective is to analyze employee data to identify the key factors contributing to employee attrition and provide data-driven recommendations to improve employee retention.

---

# Business Objectives

The primary objectives of this project are:

- Understand employee attrition patterns.
- Identify the factors influencing employee turnover.
- Discover meaningful relationships between employee characteristics and attrition.
- Generate business insights from HR data.
- Recommend actionable strategies to improve employee retention.
- Support HR decision-making through data analysis.

---

# Business Questions

This analysis aims to answer several business questions, including:

- Which employees are most likely to leave the company?
- Does overtime increase employee attrition?
- Does monthly income influence employee turnover?
- Which departments experience the highest attrition?
- Does job satisfaction affect employee retention?
- Which employee groups should HR consider high-risk?
- Are promotions associated with lower attrition?
- Does work-life balance influence employee retention?

Additional business questions may emerge throughout the exploratory analysis.

---

# Dataset

**Dataset Name**

IBM HR Analytics Employee Attrition & Performance

The dataset contains employee demographic information, work-related attributes, satisfaction scores, compensation, career progression, and an attrition indicator.

### Target Variable

**Attrition**

- Yes → Employee left the company.
- No → Employee stayed with the company.

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

The dataset will be evaluated for:

- Missing Values
- Duplicate Records
- Duplicate Employee IDs
- Incorrect Data Types
- Invalid Values
- Inconsistent Values
- Constant Features
- High Missing Columns
- Outliers

---

## Phase 4 — Data Cleaning

Cleaning tasks include:

- Handling missing values
- Removing duplicate records
- Correcting data types
- Removing constant features
- Handling outliers
- Resolving inconsistent values

---

## Phase 5 — Exploratory Data Analysis (EDA)

For each business question, the project follows a consistent analytical framework:

1. Business Question
2. Hypothesis
3. Variables
4. Visualization
5. Observation
6. Interpretation
7. Business Insight
8. Recommendation

---

## Phase 6 — Feature Engineering

Several business-driven features will be created, including:

- Income per Working Year
- Promotion Rate
- Experience Level
- Employee Tenure Groups
- High Income Indicator
- Satisfaction Score
- Overtime Risk
- Career Stage
- Income Category

Each engineered feature is created with a clear business rationale.

---

## Phase 7 — Executive Summary

A concise summary prepared for non-technical stakeholders highlighting:

- Business context
- Key findings
- Recommendations
- Expected business impact

---

## Phase 8 — Final Business Report

The final report includes:

1. Business Problem
2. Dataset Overview
3. Data Quality Assessment
4. Data Cleaning Summary
5. Exploratory Data Analysis
6. Feature Engineering
7. Business Insights
8. Business Recommendations
9. Executive Summary
10. Appendix

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
│   ├── 04_exploratory_data_analysis.ipynb
│   ├── 05_feature_engineering.ipynb
│   └── 06_executive_summary.ipynb
│
├── reports/
│   ├── Executive_Summary.pdf
│   └── Final_Business_Report.pdf
│
├── images/
│
├── src/
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
- Jupyter Notebook
- Scikit-learn (optional for future modeling)

---

# Deliverables

The final project will include:

- Clean Dataset
- Data Analysis Notebook
- Engineered Features
- Business Insights
- Business Recommendations
- Executive Summary
- Final Business Report

---

# Expected Business Value

The insights generated from this project will help Human Resources teams:

- Reduce employee turnover.
- Improve employee satisfaction.
- Identify high-risk employee groups.
- Optimize promotion and compensation strategies.
- Support evidence-based HR decisions.
- Reduce recruitment and training costs.

---

# Future Improvements

Potential future extensions include:

- Employee Attrition Prediction using Machine Learning
- Interactive HR Dashboard using Power BI or Tableau
- Employee Risk Scoring System
- HR Decision Support Dashboard
- Explainable AI (XAI) for Attrition Prediction

---

# Author

**Mahmoud Abu Al-Nour**

Computer Science Student | Data Analyst | AI Engineer

GitHub: https://github.com/Mahmoud-Abu-Al-Nour