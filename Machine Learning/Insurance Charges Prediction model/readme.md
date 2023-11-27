# Insurance Charges Prediction 🚑💸

## Introduction 🌐

Welcome to the Insurance Charges Prediction project! This initiative utilizes machine learning regression techniques to predict individual medical costs billed by health insurance. The dataset encompasses crucial factors such as age, gender, BMI, number of children, smoking status, residential region, and insurance charges.

## Dataset 📊

The dataset is sourced from Kaggle: [Insurance Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)

### Data Fields 📋

- **Age:** Age of the primary beneficiary.
- **Gender:** Insurance contractor gender (female, male).
- **BMI:** Body mass index, providing an understanding of body weight relative to height.
- **Children:** Number of children covered by health insurance / Number of dependents.
- **Smoking Status:** Smoking status (yes, no).
- **Region:** The beneficiary's residential area in the US (northeast, southeast, southwest, northwest).
- **Charges:** Individual medical costs billed by health insurance.

## Keywords and Definitions 📘

### Regression:
Regression is a statistical method used to model the relationship between a dependent variable and one or more independent variables. In this context, it helps predict insurance charges based on various features.

### BMI (Body Mass Index):
BMI is a measure of body fat based on an individual's weight and height. It provides an objective index of body weight and is calculated as \( \frac{\text{weight (kg)}}{\text{height (m)}^2} \).

### R-squared:
R-squared is a statistical measure of the proportion of the response variable's variance that is captured by the model. It ranges from 0 to 1, where 0 indicates that the model does not explain the variance, and 1 indicates a perfect fit.

## Project Overview 🛠️

### Part 1: Data Exploration

#### Step 1: Importing the Data 📥

Load the dataset for exploration, analysis, and understanding the key features affecting insurance charges.

#### Step 2: Understanding the Data 🕵️

Explore the dataset for patterns, missing values, and key statistical summaries.

### Part 2: Data-Driven Insights and Analysis 📊

#### Smoking Impact Analysis 🚭

Analyze the significant impact of smoking status on insurance charges, supported by statistical metrics.

##### Formula 1: **Smoking Impact Index**
\[ \text{Smoking Impact Index} = \frac{\text{Mean Charges for Smokers}}{\text{Mean Charges for Non-Smokers}} \]

**Numerical Analysis:**
- Mean Charges for Smokers: \$32,050.23
- Mean Charges for Non-Smokers: \$8,434.27
- Smoking Impact Index: 3.80 (indicating significantly higher charges for smokers)

#### BMI and Age Examination 📈

Examine the influence of BMI and age on insurance charges, backed by data-driven insights.

##### Formula 2: **BMI-Age Interaction**
\[ \text{BMI-Age Interaction} = \frac{\text{Sum of Charges for High BMI and High Age}}{\text{Total Sum of Charges}} \]

**Numerical Analysis:**
- Sum of Charges for High BMI and High Age: \$285,000
- Total Sum of Charges: \$1,344,323.51
- BMI-Age Interaction: 0.21 (suggesting a moderate impact of BMI and age on charges)

### Part 3: Predictive Modeling

Explore machine learning models for predicting insurance charges based on key features.

#### Regression Models:

1. **Linear Regression:**
   - Utilized for establishing a linear relationship between features and charges.
   - R-squared: 0.7999.

2. **Random Forest Regression:**
   - Employed an ensemble learning method for improved prediction.
   - R-squared: 0.8820.

3. **XGBoost Regression:**
   - Utilized a gradient boosting algorithm for enhanced accuracy.
   - R-squared: 0.8994.

### Results and Conclusions 📊🎉

The analysis uncovers deep insights into factors affecting insurance charges. Machine learning models demonstrate predictive capabilities, offering actionable insights into potential medical costs for individuals.

### Key Findings and Formulas 🤓

1. **Smoking Impact Index:** Indicates the relative impact of smoking on charges.
2. **BMI-Age Interaction:** Highlights the combined impact of BMI and age on charges.

### Data Exploration and Analysis Charts 📊

#### Distplot of Target Variable and Skew 📈
![Distplot of Target Variable](https://github.com/ashay-thamankar/deep-learning-and-machine-learning/blob/main/Machine%20Learning/Insurance%20Charges%20Prediction%20model/charts/distplot%20of%20target.png)

#### Correlation with Target Heatmap 🔍
![Correlation with Target Heatmap](https://github.com/ashay-thamankar/deep-learning-and-machine-learning/blob/main/Machine%20Learning/Insurance%20Charges%20Prediction%20model/charts/corr%20with%20target%20heatmap%20.png)

#### Bar Chart - Correlation with Target 📊
![Bar Chart - Correlation with Target](https://github.com/ashay-thamankar/deep-learning-and-machine-learning/blob/main/Machine%20Learning/Insurance%20Charges%20Prediction%20model/charts/bar%20chart%20corr%20with%20target.png)

### Overall Project Link on GitHub 🌐
[Insurance Charges Prediction Project](https://github.com/ashay-thamankar/deep-learning-and-machine-learning/tree/main/Machine%20Learning/Insurance%20Charges%20Prediction%20model)

## Acknowledgments 🙏

Special thanks to [Mirichoi0218 on Kaggle](https://www.kaggle.com/datasets/mirichoi0218/insurance) for providing the dataset.

**Happy Exploring!** 👩‍💻👨‍💻
