# PLP Python Week 6 - Safe Tools

## Files

* `safe_tools.py` - Contains three functions that safely handle division, number conversion, and dictionary lookups.
* `unbreakable.py` - Contains the additional exception-handling exercise for Week 6.
* `README.md` - Explains the assignment and the purpose of each file.

## Why can't the `if` check catch `abc` on its own?

An `if` check cannot catch `"abc"` when it is being converted with `int()` because the error happens during the conversion itself. The `try` and `except ValueError` block catches the error and allows the program to continue running instead of crashing.
