# convert-dataset
Convert crop production dataset into following formats

1. Slice the transform dataset in two different dataframe
o df1= data[:50%]
o df2=data[51%:]
2. Find the count of NaN values attribute(feature) wise in both dataframes
3. Use ‘ffill’ to replace NaN values in Df1
4. Use ‘bfill’ to replace NaN values in Df2
5. Find the mean value of every attribute and replace with NaN in df1
6. Find the median value of every attribute and replace with NaN in df2
7. Find correlation in df1, df2 and visualize it
8. Convert df1 into Min Max normalized format.
9. Convert df2 into standardization format.
