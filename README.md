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
```
Program to mark the maximum of marks using the list method sort
Developed by: vikash s
RegisterNumber: 22008879
'''
def max_marks(marks):
marks.sort()
large=marks[-1]
return large




```

ii)	# To find the maximum marks using the list method max().
```Python
Program to find the maximum marks using the list method max().
Developed by: vikash s
RegisterNumber: 22008879
'''
def max_marks(marks):

 
max=marks[0]
for i in marks:
if i>max:
max=i
return max
 
max_marks([88, 67, 77, 93, 95, 11, 67, 89, 56, 89])


```

iii) # To find the maximum marks without using builtin functions.
```Python

Program to the maximum marks without using builtin functions.
Developed by: vikash s
RegisterNumber: 22008879
'''
def max_marks(list1):
max=list1[0]
for i in list1:
if i>max:
max=i
return max
 
max_marks([88, 67, 77, 93, 95, 11, 67, 89, 56, 89])

```
## Sample Input and Output
![Screenshot (84)](https://user-images.githubusercontent.com/119433834/215094448-4f35a1c0-9ea5-4cbc-9d61-68869e678724.png)


## Output:


![Screenshot (79)](https://user-images.githubusercontent.com/119433834/215094735-837cf0d2-47c9-411d-8fe5-f721462f0280.png)


![Screenshot (82)](https://user-images.githubusercontent.com/119433834/215094695-53973145-59b0-4a6c-bc02-69aec1e174cb.png)

![Screenshot (83)](https://user-images.githubusercontent.com/119433834/215094817-b8cdfe61-0334-4462-86dd-af1ea8f45d6a.png)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
