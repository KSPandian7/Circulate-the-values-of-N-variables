# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
Step 1:

Import def circulate.
Step 2:

Prepare the lists from each linear equations and assign in np.array()
Step 3:

Get the value from the user for the number of rotation
Step 4:

Using the slicing concept rotate the list
Step 5:

Add coding to the input value.
Step 6:

Print the coding to get answer.
## Program:
```python
#Program to circulate N values.
#Developed by: kulasekarepandian
#RegisterNumber: 22001410
def circulate():
    a=eval(input())
    n=int(input())
    a=a[n:]+a[:n]
    print("After circulating the values are:",a)
```

## Output:
![output](/op.png)
## Result:
Thus the Circulating the values are sucessfully executed.