# AIML_11.1_Car_Price
# What Drives the Price of a Car?

## Overview

The goal of this project is to understand what factors make a car more or less expensive and provide clear recommendations to the client—a used car dealership—as to what consumers value in a used car.

This project aims to **predict used car prices** using historical listings and vehicle attributes. It uses multiple regression models to uncover the most influential factors affecting pricing, offering **actionable insights for used car dealerships**. The dataset includes features like vehicle age, mileage, manufacturer, condition etc.

## Important Links

[Used Cars Dataset](https://github.com/amitkushwaha2000/AIML_11.1_Car_Price/blob/main/vehicles.rar)

[Jupyter Notebook](https://github.com/amitkushwaha2000/AIML_11.1_Car_Price/blob/main/prompt_II_AK.ipynb)

## Key Highlights

-  **Data Cleaning & Exploration**:
  - Removed extreme outliers and handled missing values.
  - Converted categorical fields for modeling and standardized numerical features.

- **Models Used**:
  - Linear Regression
  - Ridge Regression (best performer)
  - Lasso Regression

- **Cross-Validation & Tuning**:
  - Grid search used to optimize regularization parameters.
  - Evaluation based on RMSE and R² Score.

- **Performance Summary**:
  | Model              | R² Score (Test) | RMSE (Log Price) |
  |--------------------|-----------------|------------------|
  | Ridge Regression   | **0.7433**       | **0.4052**      |
  | Linear Regression  | 0.7434           | 0.4052          |
  | Lasso Regression   | 0.7204           | 0.4229          |

---

## Key Findings

- **Odometer and Car Age** are the strongest numerical predictors — both negatively correlated with price.
- **Manufacturer** (e.g., Datsun, Tesla, Saturn and Porsche), **fuel type**, and **condition** were top categorical predictors.
- **Diesel and Electric vehicles** have higher average resale prices.
- **Poor condition, high mileage or older vehicles** sharply reduce price predictions.

---

## Business Value

This model helps dealerships:
- Quickly assess fair prices for trade-ins and used listings.
- Strategically focus on vehicle types/brands with better ROI.
- Implement smarter inventory and pricing strategies using data-backed predictions.

---

## Tools and Libraries Used
- Python 3 (Jupyter Notebook)
- pandas for data analysis
- seaborn & matplotlib for data visualization
- numpy for numerical operations
- Scikit-learn for modeling and pre-processing

## Acknowledgments
- Kaggle for the dataset.
