# CSS Calc() Unexpected Behavior in Flexbox

This repository demonstrates a common issue encountered when using the `calc()` function in CSS, specifically within flexbox layouts. The problem arises from improper usage of `calc()` in scenarios where the parent element doesn't have an explicitly defined width.

## Bug Description

The `bug.css` file contains CSS code that attempts to calculate a width using `calc()`.  However, because the parent container lacks a defined width, the calculation yields unpredictable results. This often results in elements not rendering as expected or displaying unexpected behavior. 

## Solution

The `bugSolution.css` file provides the corrected CSS, demonstrating the proper way to use `calc()` within a flexbox context by adding a defined width to the parent element.