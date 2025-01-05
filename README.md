# Haskell Undefined Variable Bug

This repository demonstrates a common error in Haskell: using an undefined variable.  The `bug.hs` file contains code that attempts to use the undefined value directly in a calculation, leading to a runtime exception. The `bugSolution.hs` file provides a corrected version.

## Problem
The `undefined` value in Haskell represents a computation that has no possible result.  Attempting to perform operations on `undefined` will always result in a runtime error.  This is a common mistake when working with lazy evaluation and pattern matching.

## Solution
The solution involves providing a proper definition or handling the possibility of an undefined value using appropriate error handling techniques, such as pattern matching or the `Maybe` type.