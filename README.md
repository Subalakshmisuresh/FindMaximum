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

## i) To find the maximum of marks using the list method sort.

```Python
''' 
Program to mark the maximum of marks using the list method sort
Developed by: SUBALAKSHMI . S
RegisterNumber: 212222100051
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

## ii)	To find the maximum marks using the list method max().

```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: SUBALAKSHMI . S
RegisterNumber: 212222100051
'''
def max_marks(marks):
    large=max(marks)
    return large
```

## iii) To find the maximum marks without using builtin functions.

```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: SUBALAKSHMI . S
RegisterNumber: 212222100051
'''
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i > max:
            max = i
    return max     
```

## Sample Input and Output

![output](./img/max_marks1.jpg) 

![image](https://github.com/Subalakshmisuresh/FindMaximum/assets/121957896/64dd4fed-2c42-4787-857c-5e69da8ef2e9)

![image](https://github.com/Subalakshmisuresh/FindMaximum/assets/121957896/adb48160-0282-4746-a250-22e4cfd4bb9e)



## Output:

## i) To find the maximum of marks using the list method sort.

![image](https://github.com/Subalakshmisuresh/FindMaximum/assets/121957896/55e00cc9-37e8-483e-8880-f584b0597cda)


## ii)	To find the maximum marks using the list method max().

![image](https://github.com/Subalakshmisuresh/FindMaximum/assets/121957896/c5df40be-1058-4ed8-b0ce-f8b9b61b4de7)


## iii) To find the maximum marks without using builtin functions.

![image](https://github.com/Subalakshmisuresh/FindMaximum/assets/121957896/fd9c20df-fe54-4ba8-b0be-404573be058e)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
