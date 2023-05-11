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

i) To find the maximum of marks using the list method sort.
```
Program to mark the maximum of marks using the list method sort
Developed by: HARISH RAGAV S
RegisterNumber: 212222110013

def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large
```

ii)	To find the maximum marks using the list method max().
```
Program to find the maximum marks using the list method max().
Developed by: HARISH RAGAV S
RegisterNumber: 212222110013

def max_marks(marks):
    large = max(marks)
    return large
```

iii)To find the maximum marks without using builtin functions.
```
Program to the maximum marks without using builtin functions.
Developed by: HARISH RAGAV S
RegisterNumber: 212222110013

def max_marks(list1):
    max = list1[0]
    for i in list1 :
        if i > max :
            max = i
    return max
```

## Output:
i) To find the maximum of marks using the list method sort.
![Screenshot 2023-05-11 090050](https://github.com/harishragav272003/FindMaximum/assets/119345345/230482ee-0d4c-4aa9-9be4-a4491ff1ca61)

ii)	To find the maximum marks using the list method max().
![Screenshot 2023-05-11 090120](https://github.com/harishragav272003/FindMaximum/assets/119345345/5f58e9fd-66f1-455a-a6fe-f79872a18f64)

iii)To find the maximum marks without using builtin functions.
![Screenshot 2023-05-11 090120](https://github.com/harishragav272003/FindMaximum/assets/119345345/6cc0c4e9-9a81-4977-bf60-0ecf7c05340c)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
