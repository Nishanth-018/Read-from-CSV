# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file

## ALGORITHM:
Step 1:
Import pandas as pd

Step 2:
read the csv file using read_csv method

Step 3:
Use head and tail method to get the required contents from the file

Step 4:
Use len() method to get the number of rows and columns

Step 5:
print the output

## PROGRAM:
~~~
#Developed by:Nishanth J
#Register Number: 230007929
import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
~~~

## OUTPUT:
![WhatsApp Image 2024-01-04 at 18 46 47_9c5a459d](https://github.com/Nishanth-018/Read-from-CSV/assets/149347651/57c7e703-6166-4799-9489-6a3c3cd2f501)


## RESULT:
thus a python program is written to read the contents of a CSV file
