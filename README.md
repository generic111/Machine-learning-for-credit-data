# Machine-learning-for-credit-data

This was a university project that analysed the Credit Risk Rating Data set using the sklearn library and a variety of machine learning techniques. 

This is a dataset about credit ratings given to
a list of publicly traded firms in the US, gathered from 2014 to 2015. The dataset consists of
multiple financial variables of the firms, and their respective rating given to the firms by the
rating agency Standard and Poor’s.
The assignment consists of applying models and model selection methodologies to arrive at
models that predict the rating from some of the other variables measured.
The credit ratings are often given in an ordered scale, from AAA to D, but in our dataset, the
ratings have been grouped and transformed to numbers, integers from 1 (the group of best
rankings) to 4 (the group of worse rankings).
The dataset (`credit_data.csv`) comes from a research paper that explores performance of
‘Artificial Intelligence’ methods for predicting credit ratings:
https://doi.org/10.1016/j.eswa.2020.113925

# Problem description

A primary goal is finding a model that is accurate in predicting the rating of the firms. The
accuracy of the predictions is initially measured in Mean Absolute Error (MAE).
A secondary goal is to get an understanding of which are the main factors that drive the
ratings, according to the model, this would require that at least one of the models uses a
few variables or that you can create a coherent explanation out of one of the models if all
use many variables (you do not need to be a finance expert for this, though if you want to.
Select three models, one from each model family to predict the target variable Rating.

