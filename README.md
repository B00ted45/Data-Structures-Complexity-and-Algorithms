# Data-Structures-Complexity-and-Algorithms
notes on data structures

## Matrices and list comprehension


**matrixs are a list within a list

##### rules
- All rows must have the same number of values
- All columns must have the same number of values
- All items in the 2D List must have the same data types
- Since indexing always starts at 0 ... row 1 is technically located at matrix_A[0]


#### List comprehenstion rules
* A Square Bracket containing an expression that describes the list
* One or more For clause to explain its members
* Then a zero or more if clauses depending on the complexity of the list

___


## Map and filter


#### MAP
The idea of a map function is to apply a function to an iterable data.

##### Formatting:

map(function_name, sequence)

- function_name: any function (built-in or selfmade) that returns a desired value of choice
- sequence: any iterable data type

#### FILTER
The idea of the filter function is to filter out items from a data set that meets a certain condition.

Formatting:

filter(bool_returning_function, sequence)

- function: The function name we provide for filter() must be return a boolean value ... should also be able handle the items inside the sequence as its arguments
- sequence: any iterable data type


