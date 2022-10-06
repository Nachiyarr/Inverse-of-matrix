# Inverse-of-matrix

## AIM:
To find inverse of a matrix.

## ALGORITHM:
### Step 1:

Import numpy module.
### Step 2:
Create l1 and l2 as emptyn list.

### Step 3:
Get the input of the varibles n and m.

### Step 4:
Loop a varible i in range n and nest loop a varible j in range m.

### Step 5:
Get the value of num varible.

### Step 6:
During the loop append the values to l1 and l1 vlues to l2 then make l1 as empty list. 

### Step 7:
Declare a arr1 to l2 by converting it to an array.

###Step 8:
Declare a varible inverse using numpy linalg and inverse fuctions find inverse of l2.

###Step 9:
Print the values of the inverse.


## PROGRAM:
#Developed by: Alagu Nachiyar K

#Regitration no:22002084
```
import numpy as np
r,c=int(input()),int(input())
l1,l2=[],[]
for i in range(r):
    for j in range(c):
        l1.append(int(input()))
    l2.append(l1)
    l1=[]
print(l2)
arr1=np.array(l2)
inverse=np.linalg.inv(arr1)
print(inverse)
```

## OUTPUT:
![inverse](https://user-images.githubusercontent.com/113497340/194260404-57d9f521-b5fb-46be-9b90-fdd8e004692b.png)


## RESULT:
The program is runned successfully...
