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
## input :
![input](https://github.com/Kishorerz/FindMaximum/assets/144451216/80688e0f-86fd-4b5d-9a63-a971fd73477e)
## output :
![output](https://github.com/Kishorerz/FindMaximum/assets/144451216/925e09db-bda6-4eb2-aa96-f63f71cd62d8)

## output 1 :
![output1](https://github.com/Kishorerz/FindMaximum/assets/144451216/8b2aad89-f32b-4137-8a98-d682954b6e36)
## output 2 :
![output2](https://github.com/Kishorerz/FindMaximum/assets/144451216/682937bf-d619-4b6e-b1a4-63628e08406e)
## output 3 :
![output3](https://github.com/Kishorerz/FindMaximum/assets/144451216/021638a1-5f2b-4408-82d2-589e0c5f72d1)
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
