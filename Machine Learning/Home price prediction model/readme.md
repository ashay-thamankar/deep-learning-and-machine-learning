# House Price Prediction Model 🏡📈

## Data Fields 📊

Before diving into the project steps, let's understand the key data fields:

- **SalePrice:** Property sale price in dollars (target variable).
- **MSSubClass:** Building class.
- **MSZoning:** General zoning classification.
- **LotFrontage:** Linear feet of street connected to the property.
- **LotArea:** Lot size in square feet.
- ... (and many more)

## Project Steps 🛠️

### Part 1: Data Preprocessing

#### Step 1: Data Exploration

1. **Import Libraries and Load Dataset:**
   - Utilized pandas library to load the dataset.
   - Explored the first few rows to understand the data structure.

2. **Handle Missing Values:**
   - Checked for missing values in each column.
   - Dropped columns with more than 50% null values.

3. **Impute Missing Values:**
   - Imputed missing numerical values with mean.
   - Imputed missing categorical values with mode.

4. **Data Visualization:**
   - Utilized distplot to visualize the distribution of the target variable (SalePrice).
   - Created a correlation matrix to understand feature relationships.

   ![Correlation with Target Variable](https://github.com/ashay-thamankar/machine-learning-and-deep-learning/raw/main/Machine%20Learning/Home%20price%20prediction%20model/charts/correlation%20with%20target%20value.png)
   *Correlation with Target Variable*

#### Step 2: Splitting the Dataset

5. **Split Data into Training and Testing Sets:**
   - Split the dataset into 80% training and 20% testing sets.
   - Ensured the random_state parameter for reproducibility.

6. **Prepare Features and Target Variable:**
   - Separated features (independent variables) and the target variable (SalePrice).
   - Checked the dimensions of the training and testing sets.

#### Step 3: Feature Scaling

7. **Standard Scaling:**
   - Applied standard scaling to features using the StandardScaler.
   - Ensured features are on a similar scale for better model performance.

### Part 2: Building the Model

#### Step 4: Model Selection

8. **Multiple Model Implementation:**
   - Implemented linear regression, random forest regression, and XGBoost regression.
   - Evaluated models using R-squared score.

9. **Model Performance Evaluation:**
   - Random Forest R-squared: 0.84, Linear Regression R-squared: 0.65, XGBoost R-squared: 0.78.
   - Selected random forest as the best-performing model.

### Part 3: Hyperparameter Optimization

#### Step 5: Tuning the Model

10. **RandomizedSearchCV:**
    - Utilized RandomizedSearchCV for hyperparameter optimization.
    - Searched for the best hyperparameters.

11. **Optimal Hyperparameters:**
    - Found optimal hyperparameters for the random forest model.

### Part 4: Final Model

#### Step 6: Implementation

12. **Build Final Model:**
    - Constructed the final random forest regressor using optimal hyperparameters.
    - Evaluated the model's performance on the test set.

## Project Conclusion 🎉

The house price prediction model based on the random forest regression algorithm achieved an impressive R-squared score of 0.84, indicating strong predictive capability.

### Insights 🤓

- Random forest outperformed linear regression and XGBoost.
- Feature scaling positively impacted model performance.
- Hyperparameter tuning enhanced the model's predictive power.

### Key Takeaways 🚀

- Random forest emerged as the most accurate predictor.
- Proper handling of missing values and scaling contributed to improved accuracy.
- Hyperparameter fine-tuning played a crucial role in achieving optimal performance.

### Future Directions 🔮

- Explore advanced feature engineering techniques.
- Experiment with other regression algorithms.
- Consider ensemble methods for further improvement.

### Formulas for Understanding 📈

- **R-squared Formula:**
  ![R-squared Formula](https://render.githubusercontent.com/render/math?math=R^2%20=%201%20-%20\frac{SS_{\text{residual}}}{SS_{\text{total}}})

- **Standard Scaling Formula:**
  ![Standard Scaling Formula](https://render.githubusercontent.com/render/math?math=z%20=%20\frac{x%20-%20\mu}{\sigma})

## Project Images 📸

- **Heatmap to Check Null Values:**
  ![Heatmap to Check Null Values](https://github.com/ashay-thamankar/machine-learning-and-deep-learning/raw/main/Machine%20Learning/Home%20price%20prediction%20model/charts/heatmap%20to%20check%20null.png)
  *Heatmap to Check Null Values*

- **Positively Correlated Features:**
  ![Positively Correlated Features](https://github.com/ashay-thamankar/machine-learning-and-deep-learning/raw/main/Machine%20Learning/Home%20price%20prediction%20model/charts/positively%20correlated%20features.png)
  *Positively Correlated Features*

- **Target Value Skewness and Distribution:**
  ![Target Value Skewness and Distribution](https://github.com/ashay-thamankar/machine-learning-and-deep-learning/raw/main/Machine%20Learning/Home%20price%20prediction%20model/charts/target%20skewness.png)
  *Chart shows the target value skewness and distribution*

**Feel free to explore the Colaboratory file for a detailed walkthrough!** 📓✨

**Happy Exploring!** 👩‍💻👨‍💻
