# Unexpected Behavior with Loose Equality and Null in JavaScript

This repository demonstrates a common error in JavaScript related to loose equality (==) when comparing values to null.  Loose equality can lead to unexpected behavior, especially when dealing with null and 0.

The bug.js file contains a function that adds two numbers. However, it uses loose equality to handle null values which leads to an incorrect result. The bugSolution.js file provides a corrected version of the function.

## How to Reproduce

1. Clone this repository.
2. Open bug.js in a JavaScript environment.
3. Run the file and observe the unexpected output.
4. Compare the output with the expected behavior demonstrated in the bugSolution.js file.

## Solution

The issue is resolved by using strict equality (===) instead of loose equality (==). Strict equality ensures that the types of values are also compared, thereby preventing unexpected results when dealing with null.

This example highlights the importance of using strict equality when comparing values to null or undefined to prevent subtle bugs in your JavaScript code.