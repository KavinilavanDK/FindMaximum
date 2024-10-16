## DATE: 
## Ex NO 6: Find the maximum of a list of numbers
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
```
# DVELOPED BY: KAVI NILAVAN DK
# REGISTER NUMBER: 212223230103
def max_marks(marks):
    marks.sort()
    return marks[-1]
```


ii)	# To find the maximum marks using the list method max().
```
# DVELOPED BY: KAVI NILAVAN DK
# REGISTER NUMBER: 212223230103
def max_marks(marks):
    return max(marks)
```

iii) # To find the maximum marks without using builtin functions.
```
# DVELOPED BY:  KAVI NILAVAN DK
# REGISTER NUMBER: 212223230103
def max_marks(marks):
    max_mark = marks[0]
    for mark in marks:
        if mark > max_mark:
            max_mark = mark
    return max_mark
```

## Output:
### i)
![Screenshot 2024-10-16 144917](https://github.com/user-attachments/assets/1cd24277-0622-4eed-9810-640b718636cc)

### ii)
![Screenshot 2024-10-16 145350](https://github.com/user-attachments/assets/b6b06197-d50a-43b4-99f7-a1f18859f277)

### iii)
![Screenshot 2024-10-16 145413](https://github.com/user-attachments/assets/73160d36-ca5c-44b7-8c29-7030e45c1fce)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
