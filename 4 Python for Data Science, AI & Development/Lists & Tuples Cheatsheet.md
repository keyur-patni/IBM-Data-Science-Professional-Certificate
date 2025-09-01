# Python Lists & Tuples Cheatsheet

## Table of Contents
- [Lists](#lists)  
  - [Creating a List](#creating-a-list)  
  - [Accessing List Elements](#accessing-list-elements)  
- [Tuples](#tuples)  
  - [Creating a Tuple](#creating-a-tuple)  
  - [Accessing Tuple Elements](#accessing-tuple-elements)  

---

## Lists

A **list** is a collection which is ordered and changeable.  
Lists are defined using square brackets `[]`.

### Creating a List
```python
# Empty list
my_list = []

# List with elements
my_list = [1, 2, 3, 4, 5]


Accessing List Elements

numbers = [10, 20, 30, 40]

print(numbers[0])   # 10 (first element)
print(numbers[-1])  # 40 (last element)

Slicing a List

numbers = [1, 2, 3, 4, 5, 6]

print(numbers[1:4])  # [2, 3, 4]
print(numbers[:3])   # [1, 2, 3]
print(numbers[::2])  # [1, 3, 5]

Modifying Lists

fruits = ["apple", "banana", "cherry"]

fruits[1] = "blueberry"   # Replace element
fruits.append("orange")   # Add element at end
fruits.insert(1, "kiwi")  # Insert at index
fruits.remove("apple")    # Remove element

List Operations

list1 = [1, 2, 3]
list2 = [4, 5, 6]

combined = list1 + list2   # Concatenate
repeated = list1 * 2       # Repeat list

Useful List Methods

numbers = [5, 2, 9, 1]

numbers.sort()       # Sort ascending
numbers.reverse()    # Reverse order
len(numbers)         # Length of list
max(numbers)         # Largest element
min(numbers)         # Smallest element
sum(numbers)         # Sum of elements


## Tuples  

A **tuple** is a collection which is ordered and unchangeable.  
Tuples are defined using parentheses `()`.  


Creating a Tuple

# Empty tuple
my_tuple = ()

# Tuple with elements
my_tuple = (1, 2, 3, 4, 5)

Accessing Tuple Elements

coordinates = (10, 20, 30)

print(coordinates[0])   # 10
print(coordinates[-1])  # 30

Tuple Operations

tuple1 = (1, 2, 3)
tuple2 = (4, 5, 6)

combined = tuple1 + tuple2   # Concatenate
repeated = tuple1 * 2        # Repeat tuple

Useful Tuple Methods

numbers = (1, 2, 2, 3, 4)

numbers.count(2)   # 2 (number of times 2 appears)
numbers.index(3)   # 3 (index of first occurrence of 3)


