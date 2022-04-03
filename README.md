Our work as a risk management associate at Alphabet Soup, a venture capital firm. Alphabet Soup’s business team receives many funding applications from startups every day. This team has asked us to help them create a model that predicts whether applicants will be successful if funded by Alphabet Soup.

The business team has given us a CSV file containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. The CSV file contains a variety of information about each business, including whether or not it ultimately became successful. With our knowledge of machine learning and neural networks, we going to try to decide to use the features in the provided dataset to create a binary classifier model that will predict whether an applicant will become a successful business.
To predict whether Alphabet Soup funding applicants will be successful, we will create a binary classification model using a deep neural network.
This work consists of three technical deliverables. You will do the following:
1.Preprocess data for a neural network model.
2.Use the model-fit-predict pattern to compile and evaluate a binary classification model.
3.Optimize the model.

##Technologies : This project leverages Anaconda and Jupyterlab with Python 3.7:

We need also to import the following libraries and dependencies :
```
import pandas as pd
from pathlib import Path
import tensorflow as tf
from tensorflow.keras.layers import Dense
from tensorflow.keras.models import Sequential
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler,OneHotEncoder
```
##Contributor:
Amine Baite
