# Experiment-4
AIM

To study the concept of sets in Python, their properties, operations, and applications, including the use of frozensets.

THEORY

A set in Python is an unordered collection of unique elements. Sets automatically remove duplicate values and do not maintain insertion order. Since sets are unordered, indexing is not allowed, which results in a TypeError when accessed using an index.

Sets can store multiple data types and allow efficient membership testing using the in keyword. Elements can be added using add() and removed using remove() or discard().

Python supports mathematical set operations such as union, intersection, difference, and symmetric difference, which are useful in real-world scenarios like student lists, course selection, and club membership.

A frozenset is an immutable version of a set where elements cannot be modified after creation.

ALGORITHM

1)Create a set with multiple elements.

2)Print the set to observe unordered and unique values.

3)Attempt indexing to verify that sets are not subscriptable.

4)Add and remove elements using set methods.

5)Check membership using the in keyword.

6)Perform union, intersection, difference, and symmetric difference operations.

7)Create and observe a frozenset.

CONCLUSION

Sets in Python store unique, unordered data and do not support indexing. They are efficient for membership testing and set operations. Frozensets provide immutability when data should not be changed. Thus, sets are useful for handling collections where uniqueness and mathematical operations are required.
