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
Developed by: kishor kumar B.
RegisterNumber: 23009985
'''
def max_marks(marks):
    a=marks.sort()
    d=marks[-1]
    return d




```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: kishor kumar b.
RegisterNumber: 23009985
'''
def max_marks(marks):
    a=marks.sort()
    d=max(marks)
    return d


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: kishor kumar B.
RegisterNumber: 23009985
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
        
        


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 
## output 1 :
![output1](<Screenshot 2023-11-24 174149.png>)
## output 2 :
![output2](<Screenshot 2023-11-24 174207.png>)
## output 3 :
![output3](<Screenshot 2023-11-24 174219.png>)
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.