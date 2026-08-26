# Heart Disease Prediction

This is a Machine learning project that predicts whether a patient has heart disease based on clinical health information such as age, cholesterol, blood pressure, maximum heart rate, and other medical features.

## Project Overview

This project explores and compares multiple classification models for heart disease prediction using a dataset containing 1,190 patient records.

The models evaluated include:

* Logistic Regression
* Decision Tree
* Random Forest
* K-Nearest Neighbors (KNN)

The dataset was split into training and testing sets to evaluate model performance.

## Results

| Model                    | Test Accuracy |
| ------------------------ | ------------: |
| Logistic Regression      |        82.77% |
| Decision Tree            |        78.99% |
| Random Forest            |        94.12% |
| KNN                      |        64.29% |
| KNN with Standardization |        83.61% |
| 5-fold CV Random Forest mean |    90.34% |

5-fold cross-validation: Random Forest achieved the highest mean accuracy at 90.34%.

Improved KNN test accuracy from 64.3% to 83.6% through feature standardization and achieved 94.1% test accuracy with Random Forest.

## Data Analysis

The project includes exploratory data analysis and visualization of relationships between patient characteristics and heart disease status.

The dataset contains features including:

* Age
* Sex
* Chest pain type
* Resting blood pressure
* Cholesterol
* Fasting blood sugar
* Resting ECG
* Maximum heart rate
* Exercise-induced angina
* Oldpeak
* ST slope

## Tools and Libraries

* Python
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn
* Altair

## Repository Contents

* `Heart_disease_prediction.ipynb` — complete analysis, model training, evaluation, and visualization
* `README.md` — project overview and results

## Dataset

Heart Disease Dataset from Kaggle.

## Author

Jiaen Qi

University of California, Irvine

B.S. Applied and Computational Mathematics

