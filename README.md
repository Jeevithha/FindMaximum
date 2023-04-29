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
Developed by:jeevitha S 
RegisterNumber:212222100016

def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large
    
```

ii)	# To find the maximum marks using the list method max().
```Python

Program to find the maximum marks using the list method max().
Developed by: jeevitha S
RegisterNumber:212222100016 

def max_marks(marks):
    large = max(marks)
    return large
    
```
iii) # To find the maximum marks without using builtin functions.
```Python

Program to the maximum marks without using builtin functions.
Developed by: 
RegisterNumber: 

def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i > max:
            max = i
    return max

```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
i)![image](https://user-images.githubusercontent.com/123623197/235304082-25f1818c-3009-4dd1-8939-71ba955b0557.png)

ii)![image](https://user-images.githubusercontent.com/123623197/235304113-a7fda1b8-8ab2-4966-be47-b98f17e71e34.png)

iii)![image](https://user-images.githubusercontent.com/123623197/235304126-501e9d80-183a-4ce9-ae99-10a30ad8eddc.png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
