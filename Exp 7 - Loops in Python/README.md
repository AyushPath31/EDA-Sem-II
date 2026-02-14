# Experiment-7 : Loops in Python
---

## Title: Study of For Loop and While Loop in Python

### Aim: To study and implement the use of for loop and while loop in Python programming.  

### Theory:  
Looping is a control structure that allows a set of statements to be executed repeatedly based on a condition or over a sequence.  

Python provides two main types of loops: the `for` loop and the `while` loop.
1.	`for` Loop  
The `for` loop is used to iterate over a sequence such as a list, tuple, string, or range of numbers.  
It is generally used when the number of iterations is known in advance.

Syntax:  
```python
for variable in sequence:
    statements
```

The loop variable takes each value from the sequence one by one, and the statements inside the loop are executed for each value.  

Program:
```python
for i in range(1, 6):
    print(i)
```
```bash
Output:
1
2
3
4
5
```
2.	`while` Loop  
The `while` loop is used to execute a block of statements repeatedly as long as a specified condition remains true.  
It is generally used when the number of iterations is not known beforehand. 

Syntax:  
```python
while condition:
    statements
```

The condition is checked before every iteration. If the condition becomes false, the loop terminates.  

Program:
```python
i = 1

while i <= 5:
    print(i)
    i += 1
```
```bash
Output:
1
2
3
4
5
```
---
Difference Between <b>For Loop</b> and <b>While Loop</b>  

-	For loop is used when the number of iterations is known.
-	While loop is used when the number of iterations depends on a condition.
-	For loop automatically handles iteration over a sequence.
-	While loop requires manual updating of the loop variable.
---
### Study of while loop with `break`, `continue`, and `pass` statements in Python
---
### Theory:  
The `while` loop executes a block of statements repeatedly as long as the given condition remains true.  
The loop control statements `break`, `continue`, and `pass` can alter its normal execution.  

1.	`break` statement  
The `break` statement terminates the loop immediately when executed.

2.	`continue` statement  
The `continue` statement skips the remaining statements of the current iteration and proceeds to the next iteration.  

3.	`pass` statement  
The `pass` statement is used as a placeholder and does not affect the flow of execution.  

Program:
```python
i = 1

while i <= 10:

    if i == 3:
        pass

    if i == 5:
        i += 1
        continue

    if i == 8:
        break

    print(i)
    i += 1
```
```bash
Output:
1
2
3
4
6
7
```
---
### Study of for loop with `break`, `continue`, and `pass` statements in Python  
---
### Theory:
The `for` loop is used to iterate over a sequence such as a list, string, or range of numbers.  
Python provides control statements that modify the normal execution of loops.
1. `break` statement  
The `break` statement is used to terminate the loop immediately when a specified condition is satisfied. Control transfers to the first statement outside the loop.

2.	`continue` statement  
The `continue` statement skips the remaining statements in the current iteration and moves to the next iteration of the loop.

3.	`pass` statement
The `pass` statement is a null statement. It performs no action and is used as a placeholder where a statement is syntactically required.

Program:
```python
for i in range(1, 11):

    if i == 3:
        pass

    if i == 5:
        continue

    if i == 8:
        break

    print(i)
```
```bash
Output:
1
2
3
4
6
7
```

### Conclusion :
Thus, the <u>for loop</u> and <u>while loop</u> were studied and implemented successfully using Python programs.  

We have also studied `break`, `continue` and `pass` function in `for` and `while` loop in Python.

