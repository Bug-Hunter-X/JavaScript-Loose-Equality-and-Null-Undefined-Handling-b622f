# JavaScript Loose Equality and Null/Undefined Handling

This repository demonstrates a common JavaScript error involving the loose equality operator (`==`) and the handling of `null` and `undefined` values.  The provided code shows the problem, and a solution is offered to handle these cases correctly.

## Problem

JavaScript's loose equality operator (`==`) performs type coercion, which can lead to unexpected behavior when comparing `null` and `undefined`.  In the example code, the function is intended to handle `null` as a special case, returning 0. However, `undefined` is also treated inconsistently due to the loose comparison.

## Solution

The solution demonstrates the use of strict equality (`===`) and explicit checks for `null` and `undefined` to avoid the type coercion issues. This provides more predictable and robust code.

## How to Run

1. Clone the repository
2. Navigate to the directory using your terminal
3. Run the code using Node.js: `node bug.js` and `node bugSolution.js`