# Experiment - 8: Introduction to NumPy  
---

## Aim
To study the <u>NumPy library</u> and perform basic operations on NumPy arrays.  
---
## Objectives
-	To create NumPy arrays
-	To perform mathematical operations on arrays
-	To understand array attributes and indexing
-	To use built-in NumPy functions
---
### Software Requirements  
-	Python
-	NumPy library
-	Jupyter Notebook / Google Colab / Python IDE
---
### Theory
<b>NumPy (Numerical Python)</b> is a library used for numerical computations.  
It provides a powerful N-dimensional array object and functions for performing mathematical operations efficiently.  

Advantages of NumPy:
-	Faster than Python lists
-	Requires less memory
-	Supports vectorized operations
-	Provides mathematical and statistical functions  

---
<u>Procedure</u>
1. Import NumPy  
```python
import numpy as np
```

2. Create NumPy Array
```python  
a = np.array([10, 20, 30, 40])
print(a)
```
3. Create Array with Zeros, Ones and Range
```python  
print(np.zeros(4))
print(np.ones(4))
print(np.arange(1, 10, 2))
```

4. Check Array Attributes  
```python
a = np.array([[1, 2, 3], [4, 5, 6]])

print(a.ndim)    # number of dimensions
print(a.shape)   # size of array
print(a.size)    # total number of elements
print(a.dtype)   # data type
```
5. Reshape the Array  
```python
a = np.array([1, 2, 3, 4, 5, 6])
print(a.reshape(2, 3))
```
6. Mathematical Operations
```python
a = np.array([10, 20, 30])
b = np.array([1, 2, 3])

print(a + b)
print(a - b)
print(a * b)
print(a / b)
```
7. Statistical Operations  
```python
a = np.array([10, 20, 30, 40])

print(np.mean(a))
print(np.sum(a))
print(np.max(a))
print(np.min(a))
print(np.std(a))
```
8. Indexing and Slicing  
```python
a = np.array([10, 20, 30, 40, 50])

print(a[1])
print(a[1:4])
```
Output  
-	NumPy arrays were created
-	Mathematical operations performed successfully
-	Statistical values calculated
-	Array attributes displayed
---
### Conclusion
Basic operations on NumPy arrays were successfully performed.

