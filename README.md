# Project Title :
Machine Learning-Heart-Disease-Prediction-Project

## Project Overview :
This project involves the application of various machine learning models to predict the presence of heart disease in patients based on a dataset collected in 1988. 
The dataset consists of four databases: Cleveland, Hungary, Switzerland, and Long Beach V, with 76 attributes. The goal is to build predictive models and evaluate their performance in terms of accuracy.

## Project Highlights :
  - **Dataset Information:** The dataset includes key attributes such as age, sex, chest pain type, resting blood pressure, serum cholesterol, and more, contributing to a total of 76 features. The target variable indicates the presence of heart disease, with values 0 (no disease) and 1 (disease).

- **Model Selection:** Various machine learning models have been implemented, including Decision Trees, K-Nearest Neighbors (KNN), Gaussian Naive Bayes (NB), Random Forest, AdaBoost, and Support Vector Machines (SVM).

- **Model Evaluation:** Models are evaluated based on their performance using different parameters such as depth, criterion, neighbors, and number of trees. The table below summarizes the scores for each model configuration.

## Model Configuration and Scores:

| MODEL          | DEPTH | CRITERION   | NEIGHBORS | TREES | SCORE     |
|:--------------:|:-----:|:-----------:|:---------:|:----:|:---------:|
| Decision Tree  |   4   |     gini    |     -     |  -   | 0.810344  |
| KNN            |   -   | neighbors-3 |     3     |  -   | 0.775862  |
| Gaussian NB    |   -   |      -      |     -     |  -   | 0.706896  |
| Random Forest  |   3   |   Tree-15   |     -     |  15  | 0.827586  |
| AdaBoost       |   -   | mistakes-6  |     -     |  -   | 0.810344  |
| SVM            |   -   |      -      |     -     |  -   | 0.775862  |

## Best Models:

- **Decision Tree:** Achieved the highest score of 0.810344 with a depth of 4 and using the Gini criterion.
- **KNN:** Scored 0.775862 with 3 neighbors.
- **Gaussian NB:** Achieved a score of 0.706896.
- **Random Forest:** Outperformed with a score of 0.827586 using a depth of 3 and 15 trees.
- **AdaBoost:** Scored 0.810344 with the default parameters.
- **SVM:** Achieved a score of 0.775862.

## Project Preview :
<img src="Images/best model.png">
