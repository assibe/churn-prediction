# Churn prediction with pyspark
This project presents a churn predictive model built using using the public data available at www.iainpardoe.com/teaching/dsc433/data/Churn.xls

Specifically, two predictive models, namely Random Forest and Logistic Regression are developed. For each model, grid search has been performed to tune their parameters to optimize the models. Moreover, cross validation is employed to minimize overfitting of the models to the training set. Eventually, the performances of the two models are compared using two performance metrics, namely Area Under ROC, Area Under PR.

The complete code is available in the jupyter notebook file (**churn analytics.ipynb**). 
