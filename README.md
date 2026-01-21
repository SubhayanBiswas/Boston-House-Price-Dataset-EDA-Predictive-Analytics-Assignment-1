# Predictive Analytics Project 1: Boston Housing Analysis

## Overview
This project contains an introductory analysis of the 'Boston' housing dataset, originally from the MASS Library of R. The notebook walks through data loading, inspection, and visualization to understand the relationships between the median value of owner-occupied homes and various predictors.

## Dependencies
To run this notebook, you will need the following Python libraries:
* `pandas`
* `numpy`
* `matplotlib`
* `seaborn`
* `scipy`
## Dataset
The analysis uses the **Boston Housing Data**.
* **Dimensions:** 506 rows × 15 columns.
* **Description:** Each row represents a set of observations for a specific suburb or town.

### Key Variables analyzed:
* **`medv`**: Median value of owner-occupied homes in $1000s (Response Variable).
* **`crim`**: Per capita crime rate by town.
* **`nox`**: Nitrogen oxides concentration (parts per 10 million).
* **`black`**: Proportions of blacks by town ($1000(Bk - 0.63)^2$).
* **`lstat`**: Lower status of the population (percent).

## Analysis Workflow
1.  **Data Ingestion**: Loading the raw CSV data into a Pandas DataFrame.
2.  **Structure & Class Report**: Identifying the dataset dimensions and variable types using `df.info()`.
3.  **Subsetting**: Isolating specific variables (`medv`, `crim`, `nox`, `black`, `lstat`) to create a focused mini-dataset for analysis.
4.  **Exploratory Visualization**: Generating scatter plots to observe the correlation between the median home value (`medv`) and the selected predictors.

## Usage
Open `Predictive_Analytics_Project_1.ipynb` in Jupyter Notebook or Google Colab and run the cells sequentially to reproduce the analysis and graphs.
