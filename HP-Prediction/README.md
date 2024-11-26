# House Price Prediction: Advanced Regression Techniques
This project predicts house prices using the House Prices: Advanced Regression Techniques dataset from Kaggle. It involves extensive Exploratory Data Analysis (EDA), feature engineering, and model training using various regression models to achieve accurate predictions. The best-performing model is selected based on the Root Mean Squared Error (RMSE) metric.

## Key Features
### Data Preprocessing:

Handling missing values using mean/mode imputation.
Encoding categorical variables using Label Encoding and One-Hot Encoding.
Log transformation of skewed numerical features for normalization.
Creation of new features such as:
TotalSqrtFeet: Total living area (ground + basement).
TotalBaths: Total bathrooms (full and half).
Binary features like IsGarage, IsFireplace, and IsWoodDeck.
### Exploratory Data Analysis:

Correlation heatmaps and pairplots to understand feature relationships.
Visualization of feature distributions and relationships with the target variable (SalePrice).
### Model Training and Evaluation:

Models tested:
Linear Regression
Random Forest Regressor
Gradient Boosting Regressor
Decision Tree Regressor
Gradient Boosting Regressor achieved the best performance with an RMSE of 0.1293.
### Hyperparameter Tuning:

Grid Search to optimize parameters for the best-performing model.
Project Workflow
### Data Preparation:

Read the train and test datasets.
Handle missing values and encode categorical variables.
Perform feature scaling and log transformations.
### Feature Engineering:

Add meaningful new features.
Handle skewed data for numerical columns.
### Model Training:

Train multiple regression models using cross-validation.
Select the model with the lowest RMSE for predictions.
### Model Optimization:

Use GridSearchCV to fine-tune hyperparameters for the best model.
### Prediction:

Predict house prices for the test dataset and prepare a submission file.
Results
Gradient Boosting Regressor was the best model with an RMSE of 0.1293 and 90.54% Accuracy.

Advanced feature engineering and data preprocessing significantly improved model performance.
Technologies Used
#### Python Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
#### Machine Learning Algorithms: Random Forest, Gradient Boosting, Decision Trees, Linear Regression
