# MongoDB $inc Operator Error
This example demonstrates an incorrect usage of the `$inc` operator in a MongoDB update operation.  The `$inc` operator is used to increment or decrement a numerical field by a specified value.  The crucial error here is providing a string value instead of a numerical value to the `$inc` operator. This will lead to an error.

## Solution
The solution involves modifying the update operation to provide a numerical value to the `$inc` operator, ensuring that it works correctly.