# SamplingTechniques
# Project: Evaluating ML Models with Different Sampling Techniques

## Overview

This project explores the impact of various sampling techniques on the performance of machine learning models. Sampling is a critical step in data preparation, influencing the generalizability and effectiveness of trained models. By examining different sampling strategies, the project aims to understand how diverse machine learning algorithms respond to subsets of data.

## Sampling in Machine Learning

Sampling involves selecting a subset of data from a larger population to draw inferences or build predictive models. In machine learning, sampling plays a crucial role in addressing imbalances within datasets, improving model training efficiency, and enhancing generalization to unseen data.

## Machine Learning Models

The project employs a set of diverse machine learning models:

1. **Logistic Regression**
   - A linear model suitable for binary classification problems.

2. **Decision Tree**
   - A tree-like model that makes decisions based on feature splits.

3. **Random Forest**
   - An ensemble model combining multiple decision trees to enhance accuracy and reduce overfitting.

4. **Support Vector Machine (SVM)**
   - A powerful algorithm for classification, regression, and outlier detection.

5. **k-Nearest Neighbors (k-NN)**
   - A non-parametric method relying on the similarity of data points for classification.

## Sampling Techniques

The project explores the following sampling techniques:

1. **Simple Random Sampling**
   - Selecting individuals randomly from the entire dataset.

2. **Stratified Sampling**
   - Dividing the population into homogeneous strata and sampling proportionally from each stratum.

3. **Systematic Sampling**
   - Choosing every \(k\)-th item from a list after selecting a random starting point.

4. **Cluster Sampling**
   - Dividing the population into clusters and randomly selecting entire clusters.

5. **Stratified Random Sampling**
   - Combining the features of both stratified and random sampling to ensure representative subsets.

## Workflow

1. **Data Loading:**
   - Load a balanced dataset (`balanced_df`) with features and labels.

2. **Model Definition:**
   - Define five diverse machine learning models.

3. **Sampling Techniques Implementation:**
   - Implement various sampling techniques, altering training datasets for each model.

4. **Model Training and Evaluation:**
   - Train each model on different training datasets created by the sampling techniques.

5. **Accuracy Calculation:**
   - Evaluate the accuracy of each model on a common test set.

6. **Results Display:**
   - Present the results in a matrix format, facilitating the comparison of model accuracies across different sampling scenarios.

