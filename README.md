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

Program to mark the maximum of marks using the list method sort.


Program Developed by: srivatsan G 


Register No:212223230216

```
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large

```

ii)	 To find the maximum marks using the list method max().

Program to find the maximum marks using the list method max().


Program developed by: srivatsan G 


Register No: 212223230216

```
def max_marks(marks):
    large=max(marks)
    return large

```

iii)  To find the maximum marks without using builtin functions.

Program to find the maximum marks without using builtin functions.


Program developed by: SRIVATSAN G


Register No: 212223230216

```
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max

```

## Output:
![FIND MAX 1](https://github.com/vatsan143/FindMaximum/assets/147368204/dbf7bbcf-7d5b-48d6-a8c0-cf1baddafd67)
![FIND MAX 2](https://github.com/vatsan143/FindMaximum/assets/147368204/1cd6fc88-8c34-4168-aabb-484b13201631)
![FIND MAX 3](https://github.com/vatsan143/FindMaximum/assets/147368204/085c89ef-246f-45a1-acda-69aa8d69c92f)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
