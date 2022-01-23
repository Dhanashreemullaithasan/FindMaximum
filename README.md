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
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large
max_marks([0,60,80,30,76,23])


```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    maxi=max(marks)
    return maxi


```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    maxi = list1[0]
    for i in list1:
        if i>maxi:
            maxi=i
    return maxi


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 
![max_marks2](https://user-images.githubusercontent.com/94165415/150683809-2dbe8149-b426-4def-94d8-f2803c6a3688.jpg)



## Output:
![img1](https://user-images.githubusercontent.com/94165415/150683844-a6196a18-e070-443a-9803-87ca9c502fed.png)
![img2](https://user-images.githubusercontent.com/94165415/150683850-b5c876ec-0f58-4ee2-a68a-42983dc460a1.png)
![img3](https://user-images.githubusercontent.com/94165415/150683858-442c69b1-5ff1-4438-af0b-b4fe298f97f9.png)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
