# ZeroDivisionError in seemingly safe Python function

This repository demonstrates an uncommon error scenario in Python involving a `ZeroDivisionError` despite seemingly robust error handling. The function `function_with_uncommon_error` intends to handle cases where either `a` or `b` is 0. However, it fails when both `a` and `b` are 0, leading to a division by zero.

The `bug.py` file contains the erroneous code and the `bugSolution.py` demonstrates the correct implementation.