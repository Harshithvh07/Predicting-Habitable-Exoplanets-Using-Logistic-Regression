# Predicting-Habitable-Exoplanets-Using-Logistic-Regression

## Introduciton 
This project applies Logistic Regression to classify the exoplanets are habitable or not based on various features like planet radius , planet mass , equlibrium temperature , stellar mass and other stellar and planet features. The aim of the model is to predict if an exoplanet falls within habitable zone or not. 

## About the Dataset 
The data set used in this project is from NASA's Exoplanet archive [Exoplanet Archive](https://exoplanetarchive.ipac.caltech.edu/)

## Methodology 
The data was loaded and clean , removed unwanted features and replaced missing values with mean of respective column. Logistic Regression model was chosen for classification task. The data was split into 70% training and 30% test. The model was evaluated based on accuracy , mean squared error , mean absolute error and R-squared. 

## Results 
The model achieved an accuracy of 0.9564220183486238 on the test set, indicating how well the model is classifying planets as habitable or not. 

## Requirements 
- Pandas
- Matplotlib
- scikit-learn
- numpy

## References
1. NASA Exoplanet Archive: [Exoplanet Archive](https://exoplanetarchive.ipac.caltech.edu/)
2. Logistic Regression Documentation (scikit-learn): [Logistic Regression Docs](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html)

