# Fraud Detection for Financial Transactions
This is a project which detects fraud for finacial transation using machine learning models. Random forest from Machine Learning and Neutral network from Deep learning are used for detecting fraud. It detects the fraud and then perform cross validation for the algorithms to ensure accuracy. It visualize the confusion matrix of both the algorithm and display the outputs.
## Quick Start
Import Required Libraries
```
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```
Import Algorithms
```
from sklearn.ensemble import RandomForestClassifier, AdaBoostClassifier
from sklearn.svm import SVC
```
```
from sklearn.neural_network import MLPClassifier
```
Import metrics
```
from sklearn.metrics import accuracy_score, f1_score, confusion_matrix
```
Display the Output.

