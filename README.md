# ArrayIndexOutOfBoundsException Bug in Java

This repository contains a simple Java program that demonstrates an `ArrayIndexOutOfBoundsException` and its solution. The bug arises from trying to access an array element using an index that's outside the valid range of the array.

## Bug Description
The `bug.java` file contains a program that attempts to access an array element at an invalid index (10), resulting in an `ArrayIndexOutOfBoundsException`.  This is a common error when working with arrays.

## Solution
The `bugSolution.java` file provides a corrected version of the program.  It includes boundary checks to ensure the index is within the valid range of the array, thus preventing the exception.