# Unexpected String Concatenation in JavaScript Function
This repository demonstrates an uncommon code error in JavaScript involving unexpected string concatenation.

## Description
The JavaScript function `foo` is intended to add two numbers. However, if a string is provided as one of the arguments, JavaScript's loose typing allows for string concatenation instead of numerical addition, resulting in unexpected output.

## Bug
The `bug.js` file contains the buggy code. When called with a number and a string, it concatenates them instead of adding them numerically.

## Solution
The `bugSolution.js` file provides a corrected version of the function. It includes explicit type checking to prevent string concatenation. This approach makes the function more robust and predictable.

## How to reproduce the bug
1. Clone the repository.
2. Run `node bug.js` in your terminal.