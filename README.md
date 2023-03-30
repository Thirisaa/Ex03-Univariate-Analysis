# Ex03-Univariate-Analysis

## AIM

To perform univariate analysis on the given dataset

## ALGORITHM

# Step 1

Read the data

# Step 2

Perform univariate analysis on numerical data

# Step 3

Do both Stastical and graphical methods

# Step 4

Print the output

## CODE

import pandas as pd

df=pd.read_csv('/content/SuperStore.csv')

df.head()

df.info()

df.describe()

df.dtypes

df['Postal Code'].value_counts

sns.boxplot(x="Postal Code",data=df)

sns.countplot(x="Postal Code",data=df)

sns.displot(x="Postal Code",data=df)

sns.histplot(x="Postal Code",data=df)

df['Sales'].value_counts

sns.boxplot(x="Sales",data=df)

sns.countplot(x="Sales",data=df)

sns.displot(x="Sales",data=df)

sns.histplot(x="Sales",data=df)

## OUTPUT

![op1](https://user-images.githubusercontent.com/112301582/228903843-e484735a-30a5-49b8-8bc7-d776d8380e58.png)
![op2](https://user-images.githubusercontent.com/112301582/228903850-a699daea-6ec2-4db1-937d-a0dcc9a68b89.png)
![op3](https://user-images.githubusercontent.com/112301582/228903866-a7ae9465-5727-4b3e-abec-30f7c2067cd0.png)
![op4](https://user-images.githubusercontent.com/112301582/228903880-019d99ff-19ed-4dde-86e0-be68db008f4f.png)
![op5](https://user-images.githubusercontent.com/112301582/228903894-a1f1ef34-ecd2-4277-b631-501dc86d08f8.png)
![op6](https://user-images.githubusercontent.com/112301582/228903903-c1fa569d-9f8e-4ce4-8433-2599947ddf68.png)
![op7](https://user-images.githubusercontent.com/112301582/228903924-7d42d937-351e-4530-bf87-e464f9204d0a.png)
![op8](https://user-images.githubusercontent.com/112301582/228903938-088509a7-a774-4943-9a0b-6b80b4496878.png)
![op9](https://user-images.githubusercontent.com/112301582/228903951-57231486-76a8-4b12-92bd-e7e000d8c43f.png)
![op10](https://user-images.githubusercontent.com/112301582/228903975-39e3bad3-0d17-44f7-8deb-48b60714b2b6.png)
![op11](https://user-images.githubusercontent.com/112301582/228904003-d134d181-5617-4071-b37c-f0f6d72cf5a3.png)
![op12](https://user-images.githubusercontent.com/112301582/228904019-205c9010-80f6-4a2f-adc5-e80e44c8462b.png)
![op13](https://user-images.githubusercontent.com/112301582/228904621-646c8a9a-3f95-4806-91c8-641fd9177448.png)
![op14](https://user-images.githubusercontent.com/112301582/228904465-ef4cfc6c-42ae-4024-8e06-e28a86fae88b.png)


## RESULT

Thus the univariate analysis was performed on the given dataset
