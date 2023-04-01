![Screenshot 2023-04-01 083744](https://user-images.githubusercontent.com/118708245/229262966-7a5d0b48-f547-4723-abc3-12d6b4ce5a55.png)
# Ex03-Univariate-Analysis
# Aim:

To read the given data and perform the univariate analysis with different types of plots.

# Explanation:
Univariate analysis is basically the simplest form to analyze data. Uni means one and this means that the data has only one kind of variable. The major reason for univariate analysis is to use the data to describe. The analysis will take data, summarise it, and then find some pattern in the data.

# Algorithm:
# Step1:
Read the given data.

# Step2:
Get the information about the data.

# Step3:
Remove the null values from the data.

# Step4:
Mention the datatypes from the data.

# Step5:
Count the values from the data.

# Step6:
Do plots like boxplots,countplot,distribution plot,histogram plot.

# Program:
```
DEVELOPED BY :JEEVITHA E

REG NO : 212222230054

import pandas as pd
import numpy as np
import seaborn as sns

df=pd.read_csv('superstore.csv')
df

df.head()
df.info()
df.describe()
df.isnull().sum()

df.dtypes

df['Postal Code'].value_counts()

sns.boxplot(x='Postal Code', data=df)
sns.countplot(x='Postal Code',data=df)
sns.distplot(df["Postal Code"])
sns.histplot(x='Postal Code',data=df)
```
# OUTPUT
# DATA

![Screenshot 2023-03-31 204847](https://user-images.githubusercontent.com/118708245/229262517-bab65326-930d-4375-92c3-e84271000da7.png)

# DATA HEAD

![Screenshot 2023-04-01 083744](https://user-images.githubusercontent.com/118708245/229262977-aac51dc5-5ca8-45c2-9c1a-97ecb5812291.png)

# DATA INFORMATION


# DATA DESCRIBE


