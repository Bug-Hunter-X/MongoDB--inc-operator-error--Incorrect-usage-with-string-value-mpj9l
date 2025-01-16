# MongoDB $inc operator error
This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations. The `$inc` operator is used to increment a numeric field by a specified value. However, it is crucial to provide a numeric value; otherwise, an error will occur.

## Bug Description
The original code attempts to increment a field with a string value. This results in an error because the `$inc` operator only works with numbers. 

## Solution
The solution corrects this by providing a numeric value to the `$inc` operator.