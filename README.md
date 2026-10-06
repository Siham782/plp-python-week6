# PLP Python Week 6 - Safe Tools

This assignment practices handling errors using `try` and `except` in Python.

* `safe_tools.py` - Contains three safe functions for division, number conversion, and dictionary field lookup.
* `unbreakable.py` - Demonstrates handling errors so the program can continue running.
* `README.md` - Describes the assignment and explains the use of error handling.

An `if` check cannot catch `abc` on its own because `abc` causes a `ValueError` when Python tries to convert it with `int()`. The conversion must be attempted first, and `try`/`except` can then handle the error safely.
