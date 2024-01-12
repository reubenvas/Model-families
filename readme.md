
# Statistical Machine Learning Project: Bike Demand Prediction

## Overview
This project involves the development of various machine learning models to predict the need for increased bike stock in a public bike-sharing system in Washington D.C. The prediction is based on several factors, including weather, time of day, seasonality, and more.

## Team Members
- Reuben Vas
- Vilmer Blystad
- Zakarias Brouneus
- Rustam Ismailov

## Data Source
The dataset includes 16 features, such as temperature, humidity, time of day, holiday status, and bike demand status (increase_stock).

## Objectives
- To develop machine learning models capable of predicting the demand for bikes.
- To compare the performance of different model families, namely logistic regression, discriminant analysis, k-nearest neighbors, and tree-based methods.

## Methodology
1. **Data Preprocessing:** Cleaning, transforming, and preparing the data for analysis.
2. **Feature Engineering:** Creating new features like 'is morning,' 'is afternoon,' 'is night,' and 'is summer' to enhance model performance.
3. **Model Development:** Implementing various models including logistic regression, QDA, k-NN, and tree-based methods.
4. **Model Evaluation:** Assessing models based on accuracy, precision, recall, F1-score, and ROC curve.

## Models Developed
- Logistic Regression
- Quadratic Discriminant Analysis (QDA)
- k-Nearest Neighbors (k-NN)
- Decision Trees and Random Forests

## Results
A comparative analysis of the models showed that the decision tree was the best performer, achieving a high F1-score and balancing precision and recall effectively, especially for the minority class in the dataset.

## Conclusion
The decision tree was chosen as the optimal model for this problem, given its interpretability, efficiency in handling different types of features, and ability to model non-linear relationships.

## Installation and Usage
[Include specific instructions on how to set up the environment, install dependencies, and run the models in the Jupyter Notebook]

## Dependencies
[List of libraries and tools required to run the notebook]

## Acknowledgments
- Course instructors and teaching assistants
- Dataset providers

