# Unexpected Behavior of `calc()` in CSS
This repository demonstrates two uncommon errors related to the CSS `calc()` function:

1. **Percentage values with unset parent width:** Using percentages in `calc()` when the parent element's width is not explicitly defined can lead to unexpected results.
2. **Mixing different units without type conversion:** Combining percentages with other units (such as `px`, `em`, etc.) in a `calc()` function without proper type conversion can cause the calculation to fail.

The `bug.css` file contains examples of these errors, while `bugSolution.css` demonstrates how to avoid them.  The readme file further describes the solutions to the problems.