# Survival-Analysis

# Survival Analysis and Customer Lifetime Value Modeling

This project explores survival analysis using parametric models to understand churn behavior and calculate Customer Lifetime Value (CLV) for a telecom company.

## Objective

- Fit multiple AFT models: Weibull, Log-Logistic, Log-Normal, and Exponential.
- Compare models using AIC and visualize survival functions.
- Identify significant predictors of churn.
- Calculate CLV based on survival probabilities.
- Segment customers based on CLV.
- Estimate annual retention budget and suggest retention strategies.

## Key Findings

- The Log-Normal model provided the best fit based on AIC.
- Retired customers and those with lower education levels have the highest average CLV.
- Customers using internet services tend to have lower CLV, possibly indicating service dissatisfaction.
- Based on survival probabilities and churn risk, a retention budget was calculated assuming 80% retention and $5,000 per customer.

## Project Structure

- `telco.csv` — The dataset used for modeling.
- `HW3_Sona_Stepanyan.ipynb` — Main notebook with code and report.
- `requirements.txt` — Dependencies.
- `README.md` — Project overview.

## How to Run

```bash
pip install -r requirements.txt
jupyter notebook HW3_Sona_Stepanyan.ipynb
