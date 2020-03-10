# Predicting survivors of the Titanic

In this project, I use the Titanic dataset from Kaggle to predicts survivors on the Titanic. I apply two classification models: a logistic regression and a random forest. In the logistic regression file, I fit two models: one with imputated missing values and one without. The performance of both models is very similar, except the imputated model is better at predicting deads than survivors. I suggest this could be more useful in a real setting, for example if another Titanic was departing tomorrow. We do not want to predict someone to be alive and then ratify this prediction (i.e. false positive).


In the random forest file, I start by fitting a decision tree to understand the process. Then, I fit a random forest classifier to the data. The accuracy of both models is very similar.

 
## Which model is better?

Both approaches (logistic regression or random forest) give very similar results. My models are roughly all 80% accurate. The model that is best able to distinguish between survivors and deads is the imputated logistic regression.
 
 
 
## Reproducibility

I use Python (Jupyter notebook) for the whole analysis. To install, <a href="https://jupyter.readthedocs.io/en/latest/install.html">visit</a>.
The data I used is attached. For details on the meaning of each variable, <a href="https://www.kaggle.com/c/titanic/data">visit</a>.

 
## Next steps

There are many more possibilities to explore in this dataset. For example, predicting which groups were more likely to survive (gender, social class). So, this repo is in working progress.
