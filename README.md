# House Price Prediction using Linear Regression

## Task Description
This project involves implementing a linear regression model to predict the prices of houses based on their square footage and the number of bedrooms and bathrooms.

## Dataset
The dataset used for this project is available on Kaggle: [House Prices - Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)

## Performance Metrics
The model achieved the following evaluation metrics:
- **Mean Squared Error (MSE):** 329,836,303.60
- **Root Mean Squared Error (RMSE):** 18,161.40
- **R-squared (R²):** 0.8663

## Installation & Setup
To run this project, ensure you have the following dependencies installed:
```bash
pip install numpy pandas scikit-learn matplotlib
```

## Usage
Run the Jupyter Notebook or Python script to train and evaluate the model:
```bash
jupyter notebook PRODEGY_ML_TASK01.ipynb
```

## Model Implementation
The model follows these steps:
1. Load and preprocess the dataset
2. Split the dataset into training and testing sets
3. Train a linear regression model
4. Evaluate model performance using MSE, RMSE, and R²
5. Visualize results

## Results & Observations
- The R² score of 0.8663 indicates that the model explains approximately 86.63% of the variance in house prices.
- The RMSE suggests an average error of around $18,161 in price predictions.
- Further improvements can be made by incorporating additional features, feature scaling, or trying advanced regression techniques.

## Author
Malhar (Intern at Prodigy InfoTech)
