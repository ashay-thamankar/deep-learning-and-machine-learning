# Restaurant Reviews Analysis 🍽️📊

## Overview

This project involves the analysis of restaurant reviews to predict whether a review is positive or negative. Two models, Naive Bayes and XGBoost Classifier, are employed for this classification task. The analysis includes data preprocessing, exploration, visualization, and model building.

## Part 1: Data Preprocessing 🛠️

### Importing Libraries and Dataset

- **Dataset Link:** [Restaurant Reviews Dataset](https://www.kaggle.com/datasets/akram24/restaurant-reviews)
- **Libraries Used:** `numpy`, `pandas`, `matplotlib`, `seaborn`

### Data Exploration

- **Dataset Shape:** (1000, 2)
- **Data Types:**
  - 1 categorical, 1 numerical
- **Null Values:** None
- **Statistical Summary:**
  - Average length of reviews: 58.32
  - Liked (target variable) mean: 0.5
- **Review Distribution:** Positive (500), Negative (500)

### Dealing with Missing Values

- No missing values in the dataset.

### Review Length Analysis

- **Average Review Length:** 58.32 words
- **Longest Message:** "DELICIOUS!!"
- **Shortest Message:** "."
- **Histogram:** [Histogram of Length of Words](https://github.com/ashay-thamankar/deep-learning-and-machine-learning/blob/main/Machine%20Learning/Restaurant%20review%20classification/charts/histplot%20of%20length%20of%20words.png)

### Countplot Analysis

- Equal distribution of positive and negative reviews.
- **Countplot:** ![Countplot of Review Column](https://github.com/ashay-thamankar/deep-learning-and-machine-learning/blob/main/Machine%20Learning/Restaurant%20review%20classification/charts/countplot%20of%20review%20column.png)

## Part 2: Model Building 🤖

### Splitting the Dataset

- **Train-Test Split:** 80-20
- **X shape:** (800, 1500), **Y shape:** (200, 1500)

### Model Selection

- Chose Naive Bayes and XGBoost Classifier for classification.

### Model 1: Naive Bayes

- **Accuracy:** 70%

### Model 2: XGBoost Classifier

- **Accuracy:** 72%

## Part 3: Final Model 🚀

### Final Model: XGBoost Classifier

- **Accuracy:** 72%

## Visualizations

- [Countplot Image](https://github.com/ashay-thamankar/deep-learning-and-machine-learning/blob/main/Machine%20Learning/Restaurant%20review%20classification/charts/countplot%20of%20review%20column.png)
- [Histogram Image](https://github.com/ashay-thamankar/deep-learning-and-machine-learning/blob/main/Machine%20Learning/Restaurant%20review%20classification/charts/histplot%20of%20length%20of%20words.png)

## Overall Project Link

[Restaurant Reviews Project](https://github.com/ashay-thamankar/deep-learning-and-machine-learning/tree/main/Machine%20Learning/Restaurant%20review%20classification)

## Conclusion

The analysis of restaurant reviews using Naive Bayes and XGBoost Classifier reveals promising results. The XGBoost Classifier performs slightly better with a 72% accuracy rate. The project showcases the importance of natural language processing and machine learning in sentiment analysis, providing valuable insights for businesses in the restaurant industry.
