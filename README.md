# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
 using function circulate
### Step 2:
Get the value from the user for the number of rotation
### Step 3: 
Using the slicing concept rotate the list

### Step 4: 
print the result.

## Program:
```
#Program to circulate N values.
#Developed by: Koti Sai Sankar
#RegisterNumber: 22001315

def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
    
    
```

## Output:
!["Output"](/Screenshot%20from%202022-12-25%2000-10-16.png)
## Result: 
 Successfully Executed

