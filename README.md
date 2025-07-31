# Customer Churn Prediction

## Project Overview
My Master's Degree final project, which predicts the likelihood for a customer to churn, segments them as "low-risk", "moderate-risk", or "high-risk" to churn, and gives
retention recommendations for each. The customers in this project are based on customers found in data from a fictional telecommunications company, Telco.

## Tools and Technologies
Python, Pandas, NumPy, MatPlotLib, Seaborn, MinMaxScaler, StandardScaler, SciPy Stats, GridSearchCV, Pipeline, SMOTENC, Random Forest Classifier, 
Logistic Regression Classifier, Extreme Gradient Boosting Classifier (XGB), Scaled Vector Classifier (SVC), Gaussian Naive Bayes, Confusion Matrix,
Precision Recall Curve

## Project Structure
   * requirements.txt - List of packages and dependencies used in my environment for this project.
     
   * Telco_dataset.xlsx - Dataset utilized in this project.
     
   * MastersCapstoneShowcase_KConverse.pptx - Powerpoint presentation used when presenting/discussing the project.
     
   * FinalPaper_KConverse_DATA695 - Final Paper taking the reader through the project from conception to results and future steps.
     
   * EDA_Telco_Churn_Project_KConverse.ipynb - Jupyter Notebook of Exploratory Data Analysis done for the project, including some preliminary feature selection
     and engineering steps.
   
   * Churn_Prediction_Model_Build_and_Test_KConverse.ipynb - Jupyter Notebook of the prediction model building and testing process for this project. 
     
   * (Test File)_Model_Testing_For_Features.ipynb - Additional testing file added to showcase a part of the model building/feature engineering process,
     but not necessary for running.

## How to Run
1. Clone the repo
2. Install requirements: 'pip install -r requirements.txt'
3. Run notebooks in order (Exploratory Data Analysis (EDA), then Build and Test. Test File is there to help showcase a part of the project process,
   but not necessary for running the project.) 

## Results
Using a hyperparameter-tuned logistic regression model with SMOTENC applied, I achieved an 84% class 1 recall score, .8815 ROC-AUC score, and classified 
only 4.33% False Negatives (61) in a confusion matrix of 808 True Negatives, 61 False Negatives, 313 True Positives, and 227 False Positives. The full 
results will be in the "Results" section of the Word Document.

## Contact
Created by Kyle Converse - feel free to connect!
