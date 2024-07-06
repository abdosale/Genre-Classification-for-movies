

# Overview
This project aims to create a machine learning model that can predict the genre of a movie based on its plot summary or other textual information. Techniques like TF-IDF and classifiers such as Naive Bayes, Logistic Regression, and Support Vector Machines are used.

# Data Preparation
The training data should be in the format: ID:::TITLE:::GENRE:::DESCRIPTION.
The test data should be in the format: ID:::TITLE:::DESCRIPTION.
The true labels for the test data should be in the test_data_solution.txt file in the format: ID:::TITLE:::GENRE:::DESCRIPTION.
The script processes and cleans this data, dropping any rows with missing values.

# Model Training
Three models are trained using a pipeline with TF-IDF vectorization:

Logistic Regression
Support Vector Machine (SVM)
Multinomial Naive Bayes
The training data is used to fit these models.

# Model Evaluation
The models are evaluated on the test data, and various metrics such as precision, recall, and confusion matrix are computed to assess their performance.

# Contributing
Contributions are welcome! Please feel free to submit a Pull Request.
