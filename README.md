```
import pandas as pd
from scipy import stats
import numpy as np
import pandas as pd
df=pd.read_csv("/content/bmi.csv")
df
from sklearn.preprocessing import StandardScaler
sc=StandardScaler()
df[['Height','Weight']]=sc.fit_transform(df[['Height','Weight']])
df.head(10)
from sklearn.preprocessing import MinMaxScaler
sc=MinMaxScaler()
df[['Height','Weight']]=sc.fit_transform(df[['Height','Weight']])
df.head(10)
from sklearn.preprocessing import Normalizer
Scaler=Normalizer
df[['Height','Weight']]=sc.fit_transform(df[['Height','Weight']])
df
```
