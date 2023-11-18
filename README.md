# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Define function named circulate
### Step 2: 
Take a list as input from the user and assign it to the variable l.
### Step 3: 
Take a integer as input from the user and assign it to the variable n.
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Print the updated list l with the message " After circulating the  values are"

## Program:
```
#Program to circulate N values.
#Developed by: Beatrice Thomas
#RegisterNumber: 23005036

def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)

```
## Output:
#![Alt text](<Screenshot 2023-11-18 094536.png>)# Output:

## Result:
Thus circulating variables are sucessfully executed.