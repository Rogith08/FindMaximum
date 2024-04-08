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
#Program to mark the maximum of marks using the list method sort.
#Program developed by : ROGITH. K
#Register num:212223110042
def max_marks(a):
    a.sort()
    return a[9]



```

ii)	# To find the maximum marks using the list method max().
```Python
#Program to mark the maximum of marks using the list method max().
#Program developed by : ROGITH. K
#Register num:212223110042
def max_marks(a):
    return max(a)



```

iii) # To find the maximum marks without using builtin functions.
```Python
#Program to mark the maximum of marks without using builtin functions.
#Program developed by : ROGITH. K
#Register num:212223110042
def max_marks(a):
    max =a[0]
    for i in a:
        if(i>max):
            max=i
    return max



```



## Output:
![alt text](<Screenshot 2024-04-08 222827.png>)
![alt text](<Screenshot 2024-04-08 222857.png>)
![alt text](<Screenshot 2024-04-08 222914.png>)
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
