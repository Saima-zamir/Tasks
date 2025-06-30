# Tasks
This Repository contains all the internship tasks assigned to me during  my internship at DeveloperHub.

# Project Task Details & Strategy

This file describes how each of your three tasks was approached and solved, along with the strategies used.

---

## **Task 1: Exploring and Visualizing a Simple Dataset**

**Description:**  
The first task was to select a simple dataset and perform exploratory data analysis (EDA) to understand its structure, main features, and underlying patterns.

**Strategy:**  
- **Data Loading:** Imported the dataset using pandas.
- **Initial Exploration:** Used `head()`, `info()`, and `describe()` to understand data types, missing values, and basic statistics.
- **Visualizations:**
  - Plotted histograms and boxplots for numerical features to check distributions and spot outliers.
  - Used bar plots and count plots for categorical features.
  - Created a correlation heatmap (with only numeric columns) to find relationships between variables.
- **Insights:** Wrote down key observations and interesting trends noticed in the data, such as skewed distributions or highly correlated variables.

**Outcome:**  
A clear, visual, and statistical understanding of the dataset, which set the foundation for further analysis or modeling.

---

## **Task 2: Predict Future Stock Prices**

**Description:**  
The second task involved forecasting stock prices using historical stock market data.

**Strategy:**  
- **Data Preparation:**  
  - Loaded a stock dataset (e.g., using Yahoo Finance API or a CSV).
  - Ensured there were no missing dates or extreme outliers.
  - Used only the ‘Close’ price for prediction.
- **Feature Engineering:**  
  - Created lag features (previous day prices).
  - Generated moving averages as features.
- **Model Selection:**  
  - Used simple regression models (like Linear Regression) and time series models (like ARIMA or Prophet, if allowed).
  - Split data into training and testing sets based on time order (not randomly).
- **Model Training and Prediction:**  
  - Trained the model on past data, predicted future prices for the test set.
- **Visualization:**  
  - Plotted actual vs. predicted stock prices for easy comparison.
- **Evaluation:**  
  - Calculated RMSE or MAE to measure prediction accuracy.

**Outcome:**  
Built a basic but functional pipeline to forecast stock prices and visualized how well the predictions matched actual values.

---

## **Task 3: Heart Disease Prediction**

**Description:**  
The third task was to predict whether a person has heart disease using a machine learning classification model.

**Strategy:**  
- **Data Cleaning:**  
  - Checked for missing values, duplicates, and inconsistent data.
  - Converted categorical variables to numeric (using one-hot encoding or label encoding).
- **EDA & Visualization:**  
  - Plotted feature distributions and correlation heatmap (numeric features only).
  - Explored relationships between features and the target (heart disease).
- **Model Building:**  
  - Used models like Logistic Regression or Decision Tree for binary classification.
  - Split data into train and test sets.
- **Model Evaluation:**  
  - Used accuracy, confusion matrix, and ROC curve to evaluate performance.
- **Feature Importance:**  
  - Identified which features contributed most to the prediction (using model coefficients or feature importance plots).

**Outcome:**  
Created an end-to-end pipeline to predict heart disease, evaluated the model’s effectiveness, and highlighted important health predictors.

---
