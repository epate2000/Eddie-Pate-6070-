BSAN 6070 CA-04: Ensemble Models

For this assignment, the task was to use a combination of Python's Sklearn machine learning library along with XGBoost to run and compare various ensemble models. The goal was to utilize bagging methods such as the RandomForestClassifier and boosting methods which include the AdaBoost, the GradientBoosting, and the XGBoost algorithms to train and test different models. 

Refer to the below link to access the data used for the assignment

https://github.com/ArinB/MSBA-CA-Data/blob/main/CA03/census_data.csv?raw=true

Import the below packages to perform the methods used in the assignment

import matplotlib.pyplot as plt
import pandas as pd
import numpy as np
from sklearn import tree
from sklearn.datasets import load_iris
from sklearn.tree import DecisionTreeClassifier
import pydotplus
from io import StringIO
from sklearn import metrics
from sklearn.metrics import accuracy_score
from sklearn.metrics import roc_curve
from sklearn.metrics import roc_auc_score
from pandas.core.common import random_state
from sklearn.ensemble import RandomForestClassifier
from sklearn.ensemble import AdaBoostClassifier
from sklearn.ensemble import GradientBoostingClassifier
import xgboost as xgb
from xgboost import XGBClassifier
import re
