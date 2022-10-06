# Inverse-of-matrix

## AIM:

## ALGORITHM:
### Step 1:
### Step 2:
### Step 3:
### Step 4:
### Step 5:


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

## RESULT:
