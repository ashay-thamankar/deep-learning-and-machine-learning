# Student Performance Prediction Model 🎓📊

## Overview 📊

This project aims to predict student performance using machine learning techniques. By analyzing a dataset containing various student attributes and academic details, we strive to gain insights into factors influencing academic success and build a predictive model.

## Table of Contents 📑

1. [Introduction](#introduction)
2. [Dataset Exploration](#dataset-exploration)
3. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
4. [Model Development](#model-development)
5. [Final Model](#final-model)
6. [Conclusion](#conclusion)

## Introduction 🚀

Student performance is a critical aspect of the education system, and understanding the factors influencing academic success can provide valuable insights for educators and policymakers. In this project, we employ machine learning to predict student performance based on demographic information and study habits.

## Dataset Exploration 📊

### Data Overview

The dataset contains information about students, including their gender, parental education, study time, and academic performance. Exploring and preprocessing the data is the initial step in building an effective predictive model.

### Data Preprocessing

Handling missing values, encoding categorical variables, and other preprocessing steps are crucial for preparing the data for analysis.

## Exploratory Data Analysis (EDA) 📈

Exploratory Data Analysis involves visualizing and interpreting the dataset to extract meaningful insights. Let's explore some key aspects:

### Data Distributions and Skewness

![Data Distributions](charts/Exploring%20Data%20Distributions%2C%20Detecting%20Skewness%20with%20Density%20Plots.png)

### Graphs

[Link to Graphs Section](#graphs)

### Correlation Heatmap

![Correlation Heatmap](charts/Correlation%20Heatmap%2C%20Positive%20Correlation%20with%20Study%20Time%20and%20Parental%20Education.png)

## Graphs 📈

### Gender Distribution

![Gender Distribution](charts/Gender%20Distribution%2C%20More%20Females%20than%20Males%20countplot.png)

### Performance Distribution by Gender

![Performance Distribution by Gender](charts/Performance%20Distribution%20by%20Gender%2C%20Higher%20Performances%20by%20Females%20boxplot.png)

### Parental Education Impact on Performance

![Parental Education Impact on Performance](charts/Parental%20Education%20Impact%20on%20Performance%2C%20Higher%20Education%20Correlates%20with%20Higher%20Performance%20barplot.png)

### Study Time vs. Performance

![Study Time vs. Performance](charts/Study%20Time%20vs%20Performance%2C%20Positive%20Correlation%20scatterplot.png)

### Performance Distribution by Subjects

![Performance Distribution by Subjects](charts/Performance%20Distribution%20by%20Subjects%2C%20Subject%203%20Shows%20Higher%20Median%20boxplot.png)

### Checking Outlier using Boxplot

![Checking Outlier using Boxplot](https://github.com/ashay-thamankar/deep-learning-and-machine-learning/blob/main/Machine%20Learning/Student%20Performance%20Predictrion%20Model/charts/Checking%20Outlier%20using%20boxplot.png)

### Histograms and KDEs of Average Values

![Histograms and KDEs of Average Values](https://github.com/ashay-thamankar/deep-learning-and-machine-learning/blob/main/Machine%20Learning/Student%20Performance%20Predictrion%20Model/charts/Histograms%20and%20KDEs%20of%20Average%20Values.png)

### Histograms and KDEs of Total Scores

![Histograms and KDEs of Total Scores](https://github.com/ashay-thamankar/deep-learning-and-machine-learning/blob/main/Machine%20Learning/Student%20Performance%20Predictrion%20Model/charts/Histograms%20and%20KDEs%20of%20Total%20scores.png)

### Histograms and KDEs of Male and Female Performance

![Histograms and KDEs of Male and Female Performance](https://github.com/ashay-thamankar/deep-learning-and-machine-learning/blob/main/Machine%20Learning/Student%20Performance%20Predictrion%20Model/charts/Histograms%20and%20KDEs%20of%20male%20and%20female%20performance.png)

### Histograms and KDEs of Parental Level of Education Male and Female Wise

![Histograms and KDEs of Parental Level of Education Male and Female Wise](https://github.com/ashay-thamankar/deep-learning-and-machine-learning/blob/main/Machine%20Learning/Student%20Performance%20Predictrion%20Model/charts/Histograms%20and%20KDEs%20of%20parental%20level%20of%20education%20male%20and%20female%20wise.png)

### Histograms and KDEs of Race/Ethnicity Male and Female Wise

![Histograms and KDEs of Race/Ethnicity Male and Female Wise](https://github.com/ashay-thamankar/deep-learning-and-machine-learning/blob/main/Machine%20Learning/Student%20Performance%20Predictrion%20Model/charts/Histograms%20and%20KDEs%20of%20race_ethnicity%20male%20and%20female%20wise.png)

### How is Group-wise Distribution

![How is Group-wise Distribution](https://github.com/ashay-thamankar/deep-learning-and-machine-learning/blob/main/Machine%20Learning/Student%20Performance%20Predictrion%20Model/charts/How%20is%20Group%20wise%20distribution.png)

### How is Distribution of Gender

![How is Distribution of Gender](https://github.com/ashay-thamankar/deep-learning-and-machine-learning/blob/main/Machine%20Learning/Student%20Performance%20Predictrion%20Model/charts/How%20is%20distribution%20of%20Gender.png)

### Is Race or Ethnicity Impacting Student's Performance

![Is Race or Ethnicity Impacting Student's Performance](https://github.com/ashay-thamankar/deep-learning-and-machine-learning/blob/main/Machine%20Learning/Student%20Performance%20Predictrion%20Model/charts/Is%20Race%20or%20Ehnicity%20has%20any%20impact%20on%20student's%20performance.png)

### Is Test Preparation Course Impacting Student's Performance

![Is Test Preparation Course Impacting Student's Performance](https://github.com/ashay-thamankar/deep-learning-and-machine-learning/blob/main/Machine%20Learning/Student%20Performance%20Predictrion%20Model/charts/Is%20Test%20Preparation%20Course%20Impacting%20Student's%20Performance.png)

### Is Lunch Type Intake Impacting Student's Performance

![Is Lunch Type Intake Impacting Student's Performance](https://github.com/ashay-thamankar/deep-learning-and-machine-learning/blob/main/Machine%20Learning/Student%20Performance%20Predictrion%20Model/charts/Is%20lunch%20type%20intake%20has%20any%20impact%20on%20student's%20performance.png)

### Is Parental Education Impacting Student's Performance

![Is Parental Education Impacting Student's Performance](https://github.com/ashay-thamankar/deep-learning-and-machine-learning/blob/main/Machine%20Learning/Student%20Performance%20Predictrion%20Model/charts/Is%20parental%20education%20has%20any%20impact%20on%20student's%20performance.png)

### Total Average vs. Math Average Marks of Both Genders

![Total Average vs. Math Average Marks of Both Genders](https://github.com/ashay-thamankar/deep-learning-and-machine-learning/blob/main/Machine%20Learning/Student%20Performance%20Predictrion%20Model/charts/Total%20average%20vs%20Math%20average%20marks%20of%20both%20the%20genders.png)

### Pie Chart of Features

![Pie Chart of Features](https://github.com/ashay-thamankar/deep-learning-and-machine-learning/blob/main/Machine%20Learning/Student%20Performance%20Predictrion%20Model/charts/pip%20chart%20of%20features.png)

### Violin Plot of Math, Reading, and Writing Score

![Violin Plot of Math, Reading, and Writing Score](https://github.com/ashay-thamankar/deep-learning-and-machine-learning/blob/main/Machine%20Learning/Student%20Performance%20Predictrion%20Model/charts/violin%20plot%20of%20math%2Creading%20and%20writing%20score.png)

## General Analysis 📈

The exploratory data analysis reveals interesting insights into student performance:

- **Gender Impact:** Females tend to have higher academic performance.
- **Parental Education:** Higher parental education correlates with better student performance.
- **Study Time:** There is a positive correlation between study time and academic performance.

## Model Development 🤖

### Data Preparation

Before building models, we preprocess the data, splitting it into training and testing sets.

### Model Selection

#### Linear Regression

Model performance for Train set:
- Root mean squared error: 5.3231
- Mean absolute error: 4.2667
- R2 score: 0.8743

Model performance for Test set:
- Root Mean squared error: 5.3940
- Mean absolute error: 4.2148
- R2 score: 0.8804
===================================

#### Lasso

Model performance for Train set:
- Root mean squared error: 6.5938
- Mean absolute error: 5.2063
- R2 score: 0.8071

Model performance for Test set:
- Root Mean squared error: 6.5197
- Mean absolute error: 5.1579
- R2 score: 0.8253
===================================

#### Ridge

Model performance for Train set:
- Root mean squared error: 5.3233
- Mean absolute error: 4.2650
- R2 score: 0.8743

Model performance for Test set:
- Root Mean squared error: 5.3904
- Mean absolute error: 4.2111
- R2 score: 0.8806
===================================

#### K-Neighbors Regressor

Model performance for Train set:
- Root mean squared error: 5.7091
- Mean absolute error: 4.5175
- R2 score: 0.8554

Model performance for Test set:
- Root Mean squared error: 7.2583
- Mean absolute error: 5.6370
- R2 score: 0.7835
===================================

#### Decision Tree

Model performance for Train set:
- Root mean squared error: 0.2795
- Mean absolute error: 0.0187
- R2 score: 0.9997

Model performance for Test set:
- Root Mean squared error: 8.2592
- Mean absolute error: 6.4750
- R2 score: 0.7197
===================================

#### Random Forest Regressor

Model performance for Train set:
- Root mean squared error: 2.2728
- Mean absolute error: 1.8171
- R2 score: 0.9771

Model performance for Test set:
- Root Mean squared error: 6.0423
- Mean absolute error: 4.6931
- R2 score: 0.8500
===================================

#### XGBRegressor

Model performance for Train set:
- Root mean squared error: 1.0073
- Mean absolute error: 0.6875
- R2 score: 0.9955

Model performance for Test set:
- Root Mean squared error: 6.4733
- Mean absolute error: 5.0577
- R2 score: 0.8278
===================================

#### CatBoosting Regressor

Model performance for Train set:
- Root mean squared error: 3.0427
- Mean absolute error: 2.4054
- R2 score: 0.9589

Model performance for Test set:
- Root Mean squared error: 6.0086
- Mean absolute error: 4.6125
- R2 score: 0.8516
===================================

#### AdaBoost Regressor

Model performance for Train set:
- Root mean squared error: 5.7847
- Mean absolute error: 4.7346
- R2 score: 0.8516

Model performance for Test set:
- Root Mean squared error: 5.9128
- Mean absolute error: 4.5969
- R2 score: 0.8563
===================================

## Final Model 🏆

The **Linear Regression** model is selected as the final model based on its performance metrics on both the training and testing sets:

- Root mean squared error: 5.3940
- Mean absolute error: 4.2148
- R2 score: 0.8804

### Prediction using Final Model

Predictions are made on the test data using the final Linear Regression model.

## Conclusion 🎉

This comprehensive Student Performance Prediction Model project demonstrates the significance of exploratory data analysis and model evaluation in developing accurate machine learning models. The insights gained from the data analysis contribute to informed decision-making, and the selected Random Forest Regressor showcases its prowess in predicting student performance.
