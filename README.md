# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 

### Step 1: 
Take input from the user for a list l.

### Step 2: 
Take input from the user for the number of positions to circulate n.

### Step 3: 
Get the value from the user for the number of rotation

### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
Print the new list (result) to the console.

### Step 6: 
End of the Program

## Program:
```
#Program to circulate N values.
#Developed by: NAEEN KUMAR M
#RegisterNumber: 212222110028
    
def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)
```

## Output:
![image](https://user-images.githubusercontent.com/119394582/230939652-423c1575-ad60-4bb0-93af-1b32abcdb362.png)


## Result:
Thus the program to circulate the values of n variables are successfully executed
