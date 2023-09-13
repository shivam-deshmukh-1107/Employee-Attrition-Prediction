# Employee Attrition Prediction Project

## Overview

This project aims to predict employee attrition using machine learning models. Employee attrition refers to the phenomenon where employees leave an organization for various reasons, such as finding a new job, retirement, or dissatisfaction with their current workplace. Predicting attrition can help organizations take proactive measures to retain valuable employees and maintain workforce stability.

## Data

The dataset used in this project contains information about employees, including various features such as age, education, job satisfaction, and attrition status (whether an employee left or not). The dataset was sourced from [source_link_here].

## Preprocessing

The data preprocessing steps involved:
- Handling missing values
- Encoding categorical variables
- Splitting the dataset into training and testing sets
- Addressing class imbalance using SMOTE (Synthetic Minority Over-sampling Technique)

## Modeling

Several machine learning models were trained and evaluated for this project, including:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors Classifier
- Gaussian Naive Bayes Classifier

Each model was trained on the preprocessed data and evaluated based on metrics such as accuracy, log loss, F1 score, and classification reports.

## Results

The results of the models are summarized as follows:

- Logistic Regression achieved an accuracy of 0.867 but had low recall and F1-score for attrition cases.
- Decision Tree Classifier achieved an accuracy of 0.772 but had low recall and F1-score for attrition cases.
- Random Forest Classifier achieved an accuracy of 0.874 but had low recall and F1-score for attrition cases.
- The k-Nearest Neighbors Classifier achieved an accuracy of 0.854 but had a low recall and F1-score for attrition cases.
- Gaussian Naive Bayes achieved an accuracy of 0.772 but had low recall and F1-score for attrition cases.

After applying SMOTE for oversampling, the models were retrained, resulting in improved recall for attrition cases, but the overall performance varied for each model.

## Usage

To use this project:
1. Clone the repository.
2. Install the required dependencies.
3. Run the Jupyter Notebook or Python script to train and evaluate the models.
4. Customize the models or preprocessing steps as needed for your specific dataset.

## Dependencies

- Python 3.x
- Libraries: scikit-learn, pandas, imbalanced-learn (for SMOTE), and other dependencies as specified in the project files.

You can install the required dependencies using `pip` or `conda`.

Example using `pip`:
```bash
pip install scikit-learn pandas imbalanced-learn
