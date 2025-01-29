# TypeScript Type Error: Adding String to Number

This repository demonstrates a common type error in TypeScript where a function expects number type arguments, but receives a string. This results in a runtime error. The `bug.ts` file contains the erroneous code, while `bugSolution.ts` provides the corrected version.

## Bug
The `add` function is defined to accept two numbers and return their sum. However, in the example, a string is passed as an argument, resulting in a type error.

## Solution
The solution involves using type guards or input validation to ensure that the function receives the correct types. This prevents runtime errors and improves code reliability.