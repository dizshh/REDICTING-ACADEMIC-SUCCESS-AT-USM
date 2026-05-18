Predicting Academic Success at USM using ML Models 

## Authors

Created by: **Christian Jay M. Lucañas**, **John Kierve T. Gardonia** && **Felix Joseph B. Dinopol** 

## Overview

This project is a multi-model Machine Learning-based predictive system built using **Multiple Linear Regression**, **Gaussian Naive Bayes**, and **Decision Tree Classifier** algorithms.

The architecture predicts a student's continuous academic trajectory (exact numerical grade) and classifies their academic risk (Pass/Fail) based on behavioral-related input features from the dataset.

---

## Machine Learning Algorithm Used

* Multiple Linear Regression (Continuous Prediction) 


* Gaussian Naive Bayes (Probabilistic Thresholds) 


* Decision Tree Classifier (Non-Parametric Node Splitting) 



The model also uses:

* 80/20 Train-Test Split for validation 


* Label Encoding and Threshold Binning for preprocessing 


* Mean Squared Error (MSE), Accuracy, Precision, Recall, and F1-Scores for evaluation 



---

## Dataset Information

Dataset file:

```bash
Student_Performance.csv

```

The dataset contains:

* Student-related behavioral features (Hours Studied, Previous Scores, Extracurricular Activities, Sleep Hours, and Practice Papers) 


* A binary target label indicating academic status:
* 
`0 = Fail (< 60)` 


* 
`1 = Pass (>= 60)` 




* A continuous target label indicating exact Performance Index (ranging from 10 to 100) 



> Disclaimer:
> This dataset is used strictly for educational and research practice purposes only.

---

## Features of the Project

* Data preprocessing using Scikit-learn, Pandas, and NumPy 


* 80/20 Train/Test Data Splitting 


* Multi-algorithm processing for continuous and binary targets 


* Target Threshold Binning for discrete classification 


* Feature Correlation Heatmap visualization 


* Regression Scatter Plot and Target Distribution visualization 


* Decision Tree Logic Map rendering using Gini Impurity 


* Confusion Matrix extraction for model evaluation 



---

## Project Structure

```bash
caps/
│
├── capstone.ipynb
├── Student_Performance.csv
└── README.md

```

---

## Sample Output

### Evaluation Metrics Output

```bash
--- Continuous Model Results (Multiple Linear Regression) ---
Mean Squared Error (MSE) : [Value]
R-squared (R2) Score     : [Value]

--- Classification Results (Decision Tree & Naive Bayes) ---
Model Accuracy           : [Value]
F1-Score                 : [Value]

```

---

## Educational Purpose Notice

This project is intended only for:

* Data Science and Machine Learning practice
* Educational demonstrations
* Academic projects
* Research learning
