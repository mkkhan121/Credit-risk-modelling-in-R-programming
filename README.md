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



#### Logistic regression equation:
- Interpretation of our logistic regression equation:
The criteria we chose to discard variables based on p-value, so we set our two-tailed P-value cutoff at 0.01, means we will discard those variables whose P-value exceed this cutoff and it is also called as alpha number so this is very important step as well.
So our Logistic regression equation that we are actually building is as follows:
Logit (p) = a +Bx1 + Cx2 ….
So this is the final equation we are building and is important to interpret:
Logit (p) is the independent variable, a is the coefficient then B is the coefficient and multiplied by x1 which is our variable and so on. The interpretation is as follows: so a one unit increase in x1 which is our variable will result in B times our coefficient increase in the log of odds which is Logit (P), ratio of success of failure in our case is probability of default. So in simple terms, a one unit increase in x1 will result in B times increase in the log of odds ratio of probability of default.
Logit (P) explanation:
Logit (P) = Log(p/1-p)
      So it is the log of p or probability of say y =1 as our default divided by 1-p which is non-default, in other words Log of default by non default. So that is why we call p/1-p as our odds ratio and then we take the Log so we call it Log of odds ratio. So log-odd ratio is simply the logarithm of odds ratio. The reason Logarithm was used is because it will yield the normal distribution while shrinking or reducing extremely large values of odds ratio.
So the equation, Logit (p) = a + Bx1 + Cx2 ….
so from this equation we are going to interpret all the numbers and more essentially the coefficient as well the P-value so based on that, we will accept or reject the Null Hypthesis based on alpha which is the cutoff at 0.01.

Any collaboration or further assistance would be highly appreciated to solidify the models effectiveness.

Thanks.

