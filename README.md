# DecodeLabs_DS_Project2_Fraud_Detection_Pipeline

## Project Overview

This project focuses on building a Fraud Detection Pipeline using supervised machine learning techniques. The objective is to identify fraudulent transactions in a highly imbalanced dataset and evaluate model performance using appropriate metrics.

## Objectives

* Detect fraudulent transactions using classification algorithms.
* Handle class imbalance using SMOTE (Synthetic Minority Over-sampling Technique).
* Train and compare multiple machine learning models.
* Perform hyperparameter tuning to improve model performance.
* Evaluate models using Precision, Recall, and ROC-AUC metrics.

## Dataset

The dataset contains transaction-related information along with a target variable:

* **is_fraud** → Target variable

  * 0 = Legitimate Transaction
  * 1 = Fraudulent Transaction

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Imbalanced-Learn (SMOTE)
* Google Colab

## Project Workflow

### 1. Data Loading

* Loaded the fraud detection dataset.
* Inspected dataset structure and features.

### 2. Data Preprocessing

* Handled missing values.
* Encoded categorical variables.
* Scaled numerical features using StandardScaler.

### 3. Handling Imbalanced Data

* Applied SMOTE to balance minority and majority classes.

### 4. Model Training

#### Logistic Regression

* Trained Logistic Regression classifier.
* Evaluated model performance.

#### Random Forest

* Trained Random Forest classifier.
* Compared performance with Logistic Regression.

### 5. Hyperparameter Tuning

* Used GridSearchCV to optimize Random Forest parameters.
* Selected the best-performing model.

### 6. Model Evaluation

Models were evaluated using:

* Precision
* Recall
* ROC-AUC Score

Accuracy was intentionally avoided because it can be misleading for highly imbalanced datasets.

## Results

| Model               | Precision                  | Recall                     | ROC-AUC                    |
| ------------------- | -------------------------- | -------------------------- | -------------------------- |
| Logistic Regression | Generated during execution | Generated during execution | Generated during execution |
| Random Forest       | Generated during execution | Generated during execution | Generated during execution |

## Key Learnings

* Handling imbalanced datasets using SMOTE.
* Building classification models using Scikit-Learn.
* Hyperparameter tuning with GridSearchCV.
* Evaluating fraud detection models using Precision, Recall, and ROC-AUC.

## Conclusion

A complete fraud detection pipeline was successfully developed. SMOTE improved class balance, while Logistic Regression and Random Forest models were trained and evaluated. Hyperparameter tuning further enhanced model performance, making the solution suitable for fraud detection tasks.

## Author

Smitha 

## Internship

DecodeLabs Data Science Internship – Week 2 Project
