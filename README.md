# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Step1:
Get the list of marks as input
## Step2:
Use the sort() function or max() function or use the for loop to find the maximum mark.
## Step3:
Return the maximum value
## Program:

## i)	 To find the maximum of marks using the list method sort.
```
''' 
Program to mark the maximum of marks using the list method sort
Developed by: MOHAMED AAKIF ASRAR S
RegisterNumber: 23003613
'''
def max_marks(marks):
    marks.sort()
    return marks[-1]

```

## ii)	 To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by: MOHAMED AAKIF ASRAR S
RegisterNumber: 23003613
'''
def max_marks(marks):
    a=max(marks)
    return a

```

## iii)  To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: MOHAMED AAKIF ASRAR S
RegisterNumber: 23003613
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
![Screenshot 2023-12-21 180222](https://github.com/MOHAMEDAAKIFASRAR/FindMaximum/assets/148514683/65ac1476-cd94-4e7a-8d7a-be3e851d8716)
![Screenshot 2023-12-21 180237](https://github.com/MOHAMEDAAKIFASRAR/FindMaximum/assets/148514683/a2067524-6b1d-4c38-b49c-5383541867dc)
![Screenshot 2023-12-21 180252](https://github.com/MOHAMEDAAKIFASRAR/FindMaximum/assets/148514683/fd3db15d-9bf5-4e6b-83ea-6f2a6c29da51)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
