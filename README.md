# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
start the program
### Step 2: 
get the input from the user using eval(input())
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
Using concatenation operation display the entire rotated list
### Step 6:
Stop the program 
## Program:
```
#Program to circulate N values.
#Developed by: KISHOR KUMAR B.
#RegisterNumber:23009985
def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print('After circulating the values are:',result)

```
## Output:
!["Output"](![OutPut](https://github.com/Kishorerz/Circulate-the-values-of-N-variables/assets/144451216/7ce9e456-3bd8-4fe8-bdb9-b22df93d7c27)
)
## Result:
Thus the python program for circulate the values of n variables is executed successfully
