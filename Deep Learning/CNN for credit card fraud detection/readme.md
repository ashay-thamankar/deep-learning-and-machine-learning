# Credit Card Fraud Detection with Convolutional Neural Network (CNN) 🛡️💳

## Overview

Welcome to the Credit Card Fraud Detection project using Convolutional Neural Networks (CNN). The primary objective is to employ advanced deep learning techniques to identify and prevent fraudulent credit card transactions. By analyzing transactional data, the CNN model distinguishes between legitimate and fraudulent activities, contributing to enhanced security in financial transactions.

## Installation and Setup

1. **TensorFlow Installation:**
   Ensure you have TensorFlow installed to run the CNN model.

2. **Kaggle Dataset Setup:**
   - Install the Kaggle library to facilitate data retrieval.
   - Upload your Kaggle API key following the provided instructions.

3. **Download and Unzip Dataset:**
   Download and unzip the credit card fraud dataset from Kaggle for model training.

## Data Preprocessing

1. **Load and Check Dataset:**
   Load the dataset and perform an initial check for any missing values.

2. **Balance the Dataset:**
   Create a balanced dataset by combining instances of both fraudulent and non-fraudulent transactions.

3. **Split and Scale:**
   Divide the dataset into training and testing sets. Scale the features using StandardScaler to ensure consistent data representation.

4. **Reshape Data:**
   Modify the data shape to align with the requirements of the CNN architecture.

## Building the Model

The CNN model architecture involves various layers such as convolutional layers, batch normalization, max-pooling, dropout, and dense layers. This design allows the model to learn intricate patterns in the data.

## Training the Model

Train the CNN model on the preprocessed dataset. During this phase, monitor the training progress and adjust hyperparameters as needed to enhance model performance.

## Model Evaluation

Evaluate the trained model on the test set to assess its performance. Utilize metrics such as confusion matrix and accuracy score to gauge the model's effectiveness.

## Learning Curve 📈

![Learning Curve](https://github.com/ashay-thamankar/deep-learning-and-machine-learning/blob/main/Deep%20Learning/CNN%20for%20credit%20card%20fraud%20detection/charts/learning%20curve.png)

Visualize the learning curve to gain insights into the model's training and validation performance over epochs. This graphical representation aids in understanding how well the model learns from the training data.

## Conclusion

This project demonstrates the application of Convolutional Neural Networks for credit card fraud detection. By incorporating deep learning, the model excels at identifying anomalous patterns, contributing to the overall security of credit card transactions.

🚀 Thank you for exploring this Credit Card Fraud Detection project! If you have any questions or feedback, feel free to reach out. Stay secure! 🌐🔒
