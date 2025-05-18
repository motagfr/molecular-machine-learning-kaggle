# Molecular Machine Learning Kaggle Competition

This repository contains a Jupyter notebook designed for participation in the Kaggle competition: [Molecular Machine Learning](https://www.kaggle.com/competitions/molecular-machine-learning/overview).

## About the Competition
The goal of this competition is to predict the T80 lifetime of organic molecules using a variety of molecular descriptors. The dataset includes both training and test sets, with the test set lacking the target T80 values (as is standard in Kaggle competitions).

## Notebook Overview
This notebook walks through a typical machine learning workflow for tabular data, including:

- **Data Loading and Exploration:**
  - Loads the training and test datasets.
  - Explores data types, missing values, and feature distributions.
- **Feature Engineering and Preprocessing:**
  - Handles categorical and numerical features.
  - Removes object-type columns and applies scaling and transformation to numerical features.
- **Model Training and Validation:**
  - Trains several regression models (SVM, Lasso, Ridge, Decision Tree, Gradient Boosting, Random Forest, etc.).
  - Performs hyperparameter tuning using grid search and cross-validation.
  - Evaluates models using metrics such as RMSE and MSLE.
  - Visualizes model performance and feature importances.
- **Prediction:**
  - Generates predictions for the test set (note: true T80 values are not available for the test set).

## Citation
David M. Friday, Changhyun Hwang, Seungjoo Yi, Jason L. Wu, Tiara C. Torres-Flores, Martin D. Burke, Charles M. Schroeder, Ying Diao, Nicholas E. Jackson. Molecular Data Machine Learning. https://kaggle.com/competitions/molecular-machine-learning, 2025. Kaggle.

---

For more details, see the notebook file `Molecular model.ipynb` in this repository.
