# Read-from-CSV


## AIM:
To write a python program for reading the csv file content.

## ALGORITHM:
PC Anaconda - Python 3.7
### Step 1:
Load the CSV into a DataFrame.

### Step 2:

Print the number of contents to be displayed using df.head().


### Step 3:

Print the number of contents to be displayed using df.head().



### Step 4:
Check your system's maximum column with the pd.options.display.max_column statement.
### Step 5:
Increase the maximum number of rows to display the entire DataFrame.

## PROGRAM:
```py
## DEVELOPED BY: NIVETHA.M
## REGISTER NUMBER:212221240034


import pandas as pd
df= pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("Column",len(df.axes[0]))
print("Rows",len(df.axes[1]))

```

## OUTPUT:
![GitHub Logo](.//p1.png)

## RESULT:
Thus the program is written to read the csv file.
