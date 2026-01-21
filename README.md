# Imbalanced Learning Analysis

## Project Overview
This project analyzes how different sampling techniques affect the performance of machine learning models when working with highly imbalanced datasets.

## Dataset
Credit Card Fraud Dataset  
Source: https://github.com/AnjulaMehto/Sampling_Assignment

## Sampling Techniques Used
- Random UnderSampling  
- Random OverSampling  
- SMOTE  
- NearMiss  
- SMOTEENN  

## Machine Learning Models Used
- Logistic Regression  
- Decision Tree  
- Random Forest  
- K-Nearest Neighbors (KNN)  
- Naive Bayes  

## Results Summary
The experiment showed that different models performed best under different sampling strategies:
- Logistic Regression → NearMiss  
- Decision Tree → Random OverSampling  
- Random Forest → Random OverSampling  
- KNN → SMOTEENN  
- Naive Bayes → NearMiss  

## Conclusion
This project demonstrates that there is no universally best sampling technique for imbalanced datasets. Model performance depends strongly on the interaction between the algorithm and the sampling strategy, highlighting the importance of experimentation during model development.
