# Off-by-One Error in Java Array

This repository demonstrates a common off-by-one error in Java when iterating over an array.  The `BuggyArray.java` file contains the erroneous code, while `FixedArray.java` shows the corrected version.

**The Error:**
The original code attempts to access an array element beyond its bounds causing an `ArrayIndexOutOfBoundsException`. This is a frequent mistake when using loop counters and array indices.

**The Solution:**
The corrected code ensures the loop condition avoids accessing the element beyond the last valid index.  The loop should always use `i < arr.length` to iterate through the array elements correctly.