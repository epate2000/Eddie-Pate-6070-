# Eddie-Pate-6070- CA-02

The goal of CA-02 was to train a model that could determine whether an email could be considered spam or not. The data files train-mails and test-mails which were provided were used in the Gaussian Naive Bayes classification.

The preliminary step was to import a few different packages. They are as follows.

1.import os
2.import numpy as np
3.from collections import Counter
4.sklearn.naive_bayes import GaussianNB
5.sklearn.metrics import accuracy_score

After importing the packages, we needed to clean the data, create dictionaries, a function that would count word frequency, and then run an analysis to test if the classifier worked.
