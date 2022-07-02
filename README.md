# Data-Structures-and-Algorithms-in-Python


What are Data Structures in Python?

Data structures in Python allow programmers to organize, store and manage data so that it can be accessed and modified efficiently. Python has four types of built-in data structures, list, tuple, set, and dictionary. Python also has user-defined data structures. Users can create their own data structures in Python and have full control over their functionality.



Built-in Data Structures:

1.List

Lists in Python:

- store data of different data types in a sequential manner.

- defined using square brackets and holds data that is separated by commas.

- Each element of the list has an address, called an index.

- The indexing starts from 0 and goes till the last element. 

- items in python lists can be changed; We can modify, add, and remove elements in a list after it has been created.

Example: 

list1 = [“red”, “blue”, “27”] #creating list

print(list1)


2) Tuple

- Python tuples are like lists except they are immutable.

- Python tuple elements can’t be changed or modified.

- Tuple items are defined inside parentheses, unlike lists that are defined in square brackets. The length of tuples is fixed.


For Example

tup1 = (1, 2, 3, 4, 5); #creating tuple

print(tup1)


3) Dictionary

- Python dictionaries consist of key-value pairs.

- The keys are unique and immutable objects such as strings, 
numbers, or tuples. The values can be of any type. 

-The key identifies an item and the value stores the values of 
those items.

- The value can be accessed by a unique key in the dictionary. 
- Each key is separated from its value by a colon.The items are separated by commas. 

All the key-value pairs are enclosed in curly braces.

dictionary = {“key name”: value}

For Example

dict = {‘Name’: ‘John’, ‘Age’: 24, ‘Salary’: 25000}

print “dict[‘Name’]: “, dict[‘Name’]

print “dict[‘Salary’]: “, dict[‘Salary’]


Output

dict[‘Name’]:  John

dict[‘Salary’]: 25000


4.Set

- The Python sets are an unordered and mutable collection of unique elements.

- Sets are defined in square brackets. 

- Two values cannot be the same in a set.

For Example

set1 = {1, 2, 2, 3, 3, 4, 5, 6, 6} #creating set

print(set1)


Output

{1, 2, 3, 4, 5, 6}
