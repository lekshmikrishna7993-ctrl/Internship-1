



# From
dictionary



data =
{'Name': ['Alice', 'Bob'], 'Age': [25, 30]}



df =
pd.DataFrame(data)



 



# From list of
lists



lst =
[['Alice', 25], ['Bob', 30]]



df =
pd.DataFrame(lst, columns=['Name', 'Age'])






df.head()      #
First 5 rows



df.tail()      #
Last 5 rows



df.info()      #
Info about DataFrame



df.describe()  # Summary statistics





# Column
selection



df['Name']



df[['Name',
'Age']]



 



# Row
selection by label and position



df.loc[0]



df.iloc[1]






df[df['Age']
> 25]  # Rows where Age > 25





df['Gender'] =
['F', 'M']  # Add new column



df.drop('Age',
axis=1, inplace=True)  # Remove column





df.isnull()



df.dropna()



df.fillna(0)





df.groupby('Gender')['Age'].mean()





# Merge two
DataFrames



pd.merge(df1,
df2, on='key')



 



# Join by
index



df1.join(df2)





# Read CSV



df =
pd.read_csv('data.csv')



 



# Write CSV



df.to_csv('output.csv',
index=False)





df.sort_values('Age')



df['Age'].apply(lambda
x: x + 1)



df['Name'].unique()



df['Age'].value_counts()



















