# ArrayIndexOutOfBoundsException Bug in Java

This repository demonstrates a common Java programming error: the `ArrayIndexOutOfBoundsException`.  The example code attempts to access an array element outside the valid index range, resulting in a runtime exception. The solution shows how to fix this error.

## Bug Description

The code creates an integer array of size 5 and then attempts to iterate through indices 0 through 5 (inclusive).  Because arrays are zero-indexed, the index 5 is out of bounds. This causes the `ArrayIndexOutOfBoundsException`. 

## How to Reproduce

1. Compile the `bug.java` file.
2. Run the compiled class.
3. Observe the `ArrayIndexOutOfBoundsException` being thrown.

## Solution

The solution (`bugSolution.java`) correctly modifies the loop condition to `i < arr.length`. This prevents the out-of-bounds access and avoids the exception.