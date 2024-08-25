# Dynamic Pricing Strategy for Cab Fare

This project explores a dynamic pricing strategy for cab fares using various regression techniques. The goal is to implement and evaluate linear regression, Ridge regression, and Lasso regression models to optimize fare pricing based on demand and supply factors.

## Project Overview

The project involves:
- **Exploring Linear Regression**: Building and validating a basic linear regression model.
- **Applying Ridge Regression**: Implementing Ridge regression to handle multicollinearity and improve model performance.
- **Applying Lasso Regression**: Implementing Lasso regression to enhance model selection and regularization.
- **Assumption Testing**: Verifying assumptions like multicollinearity and heteroscedasticity for linear regression.

### Achievements
- **Adjusted R² of 82.3%**: Achieved this score on the test data using Ridge Regression, demonstrating the effectiveness of the model.

## Files in the Repository

- **`data/`**: This directory contains the data file used for analysis. 
  - `data_file.csv`: The dataset used for modeling.

- **`notebooks/`**: This directory contains the Jupyter notebook file.
  - `dynamic_pricing_analysis.ipynb`: The IPython notebook containing the analysis, model implementations, and results.

## Requirements

To run the code and reproduce the results, you'll need the following Python packages:

- `numpy`
- `pandas`
- `matplotlib`
- `scikit-learn`
- `statsmodels`

You can install the required packages using pip:

```bash
pip install numpy pandas matplotlib scikit-learn statsmodels