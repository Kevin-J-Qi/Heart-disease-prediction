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
| Logistic Regression      |        81.93% |
| Decision Tree            |        80.67% |
| Random Forest            |        93.28% |
| KNN                      |        66.81% |
| KNN with Standardization |        82.77% |

Random Forest achieved the highest test accuracy at **93.28%**.

Feature standardization also improved KNN accuracy from **66.81% to 82.77%**, demonstrating the importance of feature scaling for distance-based models.

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

