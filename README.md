# Sonar-Mine-Rock-Classifier
A machine learning project that classifies sonar data to determine whether an object is a mine or a rock, utilizing Logistic Regression. This project demonstrates data preprocessing, model training, and evaluation techniques.

## Project Overview
This project implements a machine learning model to classify objects detected by sonar as either a 'mine' or a 'rock'. The dataset used consists of sonar signals bounced off various objects, and the goal is to accurately distinguish between the two categories. A Logistic Regression model is trained and evaluated for this classification task.

## Dataset
Dataset Link "https://drive.google.com/file/d/1pQxtljlNVh0DHYg-Ye7dtpDTlFceHVfa/view"

The dataset contains 60 features representing sonar signal patterns and a target variable indicating whether the object is 'M' (Mine) or 'R' (Rock).

## Features
- Data loading and initial exploration.
- Data preprocessing including separation of features and target.
- Training/Test split for model evaluation.
- Logistic Regression model implementation.
- Model evaluation using accuracy score.
- Predictive system demonstration for new data points.

## Technologies Used
- Python
- Pandas (for data manipulation)
- NumPy (for numerical operations)
- Scikit-learn (for machine learning models and utilities)


## Model Performance
The Logistic Regression model achieved the following accuracy scores:
-   **Training Data Accuracy:** 83.42%
-   **Test Data Accuracy:** 76.19%



## License
This project is licensed under the MIT License - see the `LICENSE` file for details.
