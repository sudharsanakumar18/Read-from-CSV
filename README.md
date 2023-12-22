# Read-from-CSV

## AIM:
To write a program for reading the csv file content.

## ALGORITHM:

### Step 1:
Load the CSV into a DataFrame

### Step 2:
Print the number of contents to be displayed using df.head().

### Step 3:
The number of row returned is defined in pandas option settings.

### Step 4:
Check your systems maximun column with the pd.options.display.max_columun statement

### Step 5:
Increase the maximum number of rows to display the entire DataFrame.


## PROGRAM:
```python
##Developed by: NAVEEN S
##REGISTER NUMBER: 212222240070
import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Column",len(df.axes[0]))
print("Row",len(df.axes[1]))
```

## OUTPUT:
![pyth exp 6](https://github.com/sudharsanakumar18/Read-from-CSV/assets/138849110/a17bfa4e-fb48-4498-bcfb-548cd6582636)

## RESULT:
Thus the program written to read csv file.
