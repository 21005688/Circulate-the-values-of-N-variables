# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
import the numpy module to use the built- in functions for caculation.
### Step 2:
Prepare the lists from each circulate the values and assign in np.array(). 
### Step 3: 
Get the value from the user for the number of rotation.
### Step 4: 
Using the slicing concept rotate the list.

### Step 5:
End the program
## Program:
~~~
#Program to circulate N values.
#Developed by: Gayathri A
#RegisterNumber: 21500440
def circulate(): 
    X = [10,20,30,40,50,60]
    n=int(input())
    X = X[n:]+X[:n]
    print("After circulating the values are:",X)
~~~

## Output:
![output](https://github.com/21005688/Circulate-the-values-of-N-variables/blob/main/kd%20gayu.jpg?raw=true)

## Result:
Thus circulating the n variables using python are successfully executed.
