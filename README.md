# Udacity-Data-Science-Course-1-Final-Project
This survey is based on "https://media.githubusercontent.com/media/StackExchange/Survey/refs/heads/main/packages/archive/2025/results.csv"

### Table of Contents

- [Installation ](#installation-)
- [Project Motivation](#project-motivation)
- [File Descriptions ](#file-descriptions-)
- [Results](#results)
- [Licensing, Authors, Acknowledgements](#licensing-authors-acknowledgements)

## Installation <a name="installation"></a>

The notebook and script require the standard Python data science stack. The code was developed with Python 3.14.4 and should run with the following packages installed:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- openpyxl

These can be installed via pip if needed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn openpyxl
```

## Project Motivation<a name="motivation"></a>

This project analyzes 2025 software developer survey from [this link]("https://media.githubusercontent.com/media/StackExchange/Survey/refs/heads/main/packages/archive/2025/results.csv") data to explore factors related to annual compensation (`ConvertedCompYearly`) and retained survey attributes. The goal is to:

1. Load and inspect the survey dataset.
2. Select a set of retained variables for analysis.
3. Perform descriptive statistics and generate visualizations for numeric and categorical retained columns.
4. Train and evaluate a regression tree model predicting `ConvertedCompYearly`.

The project is part of Udacity data science nanodegree certification.

## File Descriptions <a name="files"></a>

- `Course2_FinalProject.ipynb`
  - Loads survey data from a raw CSV URL.
  - Filters the dataset to retained columns and performs descriptive analysis.
  - Saves summary statistics and aggregate reports to Excel.
  - Generates histograms, correlation plots, category counts, and scatter plots.
  - Builds a decision tree regression model with `ConvertedCompYearly` as the response variable.


## Results<a name="results"></a>

The code produces:

- Descriptive statistics for retained columns.
- Excel output with statistics, missing counts, and aggregated summaries.
- Plots for numeric distributions, categorical counts, and scatter relationships.
- A regression tree model predicting `ConvertedCompYearly`, including performance metrics and residual analysis.

The main findings of the code can be found at the post available [here](https://medium.com/@kiendre.pro/welcome-to-the-2025-stack-overflow-developer-salary-survey-911d9e1f3492?postPublishedType=initial)

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

The analysis uses publicly available survey data from the Stack Overflow developer survey. Credit goes to Stack Overflow for the survey dataset and to Udacity for the course framework. Use the code freely for learning and exploration.
