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
We are attempting two modeling strategies: one supervised using XGBoost, one unsuperfised using SageMakers's Random Cut Forest

## Supervised - XGBoost

## Unsupervised - Random Cut Forest
