# Text Analysis - Predicting Writer Gender

## Overview

This GitHub repository showcases a gender prediction project for Hebrew text data, featuring ensemble voting-based modeling and dynamic hyperparameter tuning. It includes data preprocessing, TF-IDF vectorization, model selection, and adaptive hyperparameter optimization, and logs results for the best-performing ensemble model.

## Dataset

The project relies on the following dataset files:

- `annotated_corpus_for_train.csv`: This file contains annotated training data, including Hebrew text content and corresponding gender labels.

- `corpus_for_test.csv`: This file holds test data with Hebrew text content, utilized for making predictions.

## Requirements

Before running the project, ensure you have the following dependencies installed:

- Python (>=3.6)
- scikit-learn
- pandas
- numpy
- logging
- datetime

## Results

Upon running the project, the best-performing model is an SVM classifier with the following hyperparameters:

- C: 10.0
- Kernel: Sigmoid
- Max Iterations: 1000
- Degree: 2
- Coefficient 0: 0.0

The SVM model achieved a Cross-Validated Average F1 Score of 0.7703 on the provided training data. The predictions for the test data are saved in `submission_svm.csv`.

Detailed logs of the training process and hyperparameter optimization for this model are available in `text_analysis_TIMESTAMP.log`.

## Acknowledgments

This project was created by Alexey Kovalev and is intended for educational purposes. It incorporates various techniques for gender prediction in Hebrew text data, including ensemble voting and dynamic hyperparameter tuning.

