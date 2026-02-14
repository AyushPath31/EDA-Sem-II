# Experiment–6 - Conditional Statements in Python  


### <u>Title</u> : Decision Making Using if-else Statement in Python

### <u>Aim</u>: To study and implement decision-making in Python using the if-else statement.  

### <u>Objectives</u>
- To understand conditional execution in Python
- To learn syntax and working of if-else
- To apply decision logic to real-life problems  

---
### Theory  

In Python, decision making is achieved using conditional statements.  
The `if-else` statement allows a program to execute one block of code when a condition is true and another block when it is false.

Python uses indentation instead of braces to define blocks of code. Proper indentation is mandatory.  

Decision making is an essential part of any programming language. In Python, decision making is implemented using conditional statements, which allow the program to take different paths of execution depending on whether a condition is satisfied or not.  

The `if-else` statement is the most basic and widely used conditional control structure in Python.  

It enables the program to evaluate a condition and execute one block of code when the condition is true and another block when the condition is false.

---

<u>Boolean Conditions</u>  

The condition used in an if-else statement must evaluate to a Boolean value, i.e., `True` or `False`.   

Conditions are generally formed using:
-   Relational operators (`<`, `>`, `<=`, `>=`, `==`, `!=`)
-	Logical operators (`and`, `or`, `not`)  

Example conditions:  
-	marks >= 40
-	age >= 18 and citizen == True  

---
<b>Importance of Indentation in Python  </b>

Unlike other programming languages that use braces `{ }` to define code blocks, Python uses indentation.  
All statements inside the if or else block must be indented at the same level.  

Incorrect indentation leads to:  
-	Logical errors
-	IndentationError during execution  

Thus, indentation plays a crucial role in Python’s syntax and readability.

---
Control Flow in `if-else`

The if-else statement controls the flow of execution of a program:  
-	Only one block (if or else) executes at a time
-	Execution is linear after the conditional block completes  

This ensures efficient decision-based execution.

---
Types of Conditions Used  
-	Simple condition: Single comparison
-	Compound condition: Combination of two or more conditions using logical operators  

This allows complex decision-making in real-life scenarios such as eligibility checking, authentication, grading systems, etc.

Flow of Execution:  

Start  
↓  
Condition  
  ↓  
True    → if-block  
False   → else-block  
  ↓  
 End

---
<u>Decision Making Using `if-elif-else` Statement in Python Syntax:</u>  

```python
if condition1:
    statement(s)
elif condition2:
    statement(s)
elif condition3:
    statement(s)
else:
    statement(s)
```
---

Program 1: Grade Calculation  

```python
marks = int(input("Enter marks: "))

if marks >= 90:
    print("Grade A")
elif marks >= 75:
    print("Grade B")
elif marks >= 60:
    print("Grade C")
elif marks >= 40:
    print("Grade D")
else:
    print("Fail")
```

Program 2: Menu-Driven Choice  

```python
choice = int(input("Enter choice (1-Tea, 2-Coffee, 3-Juice): "))

if choice == 1:
    print("Tea selected")
elif choice == 2:
    print("Coffee selected")
elif choice == 3:
    print("Juice selected")
else:
    print("Invalid choice")
```

<u>Decision Making Using Nested if Statement in Python Syntax:</u>  

```python
if condition1:
    if condition2:
        statement(s)
    else:
        statement(s)
else:
    statement(s)
```

Program 1: Voting Eligibility with Citizenship  

```python
age = int(input("Enter age: "))
citizen = input("Are you a citizen (yes/no): ")

if age >= 18:
    if citizen == "yes":
        print("Eligible to vote")
    else:
        print("Not eligible: Not a citizen")
else:
    print("Not eligible: Age below 18")
```

Program 2: Login Authentication  

```python
username = input("Enter username: ")
password = input("Enter password: ")

if username == "admin":
    if password == "1234":
        print("Login successful")
    else:
        print("Incorrect password")
else:
    print("Invalid username")
```


### Conclusion
In this set of experiments, various decision-making statements in Python such as `if`, `if-else`, `if-elif-else`, and nested if were studied and implemented successfully.  

These control structures enable a program to make logical decisions by evaluating conditions and executing appropriate blocks of code.
