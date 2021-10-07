# coba_1
Kelas Data Sains

#Mengimpor library
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn import datasets

import pandas as pd
import io

from google.colab import files
uploaded = files.upload()

df = pd.read_csv('food_delivery_datasets.csv')
print(df)

df = pd.read_csv('food_delivery_datasets.csv')
X = df.iloc[1::,[5]].values
print(X)

data = X
mean = sum(data) / len(data) 
  
print("mean dari data tersebut adalah " + str(mean)) 
mean dari data tersebut adalah [78090.69767442]

Rata rata harga makanan di restoran itu adalah 78090.69767442 atau dapat dibulatkan menjadi 78.100
