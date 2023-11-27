# Customer Segmentation Analysis 🚀

## Overview

This project focuses on segmenting customers based on their credit card usage behavior. The dataset, comprising 18 behavioral variables for approximately 9000 active credit card holders over the last 6 months, provides valuable insights into customer patterns.

## Data Preprocessing 🛠️

### Importing Libraries and Dataset

- **Dataset Link:** [Credit Card Dataset](https://www.kaggle.com/datasets/arjunbhasin2013/ccdata)

### Data Exploration

- **Dataset Shape:** (8950, 18)
- **Data Types:**
  - 1 categorical, 14 numerical, 3 integer
- **Null Values:**
  - 'CREDIT_LIMIT' (1), 'MINIMUM_PAYMENTS' (313)

### Categorical and Numerical Features

- **Categorical Features:**
  - Identified 'CUST_ID' as a categorical feature.
- **Numerical Features:**
  - Explored 17 numerical features including 'BALANCE', 'PURCHASES', 'CREDIT_LIMIT', etc.

### Data Summary

- **Statistical Summary:**
  - Average balance: $1003.20
  - Average one-off purchase: $411.07
  - Average cash advance: $4494.45

## Dealing with Missing Values

- **Missing Values:**
  - Imputed 'CREDIT_LIMIT' and 'MINIMUM_PAYMENTS' with the mean.

### Encoding Categorical Data

- **Categorical Columns:**
  - 'CUST_ID' dropped as it does not impact the model.

### Correlation Analysis

- **Correlation Matrix:**
  - Visualized the correlation matrix using a heatmap.

## Elbow Method (Determining Optimal Clusters) 📊

- Employed the Elbow method to identify the optimal number of clusters.
- Concluded that 8 clusters provide meaningful segmentation.

## Model Selection 🤖

- **Model Chosen: KMeans Clustering**
  - KMeans is a popular unsupervised learning algorithm for clustering.
  - It partitions data into K clusters based on similarity.

## Building the Model 🏗️

- Constructed the KMeans model with 8 clusters.

## Extracting Insights 📈

- Created a DataFrame with cluster numbers and original features.
- Saved segmented customer data to a CSV file.

## Visualizations

- ![Elbow Graph for Clusters](https://github.com/ashay-thamankar/deep-learning-and-machine-learning/blob/main/Machine%20Learning/customer%20segmentation%20model/charts/elbo%20graph%20for%20clustors.png)
- ![Correlation with Target Heatmap](https://github.com/ashay-thamankar/deep-learning-and-machine-learning/blob/main/Machine%20Learning/customer%20segmentation%20model/charts/correlation%20with%20target%20heatmap.png)

## Overall Project Link

[Customer Segmentation Model](https://github.com/ashay-thamankar/deep-learning-and-machine-learning/tree/main/Machine%20Learning/customer%20segmentation%20model)

## Analysis Insights 📊

- **Optimal Clusters:**
  - The Elbow method suggests using 8 clusters for meaningful segmentation.

- **Customer Behavior:**
  - The dataset reflects diverse credit behaviors, showcasing varying balances, purchase amounts, and credit limits.

- **Segmentation Patterns:**
  - KMeans clustering provides insights into distinct patterns among customers based on their credit behavior.

- **Data Exploration:**
  - Further analysis could reveal additional patterns, contributing to a more comprehensive understanding of customer segmentation.

## Conclusion

This customer segmentation project successfully identifies distinct clusters based on credit card usage behavior. The chosen KMeans clustering model provides valuable insights that can inform targeted marketing strategies, enhancing overall customer experience.

Feel free to explore the project for a more in-depth understanding!

## Final Segmented Customer CSV File

[Download Segmented Customers CSV](https://github.com/ashay-thamankar/deep-learning-and-machine-learning/blob/main/Machine%20Learning/customer%20segmentation%20model/Segmented_customers_output.csv)
