# Fairness Metrics - Trustworthy AI

## Overview 

Is there a way to measure fairness of our machine learning model? Is our model/database biased? 

*   In this notebook, we explore the german credit database
*   A machine learning model is chosen in order to classify good/bad credit 
*   The **PPV** (positive predictive value) is calculated for both genders in order to see gender bias 
*   ***Aequitas*** is used in order to calculate the other fairness metrics \
https://github.com/dssg/aequitas 

German Credit Dataset - https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data) \
This dataset is commonly used in fairness literature. It contains information about 1000 loan applicants and includes 20 attributes describing each applicant, e.g., credit history, purpose of the loan, loan amount requested, marital status, gender, age, job, and housing status. 
It also contains an additional attribute that describes the classification outcome – whether an applicant has a good or a bad credit score.
