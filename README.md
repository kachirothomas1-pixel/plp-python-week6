# PLP Python Week 6

- safe_tools.py - contains safe functions for division, number conversion, and dictionary field lookup with error handling.
- README.md - describes the assignment and explains the safe exception-handling approach.

An if check alone cannot catch "abc" because the problem is not a missing value or a simple condition; the conversion `int("abc")` raises a `ValueError`, which only a `try`/`except` block can handle gracefully.
