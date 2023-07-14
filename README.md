# Model-Selection
In this Jupyter Notebook we will compare 3 different models (and select one) on a modified version of the ["forest fires"](https://archive.ics.uci.edu/ml/datasets/Forest+Fires) dataset.
Specifically, given some input features (temperature, relative humidity, etc.) and an output y (`area`) we wish to build models, select a particular model, and make predictions on unseen data.
We also want to bound our prediction with a 95% confidence interval (CI); for this confidence interval we will use the Central Limit Theorem (CLT).
