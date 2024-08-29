# Car Price Prediction

This project aims to build a machine learning model that predicts the prices of cars using a dataset of over 19,000 cars. The goal is to create an accurate predictive model by applying various data preprocessing and feature engineering techniques.

## Project Overview

The project follows these steps:

1. **Feature Extraction**: Extracted new features from the existing dataset to enhance the model's performance.
2. **Data Analysis**: Performed bi-variate analysis using boxplots and scatterplots to identify relationships between different features.
3. **Outlier Removal**: Applied the inter-quartile range (IQR) method to remove outliers from certain numerical features, ensuring the data is clean and suitable for modeling.
4. **Encoding Categorical Variables**:
   - **Label Encoding**: Applied to one categorical variable.
   - **Target Encoding**: Used for other categorical variables to handle high-cardinality features.
5. **Data Transformation**:
   - **Power Transform**: Applied to the dependent variable (car price) to achieve a near-normal distribution, which improves model performance.
   - **RobustScaler**: Used on the dependent variable for scaling to handle any remaining outliers.
6. **Model Training**: Utilized the `RandomForestRegressor` to train the model and predict car prices based on the processed dataset.

## Getting Started

To get started with this project, you can clone the repository and install the required dependencies.

### Prerequisites

- Python 3.x
- Required libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

## Results

The model's performance will be evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R²).

