# CodeAlpha_Disease_Prediction
# Disease Prediction from Medical Data

## Overview
This repository contains my solution for the Disease Prediction task as part of the CodeAlpha Machine Learning Internship. The objective of this project is to predict the likelihood of a patient having diabetes using structured medical data and advanced ensemble classification techniques.

## Dataset
The model is trained on the **CDC Diabetes Health Indicators Dataset** (fetched via OpenML). It is a massive, real-world dataset containing over 253,000 patient records, with features including BMI, age, general health status, and various medical indicators. The target variable is binary (0 = Healthy, 1 = Diabetic/Pre-diabetic).

## Models & Architecture
To handle the scale of this dataset efficiently, I utilized two powerful tree-based algorithms:
* **XGBoost Classifier:** Optimized with the `hist` tree method for high-speed training on massive datasets.
* **Random Forest Classifier:** Configured for parallel processing across multiple CPU cores to efficiently handle a quarter-million rows.

## Evaluation
The models were evaluated using Accuracy, Precision, Recall, and Confusion Matrices to ensure a robust understanding of false positives and false negatives in a medical context.

## Technologies Used
* Python
* Scikit-Learn
* XGBoost
* Pandas & NumPy
* Seaborn & Matplotlib

## Author
**Ammar Ahmad Khan**
Machine Learning Intern at CodeAlpha
