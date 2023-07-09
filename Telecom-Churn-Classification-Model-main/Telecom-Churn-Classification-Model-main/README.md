# Telecom Churn Classification Model
## Introduction
The Aim of this project is to utilize customer history and personal details to build a classification model that can accurately predict which customers are likely to leave the company.

## Libraries Used 
1. Pandas: for data manipulation and analysis
2. Numpy: for numerical computing and array manipulation
3. Plotly: for interactive data visualization
4. Matplotlib: for static data visualization
5. Seaborn: for statistical data visualization
6. Scikit-learn (sklearn): for machine learning modeling and evaluation
7. Open datasets: for accessing publicly available datasets for training and testing the model.

## Data Collection and Exploration
 I imported the telecom churn dataset using the open datasets module. Upon importing the data, I performed an initial exploration to gain insights into the data. This involved checking the information and statistics of the data, such as the number of rows and columns, the data types of the columns, and the presence of missing values. This initial exploration helped me get a better understanding of the data and enabled me to plan the next steps of the project, such as data cleaning, feature engineering, and modeling.
 
## Exploratory Data Analysis
Data visualization was performed to gain insights into the relationships between various factors and customer churn. Key factors affecting churn rate were identified through the analysis of the behavior of churn and non-churn customers. The insights gained from the visualizations aided in determining the most important features for building the predictive model and effectively communicating the results to stakeholders.

## Feature Selection 
Feature selection was performed based on the behavioral analysis and the collinearity between the features and the target variable (churn). Irrelevant columns were dropped and the most relevant columns were selected to build the predictive model. The selected features were then used to train the model and improve its accuracy. By considering the relationships between the features and the target variable, the model was made more effective and better results were achieved.

## Model Training and Evaluation 
The dataset was divided into three parts: training data, test data, and validation data. Different classification algorithms, including logistic regression, random forest, decision tree, and gradient boost, were applied to the validation data. The accuracy and classification report were evaluated for each model, and the best performing model was selected for further analysis. The results of the selected model were then compared to the actual values of the churn, and a confusion matrix was plotted to visualize the predictions. This process allowed me to compare the performance of different algorithms and determine which one was the best fit for the data.

# Decision Tree is the best model with accuracy: 0.9999047928848549



<div align="center">
<h3> Connect with me<a href="https://gifyu.com/image/Zy2f"><img src="https://github.com/milaan9/milaan9/blob/main/Handshake.gif" width="60"></a>
</h3> 
<p align="center">
    <a href="mailto:roshanguptark432@gmail.com" target="_blank"><img alt="Gmail" width="25px" src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/Gmail.svg"></a> 
    <a href="https://www.linkedin.com/in/roshan-sinha/" target="_blank"><img alt="LinkedIn" width="25px" src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/Linkedin.svg"></a>
    <a href="https://www.instagram.com/roshan_the_constant/?hl=en" target="_blank"><img alt="Instagram" width="25px" src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/Instagram.svg"></a>
    <a href="https://www.hackerrank.com/roshanguptark432" target="_blank"><img alt="HackerRank" width="25px" src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/HackerRank.svg"></a>
    <a href="https://github.com/roshancharlie" target="_blank"><img src="https://cdn.svgporn.com/logos/github-icon.svg" alt="Github logo" width="25px"></a>
</p>  
