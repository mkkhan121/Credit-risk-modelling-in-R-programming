# Credit-risk-modelling-in-R-programming
Credit Risk Scorecard and Probability of Default (PD) Modeling

This repository contains code and documentation for the development of a credit risk scorecard and probability of default (PD) model. The goal of this project is to assess the creditworthiness of borrowers and estimate the likelihood of default using predictive modeling techniques.

#### Data:
We are going to use the loan data, some info about the dataset is it belongs to Lendingclub company which is basically a US based world’s largest peer to peer or P2P company which acts as a broker to match investors with borrowers. So borrowers usually find it easy to borrow from this P2P platform compared to personal loans whether for home renovation, medical supplies, travel and for so many other needs because the loan amount is quick compared to personal loans at a bank etc. So there are mid aged, salaried or self-employed people who are lending on these P2P platforms to earn some attractive returns by taking high risks compared to other financial assets.


#### Introduction:
In this project, we aim to develop a credit risk scorecard and a probability of default (PD) model. The credit risk scorecard helps evaluate the creditworthiness of borrowers based on their characteristics, while the PD model estimates the likelihood of a borrower defaulting on their loan or credit obligations.

#### Components:
This project consists of the following components:
- Theoretical Framework: Understanding the concepts and methodologies related to credit risk assessment and probability of default modeling.
- Data Pre-processing: Preparing the dataset for analysis, including cleaning, transforming, and handling missing values.
- Model Development: Building predictive models using techniques such as logistic regression or other suitable algorithms.
- Model Performance Evaluation: Assessing the performance of the developed models using metrics such as AUC, ROC curve, accuracy, and confusion matrix.
- Model Fitting and Validation: Applying the trained models to a separate test dataset or conducting cross-validation to validate the model's performance.

#### Modeling Process:
The modeling process consists of the following steps:
1. Data Pre-processing: Clean and prepare the dataset for analysis.
2. Variable Selection: Identify relevant predictor variables for the models.
3. Model Development: Train the predictive models using suitable algorithms.
4. Model Evaluation: Assess the performance of the models using evaluation metrics.
5. Model Fitting and Validation: Apply the models to unseen data for validation.


#### Evaluation Metrics:
The evaluation metrics used in this project include:
- Area Under the Curve (AUC): Measures the model's ability to distinguish between default and non-default cases.
- Receiver Operating Characteristic (ROC) Curve: Plots the true positive rate against the false positive rate.
- Accuracy: Calculates the proportion of correctly classified cases.
- Confusion Matrix: Provides a breakdown of the model's predictions in terms of true positives, true negatives, false positives, and false negatives.


#### Some important takeaways from this modelling exercise:
- Accuracy : 0.73
- Sensitivity or Recall : 0.5663
- Specificity : 0.7926
