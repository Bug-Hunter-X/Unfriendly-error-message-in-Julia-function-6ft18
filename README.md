# Unfriendly Error Message in Julia Function

This example demonstrates a common issue in Julia:  unhelpful error messages. The function `myfunction` correctly handles positive and zero inputs, but when a negative input is provided, the error message is not informative.

The goal is to improve the error message to better guide the user on how to fix the issue.

## Files

- `bug.jl`: Contains the original function with the poor error message.
- `bugSolution.jl`: Shows the improved function with a more user-friendly error message.