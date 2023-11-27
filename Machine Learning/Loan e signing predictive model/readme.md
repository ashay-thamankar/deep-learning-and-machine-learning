# Loan E-Signing Predictive Modeling

## Overview 🚀

Welcome to the Loan E-Signing Predictive Modeling project repository! This project aims to analyze a dataset related to the e-signing of loans based on financial history and build a predictive model using XGBoost Classifier to understand and predict e-signing behavior.

## Dataset Overview 📑

The dataset consists of 17,908 entries with 21 features, including user details, financial information, and e-signing status. The primary objective is to explore the data, preprocess it, and develop a machine learning model to predict whether a user will e-sign a loan.

## Project Structure 📂

- **Part 1: Data Processing**: Loading the dataset, exploring its structure, and preparing it for analysis.
- **Part 2: Exploratory Data Analysis (EDA)**: Analyzing and visualizing the data to gain insights.
- **Part 3: Model Building**: Implementing machine learning models (Logistic Regression, SVM, Random Forest, XGBoost).
- **Part 4: Hyperparameter Tuning**: Using Randomized Search to find optimal hyperparameters for the XGBoost model.
- **Part 5: Final Model**: Building and evaluating the final XGBoost Classifier.

## Key Findings and Results 📈

### Data Exploration

- Dataset contains 17,908 entries with key features such as age, income, risk scores, and e-signing status.
- **Statistical Summary:**
  - Average age: 43 (min 18, max 96)
  - Average income: $3657 (min $905, max $9985)

### Model Comparison

- After building various models, XGBoost outperformed others in terms of accuracy and F1 score.
- **Model Performance:**
  - XGBoost Classifier Accuracy: 64.85%
  - XGBoost Classifier F1 Score: 68.67%

### Hyperparameter Tuning

- Utilized Randomized Search to find optimal hyperparameters for the XGBoost model.
- **Best Parameters:**
  - Learning Rate: 0.1
  - Max Depth: 3
  - Min Child Weight: 5
  - Gamma: 0.1
  - Subsample: 1.0
  - Colsample by Tree: 0.4
  - Number of Estimators: 400

## Conclusion and Insights 🌟

- The XGBoost model, with tuned hyperparameters, proved effective in predicting user behavior.
- Understanding the significance of features such as age, income, and risk scores is crucial in the lending process.

Explore the detailed analysis and model implementation in the [Project Repository](https://github.com/ashay-thamankar/machine-learning-and-deep-learning/tree/main/Machine%20Learning/Loan%20e%20signing%20predictive%20model).

![Bar Chart Correlation with Target](https://github.com/ashay-thamankar/machine-learning-and-deep-learning/blob/main/Machine%20Learning/Loan%20e%20signing%20predictive%20model/charts/bar%20correlation%20with%20target.png)
![Heatmap Correlation with Target](https://github.com/ashay-thamankar/machine-learning-and-deep-learning/blob/main/Machine%20Learning/Loan%20e%20signing%20predictive%20model/charts/correlation%20of%20target%20heatmap.png)
![Countplot of Target](https://github.com/ashay-thamankar/machine-learning-and-deep-learning/blob/main/Machine%20Learning/Loan%20e%20signing%20predictive%20model/charts/count%20plot%20of%20target.png)

Feel free to delve into the project, gain insights, and enjoy the journey!

🚀 **Happy Exploring!** 🌟
