# Titanic Survival Data Analysis

A practical data analysis project using the Titanic dataset to apply data preparation, statistical analysis, outlier detection, and data visualization techniques.

## Project Overview

This project demonstrates an end-to-end data analysis workflow using Python and Pandas.

The project starts with raw Titanic passenger data, performs data cleaning and feature engineering, and then applies statistical and visual analysis to understand passenger characteristics and survival patterns.

## Project Workflow

The project is divided into two main stages:

### 1. Data Preparation and Analysis

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

### 2. Statistical Analysis and Visualization

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

## Data Cleaning

Missing values are handled using feature-specific strategies:

- `Age` — filled using the median.
- `Cabin` — labeled as `Unknown`.
- `Embarked` — filled using the mode.

Duplicate records are also detected and removed when necessary.

## Feature Engineering

Two additional features are created during data preparation:

### Age Group

Passengers are categorized into:

- Child
- Teen
- Adult
- Senior

### Passenger Title

Passenger titles such as `Mr`, `Mrs`, and `Miss` are extracted from the `Name` column using regular expressions.

## Statistical Analysis

The project analyzes the central tendency and spread of passenger fares using:

- Mean
- Median
- Mode
- Standard deviation
- Quartiles
- Interquartile range

Fare outliers are detected using both the IQR and Z-score methods.

## Data Visualization

The project uses statistical visualizations to analyze:

- Passenger age distribution
- Fare distribution
- Fare variability by passenger class
- Passenger survival counts
- The relationship between age, fare, and survival

A 2×2 dashboard combines multiple visualizations for comparative analysis.

## Project Structure

```text
titanic-survival-analysis/
├── data/
│   ├── raw/
│   │   └── .gitkeep
│   └── processed/
│       └── .gitkeep
├── notebooks/
│   ├── titanic_data_preparation.ipynb
│   └── titanic_statistics_visualization.ipynb
├── src/
│   └── .gitkeep
├── README.md
└── requirements.txt
```

Raw and processed datasets are excluded from the repository.

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook

## Installation

Install the project dependencies using:

```bash
python -m pip install -r requirements.txt
```

## Running the Project

Run the notebooks in the following order:

```text
1. notebooks/titanic_data_preparation.ipynb
2. notebooks/titanic_statistics_visualization.ipynb
```

The first notebook prepares and cleans the raw dataset.

The second notebook applies statistical analysis and data visualization techniques.

## Skills Practiced

- Data cleaning
- Data preprocessing
- Feature engineering
- Descriptive statistics
- Outlier detection
- GroupBy operations
- Pivot tables
- Statistical interpretation
- Data visualization
- Visual insight extraction
