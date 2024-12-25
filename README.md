# Unexpected Calculation Results with CSS calc() Function

This repository demonstrates an uncommon issue related to the CSS `calc()` function. The issue involves the unexpected results obtained when combining percentage and pixel values within the `calc()` function.

## Bug Description
The `calc()` function, while powerful, can sometimes produce unexpected outcomes.  This example showcases a situation where `calc(50% - 10px)` does not consistently yield the expected result across different browsers or rendering contexts.

## Reproduction
The `bug.css` file contains the problematic CSS code.  Observe the layout of the `.container` element in different browsers.  You might find that the width is not accurately calculated.

## Solution
The `bugSolution.css` file presents a possible workaround or a more robust approach to achieve the desired width calculation, mitigating the unpredictable behavior of the `calc()` function in this specific scenario.