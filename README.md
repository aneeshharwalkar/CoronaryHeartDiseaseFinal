# CoronaryHeartDiseaseFinal
## Project Overview

This project aims to extract valuable healthcare insights and predict the risk of Coronary Heart Disease (CHD) using machine learning models. The dataset used is from the Framingham Heart Study, consisting of 4,240 records with various attributes such as age, gender, smoking status, and blood pressure. Two models, Logistic Regression and a Multi-Layer Perceptron (MLP) classifier, were implemented to predict CHD risk based on the available features.

## Dataset

**Source:** Framingham Heart Study (Kaggle) - https://www.kaggle.com/datasets/aasheesh200/framingham-heart-study-dataset/

**Attributes:** 15 variables including age, gender, smoking status, blood pressure, cholesterol levels, and diabetes status.

**Data Preprocessing:**

- Removed the education column.
- Split the dataset by gender for analysis.
- Created training and testing dataframes for model evaluation.

## Models

**Logistic Regression:**

- Accuracy: 87.48%

-   Precision: 41.67%

-   F1-Score: 9.62%

-   Performed well in terms of accuracy, with age, prevalent stroke, and hypertension being key predictors.

**MLP Classifier:**

- Accuracy: 84.75%

- Used all features for training, with a slightly lower accuracy compared to Logistic Regression.

## Key Findings
Both models provide useful insights into CHD risk.
Logistic Regression outperforms the MLP classifier in this dataset based on accuracy alone.
The most important features include age, history of stroke, hypertension, and systolic blood pressure.

## Conclusion

This project helps identify high-risk individuals and suggests that healthcare professionals can use such models to enhance preventive care for CHD.

## Contributors

- Jackson Holmes
- Josh Hee
- Sean Fu
- Aneesh Harwalkar
