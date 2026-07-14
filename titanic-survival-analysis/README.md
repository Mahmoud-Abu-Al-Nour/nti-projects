# Titanic Survival Data Analysis

A data preparation and exploratory analysis project using the Titanic dataset and Pandas.

## Project Overview

This project demonstrates a practical data analysis workflow on raw Titanic passenger data.

The analysis focuses on exploring the dataset, selecting relevant features, filtering records, handling missing values, creating new features, detecting duplicate records, and analyzing passenger survival patterns.

## Project Workflow

The project covers:

1. Dataset exploration
2. Column selection
3. Boolean filtering
4. Data sorting
5. Age group feature creation
6. Missing value handling
7. Duplicate detection and removal
8. Survival rate analysis using GroupBy
9. Survival analysis using Pivot Tables
10. Passenger title extraction and analysis
11. Cleaned dataset export

## Data Cleaning

Missing values are handled using different strategies based on the characteristics of each feature:

- `Age` — Missing values are filled using the median age.
- `Cabin` — Missing values are labeled as `Unknown`.
- `Embarked` — Missing values are filled using the most frequent value.

Duplicate rows are also checked and removed when necessary.

## Feature Engineering

### Age Group

Passenger ages are categorized into:

- Child
- Teen
- Adult
- Senior

### Passenger Title

Passenger titles such as `Mr`, `Mrs`, and `Miss` are extracted from the `Name` column using regular expressions.

These features provide additional information for survival analysis.

## Survival Analysis

Survival rates are analyzed based on:

- Passenger sex
- Passenger class
- Passenger title

GroupBy operations and pivot tables are used to compare survival patterns across passenger groups.

## Project Structure

```text
titanic-survival-analysis/
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
│   └── titanic_data_preparation.ipynb
├── src/
├── README.md
└── requirements.txt
```

The raw and processed datasets are excluded from the repository.

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Installation

Create and activate a virtual environment, then install the project dependencies:

```bash
python -m pip install -r requirements.txt
```

## Running the Project

Open the notebook located in:

```text
notebooks/titanic_data_preparation.ipynb
```

Run all notebook cells from top to bottom.

The cleaned dataset is generated inside:

```text
data/processed/
```

## Skills Practiced

- Data exploration
- Data selection
- Boolean filtering
- Data sorting
- Missing value imputation
- Feature engineering
- Regular expressions
- Duplicate handling
- GroupBy operations
- Pivot tables
- Data export