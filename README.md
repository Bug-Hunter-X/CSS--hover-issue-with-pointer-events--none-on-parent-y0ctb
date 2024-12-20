# CSS Hover Issue with pointer-events: none

This repository demonstrates a subtle bug in CSS concerning the interaction between the `:hover` pseudo-class and the `pointer-events: none` property.  When a parent element has `pointer-events: none` set, hover events are not propagated to its children, preventing expected hover effects.

The `bug.css` file contains the problematic CSS code. The `bugSolution.css` provides a solution to work around this issue.

## Reproduction

1. Clone the repository.
2. Open `bug.html` (or a similar HTML file incorporating the CSS) in a web browser.
3. Observe that hovering over the parent element does not change the child's background color, despite the CSS rule intended to do so.

## Solution

Refer to `bugSolution.css` for a solution that addresses this limitation.