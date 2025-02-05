# PRODIGY_ML_01

# House Price Prediction using Linear Regression

## Overview
This project builds a **Linear Regression model** to predict house prices based on key features such as **square footage, number of bedrooms, and number of bathrooms**. The dataset comes from a real estate dataset containing various house attributes.

## Features Used
- **GrLivArea** – Above ground living area (square feet)
- **BedroomAbvGr** – Number of bedrooms
- **FullBath** – Number of full bathrooms
- **SalePrice** – Target variable (house price)

## Workflow
1. **Data Preprocessing**
   - Handling missing values
   - Removing outliers
   - Feature scaling

2. **Model Training**
   - Linear Regression model is trained to predict house prices.

3. **Evaluation**
   - Performance is measured using **Mean Absolute Error (MAE)**, **Root Mean Squared Error (RMSE)**, and **R² Score**.

4. **Visualization**
   - Scatter plots for actual vs. predicted prices
   - Residual distribution to analyze errors

## Results Summary
- The model explains **~51% of price variations**.
- **GrLivArea (living area size)** is the most important predictor.
- Performance can be improved by adding more features like **LotArea, YearBuilt, and Neighborhood**.

## Future Improvements
- Use **more advanced models** like **Polynomial Regression, Ridge Regression, or XGBoost**.
- Incorporate **additional features** to improve accuracy.
- Apply **cross-validation** for better model evaluation.
