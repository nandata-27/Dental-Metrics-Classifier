# Dental Metric Classification Using Machine Learning

This project explores if dental measurements (Buccolingual and Mesiodistal) can be used to classify individuals by sex using supervised machine learning models. The dataset consists of dental metrics collected across populations and sex, with the goal of developing accurate, interpretable classifiers from biologically relevant features.

## Project Summary:

- Classify sex based on multivariate dental measurements using machine learning.
- Data: https://zenodo.org/records/8067443/files/dental%20metric%20data.csv?download=1
- Preprocessing and ML steps:
  - Imputed missing values using group-level means (by population and sex).
  - Scaled features with MinMaxScaler.
  - Performed univariate feature selection.
  - Feature Selection: ANOVA F-test with `SelectKBest`
  - Models Compared:
    - k-Nearest Neighbors (k-NN)
    - Random Forest
    - Support Vector Machine (SVM)
    - Naive Bayes
    - Multi-Layer Perceptron (MLP)

## Requirements
Python ≥ 3.8  
Used libraries:
bash
pandas
numpy
scikit-learn
matplotlib
