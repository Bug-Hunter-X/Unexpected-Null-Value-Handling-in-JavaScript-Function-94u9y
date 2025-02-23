# JavaScript Null Value Handling Bug

This repository demonstrates a common error in JavaScript:  incorrect handling of null values.  The `foo` function in `bug.js` fails to correctly account for `null` inputs, leading to potential runtime errors. The correct implementation in `bugSolution.js` shows how to safely check for nulls before processing.

## Bug

The original code lacked sufficient null checks, potentially leading to errors when null values were passed as arguments.

## Solution

The solution adds explicit checks for null values before proceeding with the function's core logic.