# Assignment 1 - Linear Regression

Dataset: [Liver Disorders Dataset (UCI)](https://archive.ics.uci.edu/dataset/60/liver+disorders)
Public Link to File: [https://raw.githubusercontent.com/LamisaZara/CS4372_Assignment1/main/bupa.data]

## Requirements
Python 3x with the following libraries:
- pandas
- numpy
- scikit-learn
- statsmodels
- matplotlib
- seaborn

## How to Run
1. Open `CS4372_Assignment1_LT.ipynb` in Jupyter Notebook or Google Colab.
2. Run all cells in order.

## Assumptions- also discussed in report
- Removed the `selector` variable since it’s not a feature or target.
- Checked dataset: no missing values, all numeric.
- Standardized features before using SGDRegressor.
- Dropped `alkphos` (weak correlation) and averaged `sgpt`/`sgot` (to reduce multicollinearity).
- All feature variables should have positive (or at least non-negative) correlation with target.
