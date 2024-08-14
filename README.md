# Epileptic Seizure Recognition using Machine Learning

This repository contains the implementation of a machine learning project aimed at classifying epileptic seizures using EEG data. Various classifiers, including Random Forest, Gradient Boosting, XGBoost, Neural Networks, AdaBoost, Bagging, and Stacking, are used to achieve high accuracy in detecting seizures.

# Introduction

Epileptic seizures are sudden bursts of electrical activity in the brain that can cause a variety of symptoms. This project leverages EEG data to classify whether a seizure is occurring or not. We explore different machine learning models to find the most accurate classifier for this task.

# Dataset

The dataset used for this project is the Epileptic Seizure Recognition dataset, which contains EEG recordings from 115 subjects. The data consists of multiple features representing EEG measurements, with a binary label indicating the presence of a seizure.

# Data Preprocessing

Loading Data: The dataset is loaded and examined for missing values and duplicates.
Label Adjustment: The target variable y is converted into a binary label.
Handling Imbalance: SMOTE (Synthetic Minority Over-sampling Technique) is applied to balance the class distribution.
Feature Scaling: Data is standardized using StandardScaler for better model performance.

# Feature Extraction

Wavelet Transform (DWT) is applied to extract features from the EEG data. We use the Daubechies wavelet (db4) with 5 levels of decomposition to calculate features such as energy, entropy, standard deviation, variance, and mean absolute value.

# Modeling

Various machine learning models are implemented and evaluated:
Random Forest Classifier
Gradient Boosting Classifier
XGBoost Classifier
Neural Network
AdaBoost Classifier
Bagging Classifier
Stacking Classifier

# Evaluation Metrics:

Accuracy
Sensitivity
Specificity
These metrics are calculated using cross-validation and confusion matrices to ensure robust performance.

# Results

Random Forest Classifier: Achieved average accuracy, sensitivity, and specificity through cross-validation.
Gradient Boosting: Produced high accuracy with sensitivity and specificity measurements.
XGBoost: Demonstrated competitive performance with significant sensitivity and specificity.
Neural Network: Provided satisfactory results with a well-structured architecture.
AdaBoost, Bagging, and Stacking: Further improved the classification results by combining the strengths of individual models.

# Conclusion

This project demonstrates the effectiveness of different machine learning models in classifying epileptic seizures using EEG data. The use of wavelet transform for feature extraction and various ensemble methods significantly enhances the classification accuracy.


