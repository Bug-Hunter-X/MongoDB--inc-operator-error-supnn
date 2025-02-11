# MongoDB $inc Operator Error
This repository demonstrates a common error when using the `$inc` operator in MongoDB update queries. The `$inc` operator is used to increment or decrement a numeric field in a document.  However, if you provide a string value instead of a number, it will not increment correctly and may result in unexpected behavior. 

## Bug
The bug lies in the incorrect usage of the `$inc` operator. The provided value should be a number, not a string.

## Solution
The solution is to use a numeric value instead of a string when using the `$inc` operator.