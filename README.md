We need to select individual data or slices of a DataFrame, The solution is Use loc or iloc to select one or more rows or values, We can use : to define a slice of rows we want, such as selecting the second, third, and fourth rows
We can even use it to get all rows up to a point, such as all rows up to and including the fourth row, DataFrames do not need to be numerically indexed. We can set the index of a DataFrame to any value
where the value is unique to each row. For example, we can set the index to be passenger names and then select rows using a name All rows in a pandas DataFrame have a unique index value. By default, this index is an integer
indicating the row position in the DataFrame; however, it does not have to be. DataFrame indexes can
be set to be unique alphanumeric strings or customer numbers. To select individual rows and slices of
rows, pandas provides two methods:
loc is useful when the index of the DataFrame is a label (e.g., a string).
iloc works by looking for the position in the DataFrame. For example, iloc[0] will return the first
row regardless of whether the index is an integer or a label.
It is useful to be comfortable with both loc and iloc since they will come up a lot during data cleaning.
