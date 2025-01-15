# JavaScript Null Value Handling

This example demonstrates a common issue in JavaScript: handling null values.  Improper handling of nulls can lead to unexpected behavior or runtime errors.  This code snippet provides a safe way to add numbers, explicitly handling cases where one or both inputs might be null.

## The Bug
The `foo` function demonstrates a common strategy for handling null values in a function. The solution addresses the potential for `TypeError` exceptions that may arise when operating on null values.

## The Solution
The solution is simple, explicit checks for null values before the core functionality of the function. This pattern can be applied more widely to improve code robustness.