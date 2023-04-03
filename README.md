
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

![Screenshot 2023-04-01 084140](https://user-images.githubusercontent.com/118708245/229308756-857ed371-e9e8-4186-a12d-62e84384ef46.png)


# DATA DESCRIBE

![Screenshot 2023-04-02 155006](https://user-images.githubusercontent.com/118708245/229347110-5fdfad44-d7f9-4526-9c75-c3e32c283a6f.png)

# DATA NULL VALUES

![Screenshot 2023-04-02 155130](https://user-images.githubusercontent.com/118708245/229347185-ee77091a-2cc3-4ec6-9b44-27fd01cf25c3.png)

# DATA DATA TYPES

![Screenshot 2023-04-02 155246](https://user-images.githubusercontent.com/118708245/229415912-03be46f6-55d8-40f4-b363-83bac6714a21.png)



# DATA VALUE COUNT

![Screenshot 2023-04-02 160146](https://user-images.githubusercontent.com/118708245/229347658-67317a2a-213b-4081-8ccb-3346432cbffd.png)


# BOXPLOT

![Screenshot 2023-04-02 155708](https://user-images.githubusercontent.com/118708245/229347534-5a9752ff-4321-4baa-adf3-323bb5bd7434.png)

# COUNTPLOT

![Screenshot 2023-04-02 161225](https://user-images.githubusercontent.com/118708245/229348225-814e4175-eb86-45f5-8ff9-9e86f90ac28a.png)


# DISTRIBUTION PLOT

![Screenshot 2023-04-03 103433](https://user-images.githubusercontent.com/118708245/229416100-3bff95f6-ed10-4592-a95b-9b0118e94377.png)

# HISTOGRAM PLOT

![Screenshot 2023-04-03 103620](https://user-images.githubusercontent.com/118708245/229416281-3743821c-b702-45a2-9416-82d279b34ac7.png)

# RESULT

Thus we have read the given data and performed the univariate analysis with different types of plots.
