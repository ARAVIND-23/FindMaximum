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
#developed by:ARAVIND G
#register number:212223240011
def max_marks(array):
    array.sort()
    return array[-1]


```

ii)	# To find the maximum marks using the list method max().
```Python
#developed by:ARAVIND G
#register number:212223240011
def max_marks(array):
    return max(array)


```

iii) # To find the maximum marks without using builtin functions.
```Python
#developed by:ARAVIND G
#register number:212223240011
def max_marks(array):
    max1=array[0]
    for i in range(1,len(array)):
        if max1<array[i]:
            max1=array[i]
    return max1


```



## Output:
![Screenshot 2024-05-19 154128](https://github.com/ARAVIND-23/FindMaximum/assets/138970182/1d10c18c-ea01-4514-aee4-7ba955db7081)
![Screenshot 2024-05-19 154359](https://github.com/ARAVIND-23/FindMaximum/assets/138970182/a65c19ec-9599-4893-b09b-5ef8aac6b9ee)
![Screenshot 2024-05-19 154515](https://github.com/ARAVIND-23/FindMaximum/assets/138970182/334c0d08-9029-4c64-a170-457dc16ef1fc)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
