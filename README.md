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

Upon running the project, you will find the following output files:

- `submission_ensemble.csv`: Predictions for the test data using the ensemble model.

- `text_analysis_TIMESTAMP.log`: Detailed logs of the training process and hyperparameter optimization for the best-performing ensemble model.

## Acknowledgments

This project was created by [Your Name] and is intended for educational purposes. It incorporates various techniques for gender prediction in Hebrew text data, including ensemble voting and dynamic hyperparameter tuning.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
