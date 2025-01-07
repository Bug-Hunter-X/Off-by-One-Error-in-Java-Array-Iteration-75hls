# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over arrays.  The `BuggyArray.java` file contains the erroneous code, while `FixedArray.java` provides the corrected version.

The error occurs because the loop condition `i <= arr.length` attempts to access an array element beyond the valid index range (0 to arr.length - 1).  This results in an `ArrayIndexOutOfBoundsException`.

The solution involves changing the loop condition to `i < arr.length`.