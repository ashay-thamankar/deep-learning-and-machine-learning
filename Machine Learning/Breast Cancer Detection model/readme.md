# Breast Cancer Detection Project

## Project Overview 🌟

This project aims to build a machine learning model for the detection of breast cancer based on the Wisconsin Breast Cancer dataset. We explore various classification models and employ SVM as the final model due to its promising performance.

## Dataset 📊

The dataset used in this project is the [Wisconsin Breast Cancer dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data) from Kaggle. It consists of features such as radius, texture, perimeter, area, smoothness, and more.

## Data Preprocessing 🛠️

### Handling Missing Values

We identified and handled missing values, dropping a column with null values.

### Dealing with Categorical Data

Categorical values were one-hot encoded, converting the 'diagnosis' column into numerical format.

### Feature Scaling

Standard scaling was applied to normalize the numerical features, ensuring fair contributions from all variables.

## Exploratory Data Analysis (EDA) 📈

Explored the dataset to understand its structure and characteristics. Visualizations include:

- [Count Plot of Target](https://github.com/ashay-thamankar/machine-learning-and-deep-learning/blob/main/Machine%20Learning/Breast%20Cancer%20Detection%20model/graph/countplot%20of%20target.png)
  ![Count Plot](https://github.com/ashay-thamankar/machine-learning-and-deep-learning/blob/main/Machine%20Learning/Breast%20Cancer%20Detection%20model/graph/countplot%20of%20target.png)

- [Bar Correlation of Target](https://github.com/ashay-thamankar/machine-learning-and-deep-learning/blob/main/Machine%20Learning/Breast%20Cancer%20Detection%20model/graph/bar%20correlation%20graph%20of%20target.png)
  ![Bar Correlation](https://github.com/ashay-thamankar/machine-learning-and-deep-learning/blob/main/Machine%20Learning/Breast%20Cancer%20Detection%20model/graph/bar%20correlation%20graph%20of%20target.png)

- [Correlation of Target Heatmap](https://github.com/ashay-thamankar/machine-learning-and-deep-learning/blob/main/Machine%20Learning/Breast%20Cancer%20Detection%20model/graph/correlation%20of%20target%20heatmap.png)
  ![Correlation Heatmap](https://github.com/ashay-thamankar/machine-learning-and-deep-learning/blob/main/Machine%20Learning/Breast%20Cancer%20Detection%20model/graph/correlation%20of%20target%20heatmap.png)

## Model Building 🤖

We experimented with multiple classification models:

1. **Logistic Regression**
   - A simple yet effective linear model for binary classification.

2. **Random Forest**
   - An ensemble method combining multiple decision trees for improved accuracy and robustness.

3. **Support Vector Machine (SVM)**
   - Chosen as the final model due to its excellent performance, providing a clear decision boundary in high-dimensional space.

4. **XGBoost Classification**
   - A powerful gradient boosting algorithm that often performs well in classification tasks.

The SVM model exhibited the best performance, and we selected it as the final model for breast cancer detection.

## Hyperparameter Tuning 🎯

Conducted a randomized search to find the best hyperparameters for the SVM model, improving its accuracy.

## Model Evaluation 📉

### SVM Classification (Final Model)

- **Accuracy**: 96.49%
- **F1 Score**: 95.83%
- **Precision**: 93.88%
- **Recall**: 97.87%

## Conclusion and Insights 🌐

- The SVM model demonstrated robust performance in breast cancer detection.
- The randomized search further optimized the model's hyperparameters, enhancing its accuracy.
- Feature scaling and one-hot encoding contributed to better model convergence.
- Cross-validation provided a reliable estimate of the model's generalization performance.

## Future Work 🚀

- Explore advanced feature engineering techniques.
- Experiment with other ensemble methods.
- Incorporate more advanced deep learning models for comparison.

Feel free to explore the [overall project](https://github.com/ashay-thamankar/machine-learning-and-deep-learning/tree/main/Machine%20Learning/Breast%20Cancer%20Detection%20model) for detailed code implementation and analysis.

👩‍💻 Happy Coding!
