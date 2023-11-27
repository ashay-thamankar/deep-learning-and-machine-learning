# Credit Card Fraud Detection 🕵️‍♂️💳

Welcome to the Credit Card Fraud Detection project! 🌟 In this project, we aim to build a robust model to detect fraudulent transactions in credit card data. Fraud detection is crucial to ensure the security of financial transactions and protect users from unauthorized activities.

## Dataset 📊

The dataset we are using is from Kaggle: [Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud). It contains transactions made by credit cards, with a mix of legitimate and fraudulent activities.

## Steps to Reproduce 🔄

### 1. Data Preprocessing 🛠️

#### 1.1 Download and Extract Data

1. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).
2. Install the Kaggle API by running `!pip install -q kaggle`.
3. Upload your Kaggle API key to the Colab notebook.
4. Download and unzip the dataset using Kaggle API.

#### 1.2 Explore the Data 🕵️‍♂️

- Load the dataset and examine its structure.
- Check for missing values.
- Explore data types and statistical summary.
- Visualize the distribution of transaction classes using a count plot.

![Count Plot of Target](https://github.com/ashay-thamankar/deep-learning-and-machine-learning/blob/main/Machine%20Learning/Credit%20Card%20Fraud%20Detection%20Model/charts/countplot%20of%20target.png)

### 2. Building the Model 🚀

#### 2.1 Splitting the Dataset

- Split the dataset into training and testing sets.

#### 2.2 Feature Scaling

- Standardize the features using StandardScaler to bring them to a common scale.

#### 2.3 Model Selection

1. **Logistic Regression**
   - Train a logistic regression model and evaluate its performance.
   - Accuracy: 0.9373

2. **Random Forest**
   - Build a random forest classifier and assess its accuracy.
   - Accuracy: 0.9995

3. **Support Vector Machine (SVM)**
   - Implement an SVM model and measure its effectiveness.
   - Accuracy: 0.9992

4. **XGBoost Classification**
   - Utilize XGBoost for classification and evaluate its performance.
   - Accuracy: 0.9996

### 3. Final Model 🏆

- Choose the most effective model (XGBoost) based on performance metrics.
- Train the final model on the entire dataset.

### 4. Predicting a Single Observation 🧐

- Demonstrate how the final model predicts a single observation.

## Results and Insights 📈

- Display the confusion matrix for each model.
- Provide accuracy, precision, recall, and F1-score for each model.
- Conduct cross-validation to validate the model's performance.

![Correlation with Target Bar Chart](https://github.com/ashay-thamankar/deep-learning-and-machine-learning/blob/main/Machine%20Learning/Credit%20Card%20Fraud%20Detection%20Model/charts/correlation%20with%20targer%20bar%20chart.png)

## Project Repository 📁

Explore the entire project on [GitHub](https://github.com/ashay-thamankar/deep-learning-and-machine-learning/tree/main/Machine%20Learning/Credit%20Card%20Fraud%20Detection%20Model). Feel free to delve into the code, experiment with different models, and contribute to the project! If you have any questions or suggestions, don't hesitate to reach out. Happy coding! 🚀👩‍💻👨‍💻
