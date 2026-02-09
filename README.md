# Experiment-4
AIM

To study and implement Set and Frozenset in Python and perform operations like adding, removing, membership checking, and set operations such as union, intersection, difference, and symmetric difference.

THEORY

A Set in Python is an unordered collection of elements which stores only unique values. Sets are written inside curly brackets { }.
Sets do not allow duplicate elements, so repeated values are automatically removed. Since sets are unordered, they do not support indexing, therefore accessing elements using set[index] gives an error.
Python sets support operations like adding elements using add(), removing elements using remove() and discard(), and checking presence of elements using the in keyword.
Set operations such as union (|), intersection (&), difference (-), and symmetric difference (^) are used to combine and compare sets.
A Frozenset is similar to a set but it is immutable, meaning its elements cannot be modified after creation.

### **ALGORITHM**

#### **Program 1: Cricket and Football Club Students**

1. Start
2. Create a set `cricket` containing names of cricket club students.
3. Create a set `football` containing names of football club students.
4. Find students who are in both clubs using **intersection** operation: `cricket & football`.
5. Display the common students.
6. Find students who are in only one club using **symmetric difference** operation: `cricket ^ football`.
7. Display those students.
8. Stop

---

#### **Program 2: Finding Absent Students**

1. Start
2. Create a set `all_students` containing names of all students.
3. Create a set `present_students` containing names of present students.
4. Find absent students using **difference** operation: `all_students - present_students`.
5. Store the result in `absent_students`.
6. Display the absent students set.
7. Stop


CONCLUSION

Thus, we successfully studied and implemented Sets and Frozensets in Python. We observed that sets store only unique elements, do not support indexing, and allow different operations like adding, removing, and performing union, intersection, difference, and symmetric difference. We also learned that frozenset is an immutable set which cannot be changed after creation.
