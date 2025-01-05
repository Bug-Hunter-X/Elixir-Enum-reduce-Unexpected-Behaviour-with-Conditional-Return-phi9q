# Elixir Enum.reduce Unexpected Behaviour

This repository demonstrates a subtle bug in Elixir code using `Enum.reduce`. The issue arises from inconsistent return types within the reducer function, leading to unexpected results.

## Bug Description

The `bug.ex` file contains Elixir code that uses `Enum.reduce` to sum numbers in a list only if the number is greater than 3. However, it can produce unexpected results because of the inconsistent return value.  

## Solution

The `bugSolution.ex` file provides a corrected version of the code, ensuring consistent return types within the reducer function, leading to the expected behaviour. 