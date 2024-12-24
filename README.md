# VBScript Bug: Missing Option Explicit
This repository demonstrates a common VBScript error caused by omitting the `Option Explicit` statement.  The absence of `Option Explicit` allows implicit variable declaration, which can lead to unexpected behavior and difficult-to-debug errors.  The `bug.vbs` file showcases the issue, while `bugSolution.vbs` provides the corrected code.

## Bug Description
The `bug.vbs` script demonstrates a scenario where missing `Option Explicit` allows a variable to be used without a prior declaration, potentially leading to incorrect calculations or unexpected behavior. 

## Solution
Adding the `Option Explicit` statement at the beginning of the script forces explicit variable declarations, preventing such implicit assignments and enhancing code reliability.