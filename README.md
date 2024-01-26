# DATAFRAME_1
import pandas as pd
#DataFrame Creation
df = pd.DataFrame(data=np.arange(101,126).reshape(5,5),
index=['A','B','C','D','E'],
columns=['U','V','W','X','Y'])
print("Data frame is")
print(df)
print("Column wise accessing")
print(df['W']['A'])
print(df['W'])
print(df[['W','X','U']])
print("Row wise accsessing")
print(df.loc['A']['X'])
print(df.loc['B'])
print(df.loc[['B','A']])
print(df.iloc[2]['X'])
print(df.iloc[1])
print(df.iloc[2:4])
