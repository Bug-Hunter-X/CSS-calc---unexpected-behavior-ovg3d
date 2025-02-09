# CSS `calc()` Unexpected Behavior

This repository demonstrates a common issue with the CSS `calc()` function and provides a solution.

The problem arises from unexpected behavior when combining percentages and fixed units (like pixels) in `calc()` calculations, especially when the parent element's dimensions aren't explicitly defined.

The `bug.css` file showcases the problem, while `bugSolution.css` provides a solution.

## Problem

The unexpected behavior occurs when the container's width is not explicitly defined and `calc()` tries to calculate from an undefined percentage.