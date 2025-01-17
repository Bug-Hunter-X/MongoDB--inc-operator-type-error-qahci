# MongoDB $inc Operator Type Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations. The `$inc` operator is used to increment a numerical field by a specified value. However, if a string is provided as the increment value, a type error will occur.

## Bug
The bug lies in the incorrect usage of the `$inc` operator.  The provided value is a string ("1") rather than a number (1). This leads to an error when MongoDB attempts to perform the incrementation.

## Solution
The solution involves ensuring that the value provided to the `$inc` operator is a number, not a string. Correcting the code to use the numerical value (1) resolves the issue.
