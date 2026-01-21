# Operations on List
## In Python, a list is a built-in, ordered, and changeable (mutable) collection data structure used to store multiple items in a single variable. Lists are defined by enclosing their elements within square brackets ([]), with individual items separated by commas.  

### Aim : To learn Python List operations for various tasks   
### Tools Used :  
- Google Colab
- Jupyter Nootebook
- Git
- GitHub
- VSCode

### Thoery  
A list in Python is a built-in data structure used to store multiple values in a single variable. Lists are ordered, mutable, and can store different data types.

**Creating a List**

Lists are created using square brackets [].

```numbers = [1, 2, 3, 4] ```  
```names = ["Alice", "Bob"]```  
```mixed = [1, "Python", 3.5]```


An empty list can also be created:

```my_list = []```

**Accessing Elements**

List elements are accessed using index values. Indexing starts from 0.

```numbers = [10, 20, 30]```  
```print(numbers[0])   # Output: 10```  
```print(numbers[-1])  # Output: 30```

**Traversing a List**

Traversal means accessing each element one by one.

```for item in numbers:```  
```    print(item)```

**Adding Elements**

Elements can be added using append() or insert().

```numbers.append(40)      # Adds at the end```  
```numbers.insert(1, 15)   # Adds at index 1```

**Removing Elements**

Elements can be removed using remove() or pop().

```numbers.remove(20)  # Removes value 20```
```numbers.pop(0)      # Removes element at index 0```

**Updating Elements**

List values can be changed using index assignment.

```numbers[1] = 25```

**Searching in a List**

Membership testing checks whether an element exists in the list.

```if 30 in numbers:```  
```    print("Element found")```

**Sorting a List**

Lists can be sorted in ascending or descending order.

```numbers.sort()```  
```numbers.sort(reverse=True)```  

Example Use of list in a code snippet :  
<img width="400" alt="image" src="https://github.com/user-attachments/assets/8a23de7d-a751-427e-abd4-2300efd88ebf" />


### Conclusion

Python lists are flexible and easy to use. They allow storing, accessing, modifying, and managing multiple values efficiently, making them suitable for beginner-level programming and problem-solving.
