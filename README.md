# TypeScript Type Error Example
This repository demonstrates a common type error in TypeScript where a function expects a specific type but receives an array of that type. The error arises when calling the `greeter` function with an array instead of a single string. The solution involves iterating through the array and calling the function for each element. 

## Bug
The `bug.ts` file contains a TypeScript function that expects a string as an argument.  However, it is called with an array of strings which leads to a type error. 

## Solution
The `bugSolution.ts` file demonstrates the solution which iterates through the array and calls the function appropriately for each element.