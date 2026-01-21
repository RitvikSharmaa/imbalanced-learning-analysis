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
<img width="573" height="302" alt="image" src="https://github.com/user-attachments/assets/07193df3-c619-4dbf-a3d4-5736a02e0feb" />

The experiment showed that different models performed best under different sampling strategies:
- Logistic Regression → NearMiss  
- Decision Tree → Random OverSampling  
- Random Forest → Random OverSampling  
- KNN → SMOTEENN  
- Naive Bayes → NearMiss

## Conclusion
The experiment clearly shows that the choice of sampling technique has a significant impact on model performance when working with imbalanced datasets. From the results obtained, Logistic Regression and Naive Bayes achieved their highest accuracy when combined with the NearMiss sampling technique, indicating that these models benefit from more selective undersampling of the majority class. Decision Tree and Random Forest models performed best with Random OverSampling, achieving accuracies of 98.69% and 100% respectively, which suggests that tree-based models handle duplicated minority samples effectively. The KNN model achieved its best performance with SMOTEENN (97.73%), demonstrating that a hybrid approach combining oversampling and noise removal improves neighborhood-based learning.

Overall, the results confirm that there is no single best sampling method for all models. Instead, the effectiveness of a sampling technique depends on the learning algorithm being used, and careful experimentation is essential when handling highly imbalanced datasets.
