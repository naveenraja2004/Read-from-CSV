# Read-from-CSV

## AIM:
To write a program for reading the csv file content

## ALGORITHM:
Load the CSV into a DataFrame Step 2:

Print the number of contents to be displayed using df.head(). Step 3:

The number of row returned is defined in pandas option settings. Step 4:

Check your systems maximun column with the pd.options.display.max_columun statement. Step 5:

Increase the maximum number of rows to display the entire DataFrame

## PROGRAM:
```
#Devloped By:NAVEENRAJA  N R
#Ref no: 212222230093



import pandas as pd
df = pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("column", len(df.axes[0]))
print("rows", len(df.axes[1]))
```
## OUTPUT:
![image](https://github.com/naveenraja2004/Read-from-CSV/assets/118707204/ddbc0b63-dc23-4670-8d56-a178058ed454)

## RESULT:
Thus the program executed successfully for read csv file.
