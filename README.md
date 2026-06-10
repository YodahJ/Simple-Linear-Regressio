# Simple Linear Regression: Marketing ROI Analysis

## Project Overview

This project analyzes a marketing dataset using Python and statsmodels to build a Simple Linear Regression model. The goal is to identify which marketing channel (TV, Radio, or Social Media) has the strongest correlation with Sales and determine the optimal budget allocation strategy based on ROI analysis.

## Objectives

- Load and explore the marketing dataset; handle missing values
- Perform exploratory data analysis (EDA) with visualizations
- Identify the independent variable most correlated with Sales
- Build an OLS regression model using statsmodels
- Create diagnostic plots to validate model assumptions (Linearity, Normality, Homoscedasticity)
- Interpret R-squared, coefficients, and p-values in business context
- Formulate ROI-based recommendations for marketing budget allocation

## Environment Setup

### Prerequisites
- Python 3.7+
- pip (Python package manager)

### Installation

Clone the repository:
```bash
git clone https://github.com/YodahJ/Simple-Linear-Regressio.git
cd Simple-Linear-Regressio
```

Install required packages:
```bash
pip install pandas numpy seaborn matplotlib statsmodels scikit-learn jupyter
```

### Required Packages
- **pandas**: Data manipulation and analysis
- **numpy**: Numerical computing
- **matplotlib**: Plotting and visualization
- **seaborn**: Statistical data visualization
- **statsmodels**: Statistical modeling and OLS regression
- **scikit-learn**: Machine learning tools
- **jupyter**: Interactive notebook environment

## Project Files

- `regression_analysis.ipynb` - Main Jupyter notebook with complete analysis
- `marketing_and_sales_data_evaluate_lr.csv` - Marketing dataset (177 KB)
- `README.md` - Project documentation

## Running the Analysis

1. Start Jupyter notebook:
```bash
jupyter notebook
```

2. Open `regression_analysis.ipynb` and run all cells to execute the complete analysis

3. Review the output, visualizations, and statistical results

## Key Results Summary

The analysis includes:
- **Exploratory Data Analysis**: Distribution analysis, correlation heatmaps, and relationship visualizations
- **Variable Selection**: Identification of the marketing channel with highest correlation to Sales
- **OLS Regression Model**: Statistical modeling with coefficients, p-values, and R-squared
- **Assumption Validation**: 
  - Linearity: Scatter plots with regression lines
  - Normality: Q-Q plots and histograms of residuals
  - Homoscedasticity: Residual variance analysis
- **Business Recommendations**: ROI-based insights for marketing budget allocation

## Statistical Interpretation

The model output includes:
- **R-squared**: Proportion of variance in Sales explained by the independent variable
- **Coefficients**: Impact of a one-unit increase in the marketing channel on Sales
- **P-values**: Statistical significance of the relationship
- **Confidence Intervals**: Range of plausible coefficient values

## Marketing Channel Comparison

Each marketing channel is analyzed to determine:
- Strength of relationship with Sales (correlation coefficient)
- Statistical significance (p-value)
- Return on investment (ROI) per unit of spending

## Author

YodahJ

## License

This project is provided as-is for educational purposes.

## Dataset

The `marketing_and_sales_data_evaluate_lr.csv` file contains marketing spend data across multiple channels and corresponding sales figures.
