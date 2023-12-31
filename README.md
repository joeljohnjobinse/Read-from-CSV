# Read-from-CSV

## AIM:
To write a python progrom to import content from a csv file
## ALGORITHM:
### Step 1:
Import pandas as pd
### Step 2:
Read the CSV file using read_csv
### Step 3:
Use head and tail methods to get required content from the file
### Step 4:
Use len() method to get the number of rows and columns
### Step 5:
Print the output
## PROGRAM:
```
#Program to read the contents of a CSV file
#Developed by: Joel John Jobinse
#Register No: 212223240062
import pandas as pd
df=pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
![py6](https://github.com/joeljohnjobinse/Read-from-CSV/assets/138955488/48fb9b9a-fbce-404c-b44f-2c1c5559929d)

## RESULT:
Thus a Python program is written to read the contents of a CSV file
