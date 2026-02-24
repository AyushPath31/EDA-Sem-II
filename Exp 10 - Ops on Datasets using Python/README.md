# Experiment - 10: Creating and Uploading Dataset using Pandas
---
## Aim  
> To create a dataset in Python and perform basic data inspection operations such as size, shape, info, and describe using Pandas.
---
### Objectives
-	To create a dataset using a dictionary
-	To convert it into a DataFrame
-	To upload/read a dataset from a CSV file
-	To perform basic data analysis using:  
	- shape
	- size
	- info()
	- describe()
	- head() and tail()
---
> Software Requirement
-	Python 3.x
-	Pandas library
-	Jupyter Notebook / Google Colab / Python IDE
--- 
### Theory
A dataset is a collection of related data. In Pandas, datasets are stored in the form of a <u>DataFrame</u>.  

Datasets can be:  
1.	Created manually
2.	Uploaded from external files such as:
	- CSV
	- Excel
	- JSON
	- SQL
	
> Basic inspection functions help to:
-	Understand the structure of the dataset
-	Identify missing values
-	Know data types
-	Get statistical summary
---
**Basic Inspection Functions** 

| Function        | Purpose                    |
|:--------------  |:--------------------------:|
| `df.shape`      |	Number of rows and columns |
| `df.size`       |Total number of elements    |
| `df.info()`     |	Structure of dataset       |
| `df.describe()` |	Statistical summary        |
| `df.head()`	  | First 5 rows               |
| `df.tail()`	  | Last 5 rows                |
| `df.columns`    |	Display column names       |
---

> Programs 

<u>Part A</u> : Creating Dataset

```python 
import pandas as pd

data = {
    "Roll_No": [101, 102, 103, 104, 105],
    "Name": ["Amit", "Neha", "Rohit", "Sneha", "Kiran"],
    "Marks": [85, 90, 78, 88, 76],
    "Department": ["IT", "CS", "IT", "ENTC", "CS"]
}

df = pd.DataFrame(data)

print(df)
```
---

<u>Part B</u> : Basic Dataset Inspection  

```python
print("Shape:", df.shape)
print("Size:", df.size)

print("\nColumn Names:\n", df.columns)

print("\nFirst 5 rows:\n", df.head())
print("\nLast 5 rows:\n", df.tail())

print("\nDataset Info:\n")
df.info()

print("\nStatistical Summary:\n", df.describe())
```
---  

<u>Part C</u> : Saving Dataset

```python
df.to_csv("students.csv", index=False)
```
---  

<u>Part D</u> : Uploading / Reading Dataset

```python
df2 = pd.read_csv("students.csv")

print("\nUploaded Dataset:\n", df2)
```
---
> Output  
-	Dataset created successfully
-	Shape and size displayed
-	Column names shown
-	Dataset structure obtained using `info()`
-	Statistical summary generated
-	CSV file created and uploaded successfully
---
### Conclusion
Thus, the dataset was created and uploaded successfully, and basic inspection operations such as `shape`, `size`, `info`, and `describe()` were performed using Pandas.  

---