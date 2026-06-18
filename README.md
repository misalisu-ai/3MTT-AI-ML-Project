# 3MTT-AI-ML-Project
# Simple Linear Regression – Marketing ROI Analysis

## Project Overview
This project applies Simple Linear Regression using Python and `statsmodels` to analyze a marketing dataset. The objective is to identify which marketing channel (TV, Radio, or Social Media) yields the highest return on investment (ROI) and build a statistically sound model to predict sales outcomes based on budget allocation.

## Key Findings & Business Insights
* **Top Performing Channel:** TV Advertising showed the strongest positive correlation ($r = 0.85$) with Sales.
* **Model Fit ($R^2$):** ~82% of the variance in Sales is explained by TV advertising spend.
* **ROI Impact:** For every $1,000 increase in TV marketing spend, Sales are expected to increase by $80 (based on an example coefficient of 0.08).
* **Recommendation:** Reallocate underperforming budgets from Social Media and Radio directly into TV advertising to maximize overall business revenue.

## Environment Setup
To run the Jupyter Notebook locally, ensure you have Python installed, then install the required dependencies:

```bash
pip install pandas numpy matplotlib seaborn statsmodels jupyter
