# car-sales--prediction
# Car Sales Price Prediction

This project predicts car prices using machine learning techniques based on various car attributes, such as mileage, model year, brand, fuel type, and engine type. The notebook walks through data preprocessing, feature engineering, model training, evaluation, and selection of the best-performing model.

## Project Structure

- **Data Preprocessing**: Cleaning, transforming, and encoding data for machine learning.
- **Feature Engineering**: Scaling and encoding features based on importance to improve prediction accuracy.
- **Model Selection and Evaluation**: Training models (Linear Regression, Random Forest, Gradient Boosting) and selecting the best one using Root Mean Squared Error (RMSE).
- **Prediction Output**: Prepares a CSV file for evaluation based on RMSE.

## Files

- `car-sales.ipynb`: Notebook containing code for data preparation, model training, and prediction output.

## Getting Started

### Prerequisites

Install the necessary libraries:

```bash
pip install pandas numpy scikit-learn xgboost optuna
