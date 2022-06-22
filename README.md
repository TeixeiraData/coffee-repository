# coffee-repository
## coffee analysis!!!

REMEMBER
When selecting subsets of data, square brackets [] are used.

Inside these brackets, you can use a single column/row label, a list of column/row labels, a slice of labels, a conditional expression or a colon.

Select specific rows and/or columns using loc when using the row and column names

Select specific rows and/or columns using iloc when using the positions in the table

You can assign new values to a selection based on loc/iloc.

REMEMBER
Create a new column by assigning the output to the DataFrame with a new column name in between the [].

Operations are element-wise, no need to loop over rows.

Use rename with a dictionary or function to rename row labels or column names.

REMEMBER
Aggregation statistics can be calculated on entire columns or rows

groupby provides the power of the split-apply-combine pattern

value_counts is a convenient shortcut to count the number of entries in each category of a variable

REMEMBER
Sorting by one or more columns is supported by sort_values

The pivot function is purely restructuring of the data, pivot_table supports aggregations

The reverse of pivot (long to wide format) is melt (wide to long format)

Valid date strings can be converted to datetime objects using to_datetime function or as part of read functions.

Datetime objects in pandas support calculations, logical operations and convenient date-related properties using the dt accessor.

A DatetimeIndex contains these date-related properties and supports convenient slicing.

Resample is a powerful method to change the frequency of a time series.


Uma ideia para se analisar nesse ponto é sobre oque posso melhor epoca de valorizacao, pois tem momentos que apesar do valor ser alto entre abertur e fechamento o volume é baixo de acoes negociadas. 