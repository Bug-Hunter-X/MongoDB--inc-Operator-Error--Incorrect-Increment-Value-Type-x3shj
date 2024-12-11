# MongoDB $inc Operator Error: Incorrect Increment Value Type

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations. The error occurs when using a string value instead of a number when incrementing a numerical field.

## Bug Description
The `$inc` operator is used to increment (or decrement) a numerical field in a document.  However, if a string value is provided, MongoDB will likely throw an error or produce unexpected results.

## Bug Reproduction
1. Clone this repository
2. Connect to a MongoDB instance
3. Run the `bug.js` script.
4. Observe the error or unexpected result.

## Solution
The solution involves ensuring that the value passed to the `$inc` operator is a number.

## Solution Code
The `bugSolution.js` file provides the corrected code.