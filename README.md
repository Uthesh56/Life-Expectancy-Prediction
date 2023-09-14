# LIFE EXPECTANCY PREDICTION

## Overview

Welcome to the Life Expectancy Prediction project! In this project, we delve into the fascinating realm of predicting life expectancy using machine learning models. Our goal is to develop accurate models that can estimate life expectancy based on various factors.

## Dataset

Our dataset is a comprehensive collection of health-related indicators, demographics, and socio-economic data from different countries. It provides valuable insights into factors affecting life expectancy. [Dataset Source](https://data.world/datasets/life-expectancy)

## Getting Started

### Prerequisites

Before embarking on this predictive journey, ensure you have the following prerequisites in place:

- **Python** (version 3.7 or higher)
- **Jupyter Notebook** (optional but recommended)

## Data Preprocessing

To prepare our dataset for modeling, we underwent a thorough data preprocessing phase. These steps were crucial in ensuring our data was ready for training and evaluation.

### Data Cleaning

1. **Handling Missing Values**: We addressed missing values through imputation techniques, ensuring data completeness.

2. **Outlier Detection**: Outliers were identified and, if necessary, treated to prevent them from affecting our models.

3. **Feature Scaling**: Appropriate scaling methods were applied to ensure features had similar scales.

### Feature Selection

We carefully selected relevant features based on domain knowledge and data analysis to optimize model performance.

### Data Transformation

Categorical variables were encoded, and date-based features were extracted to enhance model interpretability.

## Models and Evaluation Metrics

We employed three powerful regression models for life expectancy prediction:

1. **Linear Regression Model**
   - Model Type: Linear Regression
   - Evaluation Metrics:
     - R-squared (R^2): 0.822695

2. **Random Forest Regressor**
   - Model Type: Random Forest Regressor
   - Evaluation Metrics:
     - R-squared (R^2): 0.968701

3. **Decision Tree Regressor**
   - Model Type: Decision Tree Regressor
   - Evaluation Metrics:
     - R-squared (R^2): 0.926199

## Conclusion

- Model Performance: Among the models we explored, the Random Forest Regressor outperformed the others, with the lowest MAE and RMSE, indicating its superior predictive accuracy.

- Interpretability: While Random Forest excelled in terms of accuracy, Linear Regression and Decision Tree models provide more interpretability, making them valuable for understanding the relationships between features and life expectancy.

- Further Optimization: Our project highlighted the potential for model optimization through hyperparameter tuning and feature engineering. Experimenting with different configurations can further enhance model performance.
