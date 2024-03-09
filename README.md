# Customer Churn Prediction with Machine Learning

This Jupyter notebook analyzes customer data from a telecom company to build machine learning models that can predict whether a customer will churn or not. Churn prediction is an important task for any company as retaining existing customers is typically much more cost effective than acquiring new ones.

### Technologies Used

- Python
- pandas, matplotlib for data analysis and visualization
- scikit-learn for machine learning modeling

The notebook performs the following key steps:

### Data Collection and Pre-processing

- Imports the Telco customer dataset which contains over 7000 rows of customer information
- Drops irrelevant columns like customer ID
- One-hot encodes categorical features to prepare for modeling
- Splits data into train and test sets for model evaluation

### Exploratory Data Analysis

- Visualizes key metrics like tenure, monthly charges etc grouped by churn
- Identifies relationships that might impact churn

### Model Building and Evaluation
- Implements Logistic Regression, Decision Trees, SVM and other classifiers
- Computes accuracy, F1 scores on test set to identify the best model
- Logistic Regression performs the best with over 75% accuracy

### Business Insights
- Identifies customers most likely to churn based on features
- Suggests targeting customers with high tenure but lower spend with retention offers

This notebook demonstrates my end-to-end abilities in data collection, cleaning, exploratory analysis, predictive modeling and providing business oriented insights. I have experience building similar churn prediction and recommendation models for enterprises. Please check out my other Jupyter notebooks and feel free to reach out if you have any other questions!


