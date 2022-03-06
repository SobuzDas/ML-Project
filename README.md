# ML-Project
Neural Network Dataset
# Colab dataset Entry
from google.colab import drive
drive.mount('/content/drive')

import numpy as np
import pandas as pd

dataset = pd.read_csv('/content/drive/MyDrive/Colab Dataset-1/Social_Network_Ads.csv - Social_Network_Ads.csv.csv')
x = dataset.iloc[:, [1,2,3]].values
y = dataset.iloc[:, -1].values
