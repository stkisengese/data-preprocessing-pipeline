# data-preprocessing-pipeline
A comprehensive guide to data preprocessing and pipeline implementation using scikit-learn. This project demonstrates essential data cleaning techniques including missing value imputation, feature scaling, categorical encoding, and the powerful Pipeline API for building robust machine learning workflows.

## Features

This project is divided into six Jupyter notebooks, each focusing on a specific data preprocessing technique:

1.  **ex01_imputer_1.ipynb**: Demonstrates how to use `SimpleImputer` to handle missing values in a dataset. It shows how to fit the imputer on the training data and use it to transform both the training and test data.

2.  **ex02_scalar.ipynb**: Explains the importance of feature scaling and demonstrates how to use `StandardScaler` to standardize features. It highlights the process of fitting the scaler on the training data and applying it to the test data.

3.  **ex03_one_hot_encoder.ipynb**: Covers the one-hot encoding technique for converting categorical features into a numerical format. It uses `OneHotEncoder` and shows how to handle unknown categories that may appear in the test data.

4.  **ex04_ordinal_encoder.ipynb**: Introduces ordinal encoding for categorical features with a clear order. It demonstrates the use of `OrdinalEncoder` and how to specify the order of the categories.

5.  **ex05_categorical_variables.ipynb**: Shows how to apply different preprocessing techniques to different columns of a dataset using `make_column_transformer`. This notebook combines `OneHotEncoder` and `OrdinalEncoder` to preprocess a dataset with mixed feature types.

6.  **ex06_pipeline.ipynb**: Demonstrates how to build a complete machine learning workflow using the `Pipeline` class. It chains multiple preprocessing steps (imputation and scaling) with a final estimator (Logistic Regression) to create a single, streamlined model.