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
___ 
Explanation

Function Composition Breakdown
1. string version of the array --> map(str, array)
2. filter out the palindrome --> filter(isPalindrome, string version of the array)
3. remap all values back to integers --> map(int, palindromes)
4. turn the mapped integers iterable back inside a list --> list(palindromicIterables)

How it would looked with multiple defined variables:

array = list(range(1,10000))
str_array = map(str, array)
palindromes = filter(isPalindrome, str_array)
palindromics = map(int, palindromes)

palindromic_numbers = list(palindromes)
___

## Tuples
___
Tuple is used when you require these attributes from a data structure: 
* It must be immutable
* It must allow different datatypes as items
* It must be iterable
* It must be nestable (much like a list within a list)

Tuple is writted as () 
() is an empty tuple
(50,) is a single tuple
(50,60,) is a double tuple??
*tuples are sliceable (indexing avaliable)

#### Packing and Unpacking
Explanation:

* Packing collect multiple variable’s values and assign it to a single variable
* Unpacking help us assign certain values from a tuple to different variables
* This becomes very useful skill when combined with variable arguments for Function Definition and Function Calls

___

## Sets
A set is an unordered collection with no duplicate elements in Python 3
**mathematical way to describe collection of different unique objects.










