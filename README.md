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
''' 
Program to mark the maximum of marks using the list method sort
Developed by: Yuvaraj V
RegisterNumber: 23013769
'''
def max_marks(marks):
    marks.sort()
    return marks[-1]
```
ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: Yuvaraj V
RegisterNumber: 23013769
'''
def max_marks(marks):
    return max(marks)
```
iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: Yuvaraj.V
RegisterNumber: 23013769
'''
def max_marks(list1):
    marks=list1[0]
    
    for i in range(1,len(list1)):
        if(marks<list1[i]):
           marks=list1[i]
    return marks
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
