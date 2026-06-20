# Online Shopper Purchase Intention Prediction

## Project Overview

This project predicts whether an online visitor will make a purchase based on their browsing behavior. A Decision Tree Classifier was developed using a complete machine learning pipeline that includes preprocessing, feature transformation, hyperparameter tuning, and pruning.

## Dataset

* **Source:** Online Shoppers Purchasing Intention Dataset
* **Records:** 12,330 user sessions
* **Target Variable:** Revenue (Purchase/No Purchase)
* **Features:** Administrative visits, Product-related activity, Page values, Bounce rates, Visitor type, Month, Weekend, and more.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Pipeline
* ColumnTransformer
* GridSearchCV

## Workflow

1. Exploratory Data Analysis (EDA)
2. Data Preprocessing

   * StandardScaler for numerical features
   * OneHotEncoder for categorical features
3. Pipeline Creation using ColumnTransformer
4. Decision Tree Classification
5. Hyperparameter Tuning with GridSearchCV
6. Decision Tree Pruning
7. Model Evaluation using F1-Score

## Model Evaluation

Since the dataset is imbalanced, the **F1-Score** was used as the primary evaluation metric. Decision Tree pruning helped reduce overfitting and improve generalization.

## Key Learning Outcomes

* Machine Learning Pipelines
* Feature Engineering
* Handling Imbalanced Data
* Decision Tree Pruning
* Hyperparameter Tuning
* Model Evaluation

