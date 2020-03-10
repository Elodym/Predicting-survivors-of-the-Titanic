# Predicting survivors of the Titanic

In this project, I use the Titanic dataset from Kaggle to predicts survivors on the Titanic. I apply two classification models: a logistic regression and a random forest. In the logistic regression file, I fit two models: one with imputated missing values and one without. The performance of both models is very similar, except the imputated model is better at predicting deads than survivors. I suggest this could be more useful in a real setting, for example if another Titanic was departing tomorrow. We do not want to predict someone to be alive and then ratify this prediction (false positive).

In the random forest file, I start by fitting a decision tree to understand the process. I then fit a random forest classifier to the data. The accuracy of both models is very similar.

## Which model is better?

Both approaches (logistic regression or random forest) give very similar results. My models are roughly all 80% accurate.

I use Python (Jupyter notebook) for the whole analysis. To install: <a href="https://jupyter.readthedocs.io/en/latest/install.html">visit</a>.
