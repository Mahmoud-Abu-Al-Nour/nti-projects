# Titanic Data Analysis

## Overview

This project presents an Exploratory Data Analysis (EDA) of the Titanic dataset using Python. The objective is to understand the dataset, assess its quality, explore relationships between variables, and identify the factors that influenced passenger survival.

---

## Objectives

- Understand the dataset structure
- Perform data quality assessment
- Analyze missing values
- Generate descriptive statistics
- Explore feature distributions
- Analyze survival patterns
- Visualize relationships between variables
- Summarize key insights

---

## Dataset

The dataset contains information about Titanic passengers, including:

- Survived
- Passenger Class (Pclass)
- Name
- Sex
- Age
- Siblings/Spouses Aboard
- Parents/Children Aboard
- Fare

---

## Project Structure

```text
Titanic-project/
│
├── data/
│   └── row/
│       └── .gitkeep
│
├── notebooks/
│   └── 01_data_exploration.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Jupyter Notebook

---

## Exploratory Data Analysis

The notebook includes:

- Dataset overview
- Data types inspection
- Missing values analysis
- Duplicate detection
- Descriptive statistics
- Feature distribution analysis
- Survival analysis
- Correlation analysis
- Data visualization

---

## Key Findings

- Female passengers had a higher survival rate than male passengers.
- First-class passengers were more likely to survive.
- Age contains missing values that require preprocessing.
- Fare is positively associated with survival.
- Passenger class is an important factor influencing survival.

---

## How to Run

Clone the repository:

```bash
git clone https://github.com/Mahmoud-Abu-Al-Nour/titanic-project.git
```

Navigate to the project directory:

```bash
cd titanic-project
```

Create and activate a virtual environment:

```bash
python -m venv .venv
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
notebooks/01_data_exploration.ipynb
```

---

## Future Work

- Data Cleaning
- Feature Engineering
- Machine Learning Model Development
- Model Evaluation
- Model Deployment

---

## Author

Mahmoud Abu AlNour

Computer Science Student

Interested in Data Analysis, Machine Learning, Artificial Intelligence, and MLOps.