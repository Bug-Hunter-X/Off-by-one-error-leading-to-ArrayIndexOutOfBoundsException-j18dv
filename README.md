# Off-by-One Error in Java
This repository demonstrates a common off-by-one error in Java that leads to an `ArrayIndexOutOfBoundsException`. The error occurs when the loop index exceeds the valid bounds of the array.

## Bug Description
The `bug.java` file contains code with a loop iterating from 0 to the array's length (inclusive). This causes an attempt to access an index that is out of bounds, resulting in the exception.

## Solution
The `bugSolution.java` file demonstrates the corrected code. The loop is modified to iterate up to, but not including, the array's length, preventing the out-of-bounds access.