# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Define a function named circulate
### Step 2: 
Get a list input from the user
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
print the circulated value
### Step 6: 
call the function using function call
## Program:
~~~
#Program to circulate N values.
#Developed by:Rakshitha k 
#RegisterNumber:23003887
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
~~~
## Output:
![image](https://github.com/RakshithaK11/Circulate-the-values-of-N-variables/assets/139336455/5f987ef5-4e2d-467d-9a91-e1dec7f20424)

## Result:
Thus the circulating a list is succesfully executed
