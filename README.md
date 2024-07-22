# Customer-Churn-Prediction-using-PySpark

This project utilizes PySpark for customer churn prediction for a Telecommunications company. It demonstrates data loading, exploratory data analysis (EDA), data preprocessing, feature preparation, model training and evaluation, and provides actionable insights to reduce customer churn.

**Key Components**

Data Loading: Loads data from dataset.csv using PySpark.

Exploratory Data Analysis (EDA): 
Analyzes numerical feature distributions using histograms and correlation matrices.
Explores categorical feature value counts.

Data Preprocessing:
Imputes missing values using mean strategy.
Removes outliers based on tenure.

Feature Preparation:
Standardizes numerical features.
Applies String Indexing and OneHotEncoder to categorical features.
Combines all features into a final feature vector.

Model Training and Evaluation:
Splits the dataset into training and test sets.
Trains a Decision Tree model and evaluates performance using AUC-ROC.
Performs hyperparameter tuning on maxDepth.

Insights and Recommendations:
Visualizes feature importance to identify key factors impacting churn.
Analyzes churn rates by contract type and suggests offering incentives for longer-term contracts.
