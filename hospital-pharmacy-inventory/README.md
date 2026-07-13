# Hospital Pharmacy Inventory Manager

A Pandas data analysis activity focused on cleaning, transforming, and analyzing hospital pharmacy inventory data.

## Project Overview

This project demonstrates an end-to-end data workflow using Pandas.

The goal is to load medicine inventory data, explore the dataset, handle missing values, create new features, filter records, generate statistical summaries, and export the cleaned dataset.

## Workflow

The analysis includes:

1. Loading the medicine inventory dataset.
2. Exploring the first and last records.
3. Identifying missing values in `Price` and `Quantity`.
4. Filling missing `Price` values using the mean price.
5. Filling missing `Quantity` values with `1`.
6. Creating an `Inventory_Value` feature.
7. Filtering well-stocked medicines.
8. Selecting specific rows and columns using `loc`.
9. Generating descriptive statistics.
10. Exporting the cleaned dataset.

## Feature Engineering

A new feature called `Inventory_Value` is calculated using:

```text
Inventory_Value = Price × Quantity
```

This represents the total inventory value of each medicine.

## Filtering

Medicines with a quantity of 15 or more are classified as well-stocked.

```text
Quantity >= 15
```

## Project Structure

```text
Medicine-analysis/
├── Medical.ipynb
└── README.md
```

The original and cleaned CSV datasets are excluded from the repository.

## Skills Practiced

- Data loading with Pandas
- Data exploration
- Missing value detection
- Missing value imputation
- Data cleaning
- Feature engineering
- Boolean filtering
- Data selection using `loc`
- Descriptive statistics
- CSV data export

## Technologies

- Python
- Pandas
- Jupyter Notebook

## Dataset

The project uses `medicine_inventory.csv` as the input dataset.

The dataset is not included in this repository.