## Matrices and list comprehension
matrix is a representations of numbers, symbols, or expressions in a 2-Dimensional Array.
 we can start to create a data structure that has values in rows and columns, much like a table, by utilizing a list within a list.
All rows must have the same number of values.
All columns must have the same number of values.
All items in the 2D List must have the same data types.
Since indexing always starts at 0 ... row 1 is technically located at matrix_A[0]
List Comprehension is a concise method to create list in Python 3.
List comprehension consists of:
A Square Bracket containing an expression that describes the list
One or more For clause to explain its members.
Then a zero or more if clauses depending on the complexity of the list.
## Map and filter
The idea of a map function is to apply a function to an iterable data.
written as:ap(function_name, sequence)

-- function_name: any function (built-in or selfmade) that returns a desired value of choice
-- sequence: any iterable data type.
map function is that it doesn’t return a specific data type, but rather, an python iterable data. Therefore, after we apply the map function, we just execute a list function on it.
The idea of the filter function is to filter out items from a data set that meets a certain condition.
written as: Formatting:

filter(bool_returning_function, sequence).
## Tuples
Tuples are declared with parenthesis.
() is an empty tuple
(50,) is a singleton tuple; the comma is required
Tuples are sliceable; therefore, indexable using square brackets
Tuples are Iterable, Indexable, and Sliceable
For more methods and functions return to Slides.
## Sets
A set is an unordered collection with no duplicate elements in Python.
Set is a mathematical way to describe collection of different unique objects.
Membership is one of the key operations with set because:
A set has no duplicates
A set’s membership operation is one of the fastest operations compared to strings, lists, or tuples this will be covered more when we look at the concept of: complexity
By using membership operator, we can be certain a target exists or does not exist in our data.
Same theory as mathemathical set.
Due to its unordered nature of a set, there is no concept of indexing or slicing with a set.
Set is iterable.
Sets are mutable.
Same operator logic as mathemathics.
A is proper subset of B if all members of A is found in B, but A cannot be exactly the same as B.
Two set are consided disjointed when two sets share no common value.
 sets support comprehension.
 Sets aren’t sliceable nor indexable.
Sets cannot have sets inside them.
Sets do not have order; nor order of insertion.
Sets cannot guarantee that their values will be in order.
Sets do not record a value’s position.
## Dictionary
Dictionary (Associative Array, map, symbol table) is a data type that stores a collection of (key, value) pairs, such that each possible key appears at most once in the collection.
Common Operations are:
Adding a pair
Removing a pair
Modify an existing pair
Lookup of a value associated with a particular key.
Dictionaries also use {} like sets; however, their individual item format is very different.
Each item in a dictionary is called a key.
Key's are immutable and unique.
Value of a key can be anything.
We can delete a key hence deleting the value connected to the key
We can empty out the entire dictionary
We can delete the dictionary.
We can use the in and not in operators in a dictionary.
If A and B are dictionary's some common methods are:
A.keys() –> Returns a sequence of keys/addresses in A
A.values() –> Returns a sequence of item values in A
A.items() –> Returns a sequence of key,item pairs in A
A.get(address) –> Returns the item value at address
A.update(B) –> Extends A with the dictionary of key,value pairs of B
We can turn other data types to dictionaries by using Dict().
dictionaries support comprehension.






