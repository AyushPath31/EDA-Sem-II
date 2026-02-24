# Experiment - 9: Study of Pandas Library in Python
---
## Aim  
To study the <u>Pandas library</u> and perform basic operations on Series and DataFrame.
---
## Objectives
-	To understand the features of Pandas
-	To create Series and DataFrame
-	To perform data selection and filtering
-	To handle missing values
-	To read and write data using Pandas
---
Software Requirement  
-	Python 3.x
-	Pandas Library
-	Jupyter Notebook / Google Colab / Python IDE
---
### Theory
<b>Pandas</b> is an open-source Python library used for data manipulation and data analysis.   
It provides two main data structures:
1. Series  
A one-dimensional labeled array capable of holding data of any type.

2. DataFrame  
A two-dimensional labeled data structure consisting of rows and columns.

Pandas is widely used in:
-	Data cleaning
-	Data transformation
-	Statistical analysis
-	Exploratory Data Analysis
It is built on NumPy and provides fast and efficient data handling.  
---

<u>Important Functions  </u>

- head()	: Displays first 5 rows
- tail()	: Displays last 5 rows
- info()	: Shows dataset structure
- describe() :	Statistical summary
- loc :	Label-based selection
- iloc: Position-based selection
- isnull()	: Detect missing values
- dropna()	: Remove missing values
- fillna() :	Fill missing values
---
Program  
```import pandas as pd```

1. Creating Series
```python
s = pd.Series([10, 20, 30, 40])
print("Series:\n", s)
```

2. Creating DataFrame
```python
data = {
    "Name": ["A", "B", "C"],
    "Marks": [85, 90, 78]
}

df = pd.DataFrame(data)

print("\nDataFrame:\n", df)
```

3. Display first rows
```python
print("\nFirst 5 rows:\n", df.head())
```

4. Statistical summary
```python
print("\nDescription:\n", df.describe())
```

5. Selecting column
```python
print("\nMarks Column:\n", df["Marks"])
```
---
Output  
-	Series is created successfully
-	DataFrame is displayed
-	First five rows are shown
-	Statistical summary of numerical data is displayed
-	Column selection is performed
---
### Conclusion
Thus, the basic operations of the Pandas library such as creation of Series and DataFrame, data viewing, and data selection were successfully performed.

