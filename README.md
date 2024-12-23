# Stack Overflow in Recursive Function

This repository demonstrates a common error in recursive functions: stack overflow due to a missing or incorrect base case.  The `foo` function calculates factorials, but it fails when given a negative input because the recursion never terminates.

The solution demonstrates how to properly handle the case of negative input to prevent stack overflow.