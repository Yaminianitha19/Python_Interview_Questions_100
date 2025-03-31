<!-- what are the key features of python -->

![alt text](image.png)

<!-- what are keyword in python -->

![alt text](image-1.png)

<!-- what are literals in python -->

![alt text](image-2.png)

<!-- How can ypu concatenate two tuples -->

t1 = (1,"abc",True)
t2 = (2,4,7)
print(t1 + t2)

<!-- what are functions in python -->

![alt text](image-3.png)
example:
<!--  -->
    def greet(name):
    return f"Hello, {name}!"

    # Calling the function
    print(greet("Yamini"))

<!--  -->

<!-- How can you initialze a 5x5 NumPy array with only zeros? -->
![alt text](image-4.png)

import numpy as np
n1 = np.zeros((5,5))
print(n1)

<!-- o/p: -->

[[0 0 0 0 0]
[0 0 0 0 0]
[0 0 0 0 0]
[0 0 0 0 0]
[0 0 0 0 0]]

<!-- what is Pandas? -->

![alt text](image-5.png)

<!-- what are DataFrames -->

![alt text](image-6.png)
with example:
![alt text](image-7.png) 

<!-- what is csv file? -->
A CSV (Comma-Separated Values) file is a plain text file that stores data in a tabular format (rows and columns), where values are separated by commas. It is commonly used for storing and exchanging data between different applications like Excel, databases, and Python.

<!-- eg: -->
Name,Age,City
Alice,25,New York
Bob,30,London
Charlie,35,Paris

<!-- it can stored as like: -->
     Name  Age      City
0   Alice   25  New York
1     Bob   30   London
2  Charlie   35    Paris

<!-- program: -->

import pandas as pd
df = pd.read_csv("data.csv")  # Reading the CSV file
print(df)  # Displaying the content

<!-- what is Pandas Series -->
![alt text](image-9.png)
<!-- what is dtype in output? -->

![alt text](image-10.png)

<!-- what is the use of Pandas groupby() function? -->

![alt text](image-11.png)
example:
![alt text](image-12.png)
<!-- Explanation: -->
The groupby('Department') groups the data by the "Department" column.

['Salary'].mean() calculates the average salary for each department.

It can also be used with other aggregate functions like .sum(), .count(), .max(), .min(), etc.

<!-- HOW to create dataframe from list -->
![alt text](image-14.png)

![alt text](image-13.png)

<!-- how to combine dataframes using join() func -->

![alt text](image-15.png)
![alt text](image-16.png)
![alt text](image-17.png)
<!-- vertical stacking -->
![alt text](image-18.png)
<!-- horizondal stacking -->
![alt text](image-19.png)







