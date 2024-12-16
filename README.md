# CSS `calc()` Operator Precedence Bug

This repository demonstrates a common, yet subtle, bug related to operator precedence within the CSS `calc()` function.  The `calc()` function, while powerful, can lead to unexpected results if you don't carefully consider the order of operations.

**Bug:** Incorrect calculations in `calc()` due to left-to-right evaluation of `+` and `-`.

**Solution:** Using parentheses to explicitly control the order of operations.