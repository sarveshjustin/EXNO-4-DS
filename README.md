```
import pandas as pd
from scipy import stats
import numpy as np
import pandas as pd
df=pd.read_csv("bmi.csv")
df
from sklearn.preprocessing import StandardScaler
df[['Height','Weight']]=StandardScaler().fit_transform(df[['Height','Weight']])
df.head(10)
from sklearn.preprocessing import MinMaxScaler
df[['Height','Weight']]=MinMaxScaler().fit_transform(df[['Height','Weight']])
df.head(10)
from sklearn.preprocessing import Normalizer
df[['Height','Weight']]=Normalizer().fit_transform(df[['Height','Weight']])
df
```
