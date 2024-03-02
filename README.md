# Anemia Detection with Machine Learning Models

This repository contains Python machine learning code for the detection of anemia using data from Kaggle, provided by the username Biswa Ranjan Rao. The dataset can be accessed [here](https://www.kaggle.com/datasets/biswaranjanrao/anemia-dataset).

## Overview

The dataset consists of 1421 samples with six attributes: gender, hemoglobin, mean corpuscular hemoglobin (MCH), mean corpuscular hemoglobin concentration (MCHC), mean corpuscular volume (MCV), and result.

The `result` attribute (class) is represented by binary values: 0 for non-anemic and 1 for anemic. The dataset's memory size is 66.7 MB.

## Introduction to Anemia

Anemia is a medical condition characterized by a deficiency of healthy red blood cells in the body or a reduction in the amount of hemoglobin in the blood. Symptoms include fatigue, weakness, shortness of breath, pale skin, and irregular heartbeat.

## What's Inside

- Exploratory Data Analysis
- Statistical tests:
        t-test,
        Odds ratio,
        Chi-square test
- Feature Selection:
        Correlation,
        SelectKBest,
        Extra Tree Classifier
- Scaling features:
        Log,
        Standardization,
        Normalization
- Class imbalance handling:
        Random Undersampling,
        Random Oversampling,
        SMOTE,
        ADASYN
- Data Leakage handling
- Algorithms employed:
        Decision Tree (DT),
        Random Forest (RF),
        Logistic Regression (LG),
        K-Nearest Neighbors (KNN),
        Support Vector Machine (SVM),
        Gaussian Naive Bayes (NB)
- Performance measured:
        Accuracy,
        Area Under the Curve,
        Precision, Recall,
        F1 Score,
        Kappa Stat
- Hyperparameter tuning with GridsearchCV
- 5-fold cross-validation

## Contributing

Contributions are welcome! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.
