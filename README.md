# Unexpected Null Handling in JavaScript Function

This repository demonstrates an unexpected null handling issue in a simple JavaScript function and provides a solution.

## Bug Description
The function `foo` is intended to add two numbers. However, it unexpectedly returns `null` if either of the input arguments is `null`. This behavior might not be intuitive or desirable in all cases.

## Solution
The solution involves handling null values gracefully, for instance, by treating them as 0. This modification ensures that the function produces a predictable output regardless of whether the input values are numbers or null.