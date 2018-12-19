# Credit Card Anomaly Detection

Authors:
- Kevin Wendt
- Dan DeBruler
- Andrew Schuster
- Ravi Thinakkal
- Derek Donahue
- Wesley Merkel

# Dataset

We are using a 182MB dataset from Kaggle.com with over 6 million records and 11 columns including:
- time
- transaction type
- amount
- origin
- old balance
- new balance
- destination
- destination old balance
- destination new balance
- whether or not the transaction is fraudulent
- whether other predefined rules marked the transaction as fraudulent

Dataset can be found here: https://www.kaggle.com/ntnu-testimon/paysim1

# Modeling Strategy
We are attempting two modeling strategies: one supervised, one unsupervised using SageMakers's Random Cut Forest.

It may be possible to identify networks of repeat offenders.

## Supervised - XGBoost/Linear Learner

We will train a model based on XGBoost and one on Linear Learner and evaluate effectiveness of each relative to the other.

Based on the output of that initial training, we will attempt to identify a set of actors more likely to be involved in fraudulent transactions.  As a stretch goal, we will build a(n) additional model(s) including a flag on those actors and evaluate whether that flagging increases the model's effectiveness in identifying anomalous transactions.

## Unsupervised - Random Cut Forest
