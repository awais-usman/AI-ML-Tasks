# AI-ML-Tasks
Machine Learning Projects – Beginner Portfolio

This repository contains three beginner-level machine learning tasks focused on data exploration, regression, and classification.

Task 1: Exploring and Visualizing the Iris Dataset

Objective  
Understand trends and patterns in the Iris flower dataset using basic data exploration and visualization techniques.

Dataset  
Source: Built-in Iris dataset from Seaborn

Techniques  
- Data loading and inspection with pandas  
- Scatter plots, histograms, and box plots using matplotlib and seaborn

Key Insights  
- Clear separation of flower species based on petal measurements  
- Box plots revealed potential outliers in sepal width  
- Useful introduction to Exploratory Data Analysis (EDA)

Task 2: Stock Price Prediction (Regression)

Objective  
Predict the next day's closing price of a stock using historical market data.

Dataset  
Source: Yahoo Finance (retrieved using yfinance Python API)  
Example Ticker: AAPL (Apple Inc.)

Techniques  
- Feature selection: Open, High, Low, Volume  
- Linear Regression model using sklearn  
- Visualization of predicted vs actual prices

Key Results  
- Model captured overall price trends with reasonable accuracy  
- Mean Squared Error (MSE) used to evaluate performance  
- Useful for understanding time-series regression basics

Task 3: Heart Disease Classification

Objective  
Predict whether a person is at risk of heart disease based on their medical information.

Dataset  
Source: Heart Disease UCI Dataset (via public GitHub mirror)

Techniques  
- Data preprocessing and splitting  
- Classification using Logistic Regression  
- Model evaluation: Accuracy, Confusion Matrix, ROC-AUC  
- Feature importance visualization

Key Findings  
- Model achieved good accuracy (around 85 percent) and AUC score  
- Key predictors: chest pain type, max heart rate, ST depression  
- Classification performance visualized using ROC curve and confusion matrix


Skills Demonstrated

- Exploratory Data Analysis  
- Regression and Classification modeling  
- Model evaluation (Accuracy, AUC, Confusion Matrix)  
- Real-world data handling with APIs (yfinance)  
- Visualization with matplotlib and seaborn
