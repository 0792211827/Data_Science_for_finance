# Yield Curve Prediction
This project focuses on Yield Curve Prediction, a critical component in finance, especially in understanding the dynamics of interest rates across different maturities. The objective is to forecast the yield curve and assess the performance of machine learning models in predicting short, medium, and long-term yields.

## Overview
The yield curve represents the relationship between bond yields and their maturities. It is a vital tool for evaluating economic conditions, pricing fixed-income securities, and making investment decisions. Accurately predicting the yield curve helps investors anticipate interest rate changes and adjust their strategies accordingly.

In this project, we:

  - Implement and compare models such as Linear Regression and Artificial Neural Networks (ANN) for yield curve prediction.
  - Evaluate the models' performance in predicting yields for short (1-month), medium (5-year), and long-term (30-year) maturities.
  - Visualize the actual vs. predicted values to analyze performance trends.
## Features
**Data Processing:**

- Load and preprocess historical yield curve data.
- Perform exploratory data analysis (EDA) to understand yield trends over time.
**Model Training:**

- Train Linear Regression and Multi-Layer Perceptron (MLP) models to predict yields for various maturities (1-month, 5-year, 30-year).

**Performance Evaluation:**

- Use metrics like Mean Squared Error (MSE) and R-squared (R²) to compare model performance.
- Highlight the strengths of Linear Regression in short-term predictions and MLP in handling long-term trends.
**Visualization:**

- Plot actual vs. predicted yields to assess model accuracy and trends.
- Analyze how each model adapts to changing market conditions.
## Tools and Libraries
This project leverages the following tools and libraries:

**Programming Language:** Python

**Libraries:**

- NumPy: Numerical computations.
- Pandas: Data manipulation and preprocessing.
- Matplotlib & Seaborn: Data visualization.
- Scikit-learn: Model implementation and evaluation.

## Conclusion
This project demonstrates the effectiveness of both Linear Regression and ANN models in yield curve prediction. While Linear Regression excels in scenarios where the yield curve is more stable, the flexibility of ANNs makes them well-suited to dynamic market conditions. Future enhancements, such as hyperparameter tuning or exploring LSTM models, could further improve predictions.
