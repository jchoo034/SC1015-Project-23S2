# Consumer subscription prediction

## About

This is a Mini-project for SC1015 which focuses on [Consumer Behavior and Shopping Habits Dataset](https://www.kaggle.com/datasets/zeesolver/consumer-behavior-and-shopping-habits-dataset). For detailed walkthrough, please view the source code in order from:

1. [Data Visualisation](https://github.com/jchoo034/SC1015-Project-23S2/blob/main/1.%20Visualisation%20and%20Cleaning.ipynb)
2. [Naive Bayes and Random Forest](https://github.com/jchoo034/SC1015-Project-23S2/blob/main/2.%20Naive%20Bayes%20and%20Random%20Forest.ipynb)
3. [Naive Bayes and Random Forest + Grid Search(Reduced set)](https://github.com/jchoo034/SC1015-Project-23S2/blob/main/3.%20Final%20Model.ipynb)

## Contributors

- @Dlhwai
- @jchoo034
- @yys0511

## Problem Definition

- How can businesses increase the chances of consumers enrolling in their loyalty program?
- What are the factors that affect a consumer decision on enrolling in a loyalty program?

## Models Used

1. Naive Bayes
2. Random Forest
3. Grid Search

## Conclusion

- Initial variables that we selected were proven to have redudancy
- Random forest was used to show the importance of variables we had selected
- Discounts appied and Purchase amount were the best indicators for predicting a user's likelyhood to subscribe
- A higher purchase amount and use of discount would have a higher chance for user to subscribe

## What did we learn from this project?

- Encoding of feature variables using onehotencoder
- Naive Bayes and Random Forest models
- Using Random Forest to get feature importance in modelling proccess
- Use of Grid search to improve model accuracy
- Naive Bayes is hard to implement in real world situations as they assume that all variables are independent which is often not the case

## References

- https://www.kaggle.com/datasets/zeesolver/consumer-behavior-and-shopping-habits-dataset
- https://www.kaggle.com/code/dansbecker/using-categorical-data-with-one-hot-encoding
- https://www.analyticsvidhya.com/blog/2021/11/implementation-of-gaussian-naive-bayes-in-python-sklearn/
- https://scikit-learn.org/stable/auto_examples/ensemble/plot_forest_importances.html
