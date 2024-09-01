# Linear-Regression-Multivariable---Student-Performance-Prediction
# Student Performance Prediction using Multiple Linear Regression

This project demonstrates the application of linear regression to predict student performance based on several features. The model is implemented in Python within a Jupyter Notebook, leveraging libraries like pandas, numpy, matplotlib, and seaborn.

## Key Features

- **Multiple Predictors:** The model considers multiple variables that might influence student performance, including:
    - Hours Studied
    - Previous Scores
    - Sleep Hours
    - Extracurricular Activities (encoded as a binary feature)

- **Gradient Descent Optimization:** Implements the gradient descent algorithm from scratch to iteratively find the optimal model parameters (weights) that minimize the Mean Squared Error (MSE) cost function.

- **Normal Equation Solution:** Demonstrates the use of the normal equation as an alternative method to directly calculate the optimal weights.

- **Model Evaluation and Comparison:** Compares the performance of the models trained using both gradient descent and the normal equation, providing insights into their effectiveness.

- **Data Visualization:** Employs various visualization techniques, including:
    - Pair plots to explore relationships between features and the target variable.
    - Box plots to compare performance distributions based on extracurricular activities.
    - Scatter plots with best fit lines to visualize the model's predictions.

## Notebook Contents

- **Data Loading and Exploration:** Loads the 'Student_Performance.csv' dataset and performs initial data analysis.
- **Data Preprocessing:** Handles missing values (if any) and converts categorical features to numerical representations.
- **Feature Scaling:** Normalizes numerical features to improve model performance.
- **Linear Regression Implementation:** Implements the core logic of multiple linear regression, including:
    - Cost function definition (MSE)
    - Gradient descent algorithm
    - Normal equation calculation
- **Model Evaluation and Visualization:** Evaluates the trained models and generates visualizations to interpret the results.
