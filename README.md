# Using machine learning to detect fraudlent transactions

This repository contains the code for my Data Science MSc dissertation, titled "Using machine learning to detect fraudulent transactions."

Due to the highly imbalanced nature of the PaySim dataset Synthethic Minority  Over-sampling Technique (SMOTE) was applied alongside, random under-sampling and Label encoding to ensure that the appropriate data pre-processing had taken place before intialising the models for the purposes of our study. 

In this project, I explored a plethora of machine learning techniques and utilised hyperparameter optimization to compare the performance of various models. The goal was to identify the most effective model for detecting fraudulent transactions using a Kaggle dataset.

## Machine Learning Models Explored 📊: 

- **XGBoost**
- **Random Forest**
- **Logistic Regression**
- **K-Means Clustering**

GridSearchCV is then applied as the method for determining the optimal hyperparameter split for my XGBoost and Random forest models, as they perform the best at fraudlent transaction detection. 

The final results suggest that XGBoost was the best model out of the models tested, but hyperparameter optimisation could have been further optimised to enhance resutls further, but due to hardware constraints we were unable to for the purposes of this research. 
