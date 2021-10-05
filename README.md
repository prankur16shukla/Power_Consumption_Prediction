# Power_Consumption_Prediction
In this project we will apply Recurrent Neural Network (LSTM) which is best suited for time-series and sequential problem. This approach is the best if we have large data. 
The data that we will be using for this project is taken from http://archive.ics.uci.edu/ml/datasets/Individual+household+electric+power+consumption, we will be creating a LSTM
model, train it on data and make predictions to check its performance.

# Important Libraries used
-import warnings
 warnings.filterwarnings('ignore')

-import numpy as np
-import pandas as pd
-import seaborn as sns
-import matplotlib.pyplot as plt
 %matplotlib inline

-from sklearn.preprocessing import MinMaxScaler
-from sklearn.model_selection import train_test_split
-from sklearn.metrics import mean_squared_error

-from tensorflow.keras.models import Sequential
-from tensorflow.keras.layers import LSTM
-from tensorflow.keras.layers import Dense
-from tensorflow.keras.layers import Flatten
-from tensorflow.keras.layers import Dropout
