# Employee Attrition Prediction Model 🚀

## Overview

This project focuses on predicting employee attrition using advanced machine learning techniques. Leveraging Python and popular libraries such as Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, and XGBoost, we aimed to gain insights into employee churn and develop an effective prediction model.

## Project Structure

### 1. Data Preprocessing 🛠️

- **Dataset Link:** [Employee Attrition Dataset](https://www.kaggle.com/datasets/patelprashant/employee-attrition)
  
  - **Dataset Overview:**
    - Explored the dataset, revealing its structure and dimensions.
    - Shape of the dataset: (1470, 35)

  - **Data Exploration:**
    - Extracted key statistics and insights from the dataset.
      - Average age of employees: 36.92
      - Average daily rate: 802.49
      - ...

  - **Handling Missing Values:**
    - Checked for missing values (Result: No missing values).

  - **Restructuring of Dataset:**
    - Dropped irrelevant columns: 'Over18', 'EmployeeCount', 'EmployeeNumber', 'StandardHours'.
    - Dataset shape after restructuring: (1470, 31).

  - **Encoding Categorical Data:**
    - Encoded categorical data, resulting in a dataset with shape: (1470, 45).
    - Categorical columns after encoding: 0

### 2. Data Visualization 📊

   - **Countplot of Target:**
     - Visualized the distribution of the target variable ('Attrition').
     - Number of employees attrited: 237
     - Number of employees not attrited: 1233
     ![Countplot of Target](https://github.com/ashay-thamankar/deep-learning-and-machine-learning/blob/main/Machine%20Learning/Employee%20Attrition%20Prediction%20model/charts/countplot%20of%20target.png)

   - **Attrition Trends in Departments and Roles:**
     - Explored attrition trends across different departments and roles.
     ![Attrition in Departments and Roles](https://github.com/ashay-thamankar/deep-learning-and-machine-learning/blob/main/Machine%20Learning/Employee%20Attrition%20Prediction%20model/charts/attrition%20in%20depts.png)

   - **Correlation Heatmap:**
     - Visualized the correlation matrix using a heatmap.
     ![Correlation Heatmap](https://github.com/ashay-thamankar/deep-learning-and-machine-learning/blob/main/Machine%20Learning/Employee%20Attrition%20Prediction%20model/charts/correlation%20heatmap.png)

### 3. Model Selection 🤖

   - **Model Performance:**
     - Explored the performance of Logistic Regression, SVM, Random Forest, and XGBoost models.

### 4. Hyperparameter Tuning ⚙️

   - **Randomized Search:**
     - Applied Randomized Search to discover optimal hyperparameters for the Logistic Regression model.
     - Best parameters: {'solver': 'liblinear', 'penalty': 'l1', 'max_iter': 100, 'C': 1.0}
     - Best score: 0.8221

### 5. Final Model 🏆

   - **Optimized Model:**
     - Trained the Logistic Regression model with optimized hyperparameters.
     - Achieved an accuracy of 88.44%.

### 6. Prediction 📈

   - **Single Variable Prediction:**
     - Demonstrated how the model predicts employee attrition based on input features.

## Analysis Insights 📊

- 🎉 **Optimized Model:**
  - Logistic Regression, after hyperparameter tuning, achieved a remarkable accuracy of 88.44%.

- 📈 **Attrition Trends:**
  - Analyzed countplot and department/role-specific graphs, revealing insights into attrition trends.
  
- 🤖 **Model Performance:**
  - Logistic Regression outperformed other models, showcasing its suitability for this prediction task.

- ⚙️ **Hyperparameter Tuning:**
  - Randomized Search significantly improved the Logistic Regression model, optimizing its performance.

## Conclusion

This project provides valuable insights into employee attrition and presents a reliable Logistic Regression model for predicting attrition with high accuracy. The detailed analysis and visualizations contribute to a better understanding of the underlying patterns.

Feel free to explore the [overall project]( https://github.com/ashay-thamankar/deep-learning-and-machine-learning/tree/main/Machine%20Learning/Employee%20Attrition%20Prediction%20model ) for detailed code implementation and analysis.

Feel free to explore the project for a more in-depth understanding!
