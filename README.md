# SAMPLING

## Overview

This assignment focuses on exploring and implementing different sampling techniques for credit card fraud detection using a provided CSV dataset. The goal is to train five distinct models using various sampling methods and evaluate their accuracy in detecting fraudulent transactions. The models to be used are RandomForestClassifier, SVC , AdaBoostClassifier, LogisticRegression and DecisionTreeClassifier.

## Dataset

The dataset for this assignment is a CSV file containing credit card transactions. The data includes various features such as transaction amount, timestamp, and others. It is essential to handle imbalanced classes, as fraudulent transactions are typically rare compared to legitimate ones.


## Sampling Techniques

The assignment involves applying five different sampling techniques to address the imbalanced nature of the data. The selected techniques are:

1. **Simple Random Sampling**
2. **Stratified Sampling**
3. **Cluster Sampling**
4. **Random Over Sampling**
5. **SMOTE (Synthetic Minority Over-sampling Technique)**

## Models

Five different machine learning models will be trained on each of the sampled datasets. The selected models are:

1. **RandomForestClassifier**
2. **SVC**
3. **AdaBoostClassifier**
4. **LogisticRegression**
5. **DecisionTreeClassifier**

## Instructions

1. **Data Loading:**
   - Load the credit card dataset from the provided CSV file.
   - Understand the dataset's structure and features.

2. **Data Preprocessing:**
   - Handle missing values, if any.
   - Explore and visualize the class distribution to understand the data imbalance.

3. **Sampling:**
   - Apply the five sampling techniques to create five different datasets.
   - Ensure the balance between fraudulent and legitimate transactions in the sampled datasets.

4. **Model Training:**
   - Train a AdaBoost, LogisticRegression , DecisionTree , SVC, and Random Forest model on each sampled dataset.

5. **Model Evaluation:**
   - Evaluate the accuracy of each model on a separate test dataset (not used during training).
   - Compare the performance of models trained on different sampling techniques.

6. **Results and Conclusion:**
   - Summarize the findings, comparing the effectiveness of each sampling technique in improving model accuracy for credit card fraud detection.
