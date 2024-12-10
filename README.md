# Java ArrayIndexOutOfBoundsException Bug
This repository demonstrates a common Java error: the `ArrayIndexOutOfBoundsException`.  The `Bug.java` file contains code that attempts to access an array element beyond its defined bounds, resulting in the exception. The `BugSolution.java` file provides a corrected version.

**Bug Description:** The code attempts to assign a value to the 6th element (index 5) of an array of size 5, which is out of bounds. This causes an `ArrayIndexOutOfBoundsException`. 

**Solution:** The solution involves checking array bounds before accessing elements or using appropriate data structures that dynamically resize.