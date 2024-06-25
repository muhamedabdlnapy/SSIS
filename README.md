-DB Source:
This is the starting point of the data flow.
The source component is reading data from a database table or view.
It indicates that 14 rows have been read from the source.

-Data Conversion:
This transformation is used to convert data types of columns from the source data.
It's useful when the source data types do not match the data types required by downstream components.
It shows that all 14 rows passed through this transformation.

-Derived Column:
This transformation allows for the creation of new columns or the modification of existing columns using expressions.
It indicates that 14 rows were processed, meaning some columns might have been modified or new columns added.

-Lookup:
This transformation is used to perform a lookup operation by matching input rows with rows in a reference dataset (usually another table or a cached dataset).
The screenshot shows that 14 rows entered the Lookup transformation, but there are two outputs:
The default output (matched rows).
The "Lookup No Match Output" which is showing 2 rows that did not find a match in the reference dataset.
OLE DB Destination:

This is the destination component where the processed data is written to a database.
It indicates that the 2 rows which did not find a match in the Lookup transformation were directed to this destinatio
