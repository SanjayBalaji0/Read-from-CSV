# Read-from-CSV

## AIM:

## ALGORITHM:
### Step 1:
Import pandas as pd.
### Step 2:
Read the CSV file.
### Step 3:
Use head and tail method to get the required contents.
### Step 4:
use len() functtion to count rows and columns.
### Step 5:
Print the result.
## PROGRAM:
```
#Developed by: S.Sanjay Balaji
#Register No: 23005804
#To write a python program for reading content from
import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
![image](https://github.com/SanjayBalaji0/Read-from-CSV/assets/145533553/40a666c6-bdcf-4e40-9a9c-8ab849aebc8f)

## RESULT:
