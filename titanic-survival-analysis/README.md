# Titanic Survival Data Analysis

A practical data analysis project using the Titanic dataset to apply data preparation, preprocessing, feature engineering, statistical analysis, outlier detection, and data visualization techniques.

---

## Project Overview

This project demonstrates a complete end-to-end data analysis workflow using Python and the Titanic dataset.

Starting from the raw dataset, the project walks through data assessment, cleaning, preprocessing, exploratory data analysis (EDA), feature engineering, and statistical visualization. The prepared dataset will serve as the foundation for future machine learning models.

---

# Project Workflow

The project is organized into three stages.

## 1. Data Preparation and Analysis

- Dataset exploration
- Column selection
- Boolean filtering
- Data sorting
- Missing value handling
- Duplicate detection and removal
- Age group feature creation
- Passenger title extraction
- GroupBy analysis
- Pivot table analysis
- Cleaned dataset export

---

## 2. Statistical Analysis and Visualization

- Mean, median, and mode analysis
- Standard deviation and grouped variability
- Five-number summary
- Interquartile range (IQR)
- IQR-based outlier detection
- Z-score outlier detection
- Distribution analysis
- Histograms and KDE
- Box plots
- Count plots
- Scatter plots
- Multi-chart statistical dashboard
- Visual insight interpretation

---

## 3. End-to-End Data Science Workflow

This stage simulates a real-world data science workflow starting from the original raw dataset.

### Data Assessment

- Dataset inspection
- Shape and information summary
- Missing value analysis
- Duplicate detection
- Unique value inspection
- Outlier identification

### Data Cleaning

- Missing value imputation
- Duplicate removal
- Data type optimization
- Fare outlier handling using the IQR method

### Data Preparation

- Label Encoding
- One-Hot Encoding
- Feature Scaling using StandardScaler

### Exploratory Data Analysis (EDA)

- Age distribution
- Survival analysis
- Correlation heatmap
- Feature relationships

### Feature Engineering

New features created:

- FamilySize
- IsAlone
- AgeGroup

### Reflection

The workflow concludes with observations about:

- Data quality
- Cleaning decisions
- Engineered features
- Important insights discovered during EDA

---

# Data Cleaning

Missing values are handled using feature-specific strategies.

- `Age` → Median
- `Cabin` → Unknown
- `Embarked` → Mode

Duplicate records are detected and removed when necessary.

Fare outliers are handled using the IQR method.

---

# Feature Engineering

The project creates several useful features.

## Age Group

Passengers are categorized into:

- Child
- Teen
- Adult
- Senior

## Passenger Title

Passenger titles such as:

- Mr
- Mrs
- Miss
- Master

are extracted from the `Name` column using regular expressions.

## Family Size

```text
FamilySize = SibSp + Parch + 1
```

## Is Alone

Binary feature indicating whether a passenger traveled alone.

---

# Statistical Analysis

The project analyzes passenger characteristics using:

- Mean
- Median
- Mode
- Standard deviation
- Quartiles
- Interquartile Range (IQR)

Outliers are detected using:

- IQR Method
- Z-Score Method

---

# Data Visualization

Visualizations include:

- Passenger age distribution
- Fare distribution
- Fare variability by passenger class
- Passenger survival counts
- Correlation heatmap
- Scatter plots
- Count plots
- Histograms
- KDE plots
- Box plots
- Multi-chart dashboard

---

# Project Structure

```text
titanic-survival-analysis/
│
├── data/
│   ├── raw/
│   │   └── .gitkeep
│   └── processed/
│       └── .gitkeep
│
├── notebooks/
│   ├── titanic_data_preparation.ipynb
│   ├── titanic_statistics_visualization.ipynb
│   └── titanic_end_to_end_workflow.ipynb
│
├── src/
│   └── .gitkeep
│
├── README.md
└── requirements.txt
```

Raw and processed datasets are excluded from the repository.

---

# Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- SciPy
- Jupyter Notebook

---

# Installation

```bash
python -m pip install -r requirements.txt
```

---

# Running the Project

Run the notebooks in the following order:

```text
1. titanic_data_preparation.ipynb
2. titanic_statistics_visualization.ipynb
3. titanic_end_to_end_workflow.ipynb
```

---

# Skills Practiced

- Data Assessment
- Data Cleaning
- Data Preprocessing
- Feature Engineering
- Missing Value Handling
- Encoding Techniques
- Feature Scaling
- Exploratory Data Analysis (EDA)
- Descriptive Statistics
- Outlier Detection
- GroupBy Operations
- Pivot Tables
- Correlation Analysis
- Data Visualization
- Statistical Interpretation
- End-to-End Data Science Workflow

---

# Future Work

The next stage of this project will focus on building machine learning models using the prepared dataset.

Planned topics include:

- Train/Test Split
- Classification Models
- Model Evaluation
- Hyperparameter Tuning
- Model Comparison
- Feature Importance