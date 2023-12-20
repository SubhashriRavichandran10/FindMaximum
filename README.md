# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```Python
Program to mark the maximum of marks using the list method sort
Developed by:R.Subhashri 
RegisterNumber:23012776 
'''
def max_marks(marks):
    marks.sort()
    return marks[-1]


```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by:R.Subhashri 
RegisterNumber:23012776 
'''
def max_marks(marks):
    a=max(marks)
    return a



```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by:R.Subhashri 
RegisterNumber:23012776 
'''
def max_marks(list1):
    a=0
    for i in list1:
        if i>a:
            a=i
    return a



```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![Screenshot 2023-12-20 104250](https://github.com/SubhashriRavichandran10/FindMaximum/assets/145743413/5d346c9b-b6c1-4700-bcd9-f892c43d4cca)
![Screenshot 2023-12-20 111934](https://github.com/SubhashriRavichandran10/FindMaximum/assets/145743413/c063aa30-d357-4ada-8d0f-53cac4a64cfe)
![Screenshot 2023-12-20 112013](https://github.com/SubhashriRavichandran10/FindMaximum/assets/145743413/02108ac2-1800-46f0-92eb-a46fb175e63e)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
