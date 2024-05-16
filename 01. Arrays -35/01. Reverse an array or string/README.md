### 01. [Reverse an array](https://www.naukri.com/code360/problems/reverse-the-array_1262298?topList=love-babbar-dsa-sheet-problems&leftPanelTabValue=PROBLEM)

```py
from os import *
from sys import *
from collections import *
from math import *


# Tc: O(n)
# Sc: O(1)

# Define the method
def reverseArray(arr, m):

    # Compute the length of the array
    n = len(arr)
    
    # Declare and initialize the 2 pointer's i & j
    i = m + 1
    j = n - 1
    
    # Till the i<j condition holds swap the elements.
    while i < j:

        # Swap the positions
        arr[i], arr[j] = arr[j], arr[i]
        
        # Update the i pointer
        i += 1

        # Update the j pointer
        j -= 1
        
    # Finally return the updated array
    return arr
    
```
