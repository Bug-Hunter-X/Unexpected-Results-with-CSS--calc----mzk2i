# Unexpected Results with CSS `calc()`

This repository demonstrates some uncommon errors that can occur when using the `calc()` function in CSS.  These errors often stem from subtle issues like incorrect spacing, missing multiplication operators, or incompatible units within the calculation.

The `bug.css` file contains examples of these problematic `calc()` expressions.  The `bugSolution.css` file provides corrected versions with explanations of the fixes.

## Common `calc()` Pitfalls:

* **Incorrect Spacing:**  Spaces around operators are crucial. Incorrect spacing can lead to unexpected parsing. 
* **Missing Multiplication Operators:**  When multiplying, you *must* explicitly use the `*` operator.
* **Incompatible Units:** You can't directly add or subtract different units (e.g., `px` and `em`) within a single `calc()` expression.

## How to reproduce:
1. Clone this repository.
2. Open `bug.html` (or create your own HTML) and include the `bug.css` file. 
3. Observe the unexpected layout. 
4. Replace `bug.css` with `bugSolution.css` to see the corrected layout.

## Learning Points:
This exercise highlights the importance of carefully reviewing CSS calculations using `calc()` to ensure accurate and predictable layouts.