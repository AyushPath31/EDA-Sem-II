# Experiment – 5 : Sets and Dictionaries  

### <u>Title</u>: Implementation of Set and Dictionary in Python

### <u>Aim</u>: To study and implement set data structure in Python and perform various set and Dictionary operations.  

### <u>Objectives</u>
- To understand the concept of sets
-	To perform set creation and basic operations
-	To apply mathematical set operations
-	To understand dictionary structure
-	To perform insertion, deletion, and access of data
-	To apply dictionary methods  


### Theory on Sets
A set in Python is an unordered collection of unique elements.  
Sets are defined using curly braces {} or the set() constructor.  

Characteristics of Set:
-   Unordered
-	No duplicate elements
-	Mutable
-	Does not support indexing  

Sets are commonly used in real-life scenarios such as removing duplicates, membership testing, and mathematical operations.

Set Operations:  
-   Union
-   Intersection
-   Difference
-   Symmetric Difference  

---
Program 1: Creating a Set and Displaying Elements
```python
fruits = {"apple", "banana", "cherry"}  
print("Fruits:", fruits)
```
---
Program 2: Removing Duplicate Values  
```python
numbers = {1, 2, 3, 2, 4, 1}
print("Unique numbers:", numbers)
```
---
Program 3: Set Operations  
```python
A = {1, 2, 3, 4}
B = {3, 4, 5, 6}

print("Union:", A | B)
print("Intersection:", A & B)
print("Difference:", A - B)
print("Symmetric Difference:", A ^ B)  
```
---
Program 4: Set Methods  
```python
s = {10, 20, 30}
s.add(40)
s.remove(20)

print("Updated Set:", s)
```
---
Applications of Sets:  
- Removing duplicate records
- Membership testing
- Mathematical computations
________________________________________

### Theory on Dictionary  
A dictionary is an unordered collection of key-value pairs.  
Each key must be unique, while values may be duplicated.  

<u>Syntax:</u>  

```python
dictionary = {key:value}
```
Dictionaries are widely used in real-life applications such as student records, phone books, and configuration data.  


Characteristics of Dictionary:  
- Key-value based
- Mutable
- Keys are unique
- Values can be modified
---
Program 1: Creating and Accessing Dictionary
```python
student = {
    "roll": 101,
    "name": "Amit",
    "branch": "CSE"
}

print("Name:", student["name"])
```
---
Program 2: Adding and Updating Elements
```python
student["year"] = "Second"
student["name"] = "Rahul"

print(student)
```
---
Program 3: Removing Elements
```python
student.pop("branch")
print("After removal:", student)
```
---
Program 4: Dictionary Methods
```python
print("Keys:", student.keys())
print("Values:", student.values())
print("Items:", student.items())
```
---
Program 5: Iterating Through Dictionary
```python

for key, value in student.items():
    print(key, ":", value)
```
---
Applications of Dictionary:  
- Student information systems
- Phone directories
- Database records
- Configuration files
---

### <u>Conclusion</u>
Sets efficiently handle unique data and support mathematical operations, making them useful for data processing tasks.  
Dictionaries provide efficient storage and retrieval of data using keys, making them essential for real-world applications.

