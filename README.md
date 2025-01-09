# CSS Specificity Bug: Unexpected Rule Override

This repository demonstrates a subtle bug in CSS related to specificity and inheritance. The `bug.css` file contains CSS code where a seemingly more specific rule is unexpectedly overridden by a less specific rule due to the way CSS resolves specificity conflicts.

The `bugSolution.css` file provides a corrected version.  The issue highlights a common source of confusion for developers unfamiliar with the intricacies of CSS specificity.

To reproduce the bug, simply include `bug.css` in your HTML and observe the unexpected styling. The solution file demonstrates how to resolve the issue by addressing the specificity problem.