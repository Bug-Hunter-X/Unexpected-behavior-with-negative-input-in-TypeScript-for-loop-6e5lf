# Unexpected behavior with negative input in TypeScript for loop

This code demonstrates an unexpected behavior in a TypeScript function that iterates through numbers using a for loop. When a negative number is provided as input, the loop does not execute, resulting in no output.  The issue lies in the loop condition `i <= n`. When `n` is negative, `i` (starting at 1) will never be less than or equal to `n`, hence the loop never starts. 

The solution involves adding a check to handle negative input appropriately, either by throwing an error, printing an appropriate message, or modifying the loop to handle the negative case correctly.