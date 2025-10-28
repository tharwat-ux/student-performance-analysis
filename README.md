# Students Data Analysis Project

## Description
This project analyzes a student dataset to explore relationships between categorical variables (like gender, race, and alive status). 
It includes:
- Contingency tables
- Proportion tables
- Chi-square tests
- Z-tests for proportions
- Correlation analysis for categorical variables

## Dataset
The dataset used is `Students.csv` (or describe source if public). 
Columns include:
- `gender`: Male/Female
- `race`: Categorical group
- `alive`: Binary outcome (0/1)
- `lunch`: Standard / Free or Reduced

## Features
- Calculates contingency tables using `pd.crosstab`
- Converts contingency tables to proportions
- Performs Chi-square tests for independence
- Performs Z-tests for proportions between groups
- Spearman correlation for ordinal categorical variables

## How to Run
1. Clone the repository:
```bash
git clone <repo-url>
```
2. install depndencies
```python
pip install pandas scipy statsmodels
```
3. Run
