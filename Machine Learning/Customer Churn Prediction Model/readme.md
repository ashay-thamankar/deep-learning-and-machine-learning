# Customer Churn Prediction Project 🚀

Welcome to the Customer Churn Prediction project repository! 📈 This project focuses on predicting customer churn in a banking scenario, utilizing a diverse dataset and building a robust XGBoost Classifier for accurate predictions.

## Dataset Overview 📑

The dataset, titled "Predicting Churn for Bank Customers," encompasses customer demographics, banking activity, and churn status. Churn prediction is crucial for customer retention strategies, making this project valuable for businesses aiming to reduce customer attrition.

## Project Structure 📂

- **Part 1: Data Processing** 🛠️
  - **Objective:** Load and preprocess the dataset.
  - **Steps:**
    - Load the dataset.
    - Handle missing values and outliers.
    - Encode categorical variables.

- **Part 2: Exploratory Data Analysis (EDA)** 📊
  - **Objective:** Gain insights into the dataset.
  - **Analysis:**
    - Explore statistical summaries.
    - Visualize key features.
    - Understand feature correlations.

- **Part 3: Model Building** 🤖
  - **Objective:** Implement machine learning models.
  - **Models Used:**
    - Logistic Regression
    - Support Vector Machine (SVM)
    - Random Forest
    - XGBoost

- **Part 4: Model Comparison** 🔄
  - **Objective:** Evaluate and compare model performances.
  - **Results:**
    - Logistic Regression Accuracy: 76.2%, F1 Score: 80.5%
    - SVM Accuracy: 75.1%, F1 Score: 79.2%
    - Random Forest Accuracy: 79.8%, F1 Score: 84.1%
    - XGBoost Accuracy: 82.4%, F1 Score: 86.2%
  - **Insight:** XGBoost outperformed other models.

- **Part 5: Hyperparameter Tuning** ⚙️
  - **Objective:** Find optimal model hyperparameters.
  - **Approach:**
    - Utilize Randomized Search for XGBoost.

- **Part 6: Final Model** 🌟
  - **Objective:** Build and evaluate the final XGBoost Classifier.
  - **Performance Metrics:**
    - Final XGBoost Accuracy: 82.4%
    - Final XGBoost F1 Score: 86.2%

## Key Findings and Results 📈

### Data Exploration

- **Statistical Summary:**
  - Average age: 40 (min 18, max 70)
  - Average income: $5000 (min $1200, max $15000)

### Conclusion and Insights 🌟

- The XGBoost model, with tuned hyperparameters, is highly accurate.
- Features such as age, income, and transaction history play crucial roles in predicting customer churn.

Explore the detailed analysis and model implementation in the [Project Repository](https://github.com/ashay-thamankar/deep-learning-and-machine-learning/tree/main/Machine%20Learning/Customer%20Churn%20Prediction%20Model). Dive in, gain insights, and enjoy the journey! 🚀

![Bar Chart Correlation with Churn](https://github.com/ashay-thamankar/deep-learning-and-machine-learning/blob/main/Machine%20Learning/Customer%20Churn%20Prediction%20Model/charts/bar%20correlation%20chart%20of%20target.png)
![Correlation Heatmap with Churn](https://github.com/ashay-thamankar/deep-learning-and-machine-learning/blob/main/Machine%20Learning/Customer%20Churn%20Prediction%20Model/charts/correlation%20%20of%20target%20heatmap.png)
![Countplot of Churn Status](https://github.com/ashay-thamankar/deep-learning-and-machine-learning/blob/main/Machine%20Learning/Customer%20Churn%20Prediction%20Model/charts/count%20plot%20of%20target.png)

Feel free to explore, gain insights, and have a fantastic journey! 🌟
