# JavaScript toString() method and null/undefined values

This repository demonstrates a common JavaScript bug related to the use of the `toString()` method with `null` and `undefined` values.

The `bug.js` file contains the buggy code.  The `bugSolution.js` file provides a corrected version.

## Bug Description
The original code attempts to call `toString()` on values that might be `null` or `undefined`, leading to a `TypeError`. The solution addresses this by explicitly checking for `null` and `undefined` before calling `toString()`. 

## How to reproduce
1. Clone this repository.
2. Open `bug.js` and `bugSolution.js` in a JavaScript environment.
3. Run the code in `bug.js` to observe the error.
4. Run the code in `bugSolution.js` to see the corrected output.

## Solution
The solution involves adding explicit checks for `null` and `undefined` before using the `toString()` method, preventing the `TypeError`.