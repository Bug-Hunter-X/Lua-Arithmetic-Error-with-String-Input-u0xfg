# Lua Arithmetic Error with String Input

This repository demonstrates a common error in Lua: attempting to perform arithmetic operations on a string value. The `foo` function is intended to add 1 to a numerical input, but lacks proper input validation, leading to an error when a string is passed.

The `bug.lua` file contains the erroneous code, while `bugSolution.lua` provides a corrected version with improved input handling.

This is a classic example of the importance of validating user input and ensuring the data types are consistent before performing any arithmetic or other potentially unsafe operations.