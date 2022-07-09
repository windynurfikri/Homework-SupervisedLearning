# Homework-SupervisedLearning

The purpose of this project is to analyze the potential depositor's behaviour of banking institution and to increase the conversion rate to deposits subscription.

Dataset: Banking Dataset - Marketing Targets, Citation from UCI Machine Learning, 2014
https://www.kaggle.com/datasets/prakharrathi25/banking-dataset-marketing-targets

## Summary
#### Project Background 
Term deposits are one of the major income sources of a bank. These days, selling deposits through telemarketing is still the main of various plans to reach out to the clients.
However, the bank still needs to pay attention to the effectiveness of the direct campaign considering the high cost and the time it takes.
Based on previous campaign data of 45,211 clients, only 11.7% of them actually subscribed to a term deposit. Despite the fact that 36,959 clients were never contacted.
Therefore, determining the right potential depositors needs to be done to save resources. Meanwhile, we also need to review the efficiency and effectiveness of telemarketing as a direct campaign method.

#### Exploratory Analysis & Data Processing
The dataset has 455211 observations and 17 variables with 8 numerical variables, 8 categorical variables and one target variable.
All numerical variables have right-skewed distribution and contain an extreme outliers.
Numerical variables has weak correlation with the target variable, only duration which seems to have a positive correlation with it.

In data processing, we perform several steps, such as check if it has missing or duplicate data, handling outlier, label & one-hot encoding, handling class imbalance.
we didn't do feature transformation for any variable, because it is constrained by zero value and negative value.

#### Meachine Learning
3 Models tested with F1-score as evaluation target to increase True Positive. It goes to Random Forest - Hyperparameter Tuning model with F1-score 91.77%

#### Business Recomendation
- Reach out client at middle of the month or pay day.
- Focus on customer with balance above 1800.
- Classify customers who should be contacted first based on their background (married, has housing loan, has no persoal loan, and no default).
- Train communication skill to telemarketer so can provoke customer’s curiosity for the Deposit product and also maintain the duration of the conversation to average about 9 minutes.


Stage 0 - Stage 4: the progress of the project per each stage.
