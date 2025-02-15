# CSS Specificity Issue: Unexpected Inheritance Behavior

This repository demonstrates a subtle but important CSS specificity issue that can lead to unexpected inheritance behavior when combining class and element selectors.  The problem arises when selectors of equal specificity are used, and the order of declaration doesn't guarantee the expected override.

The `bug.css` file contains the problematic CSS code.  The `bugSolution.css` demonstrates how to resolve the issue using more specific selectors or adjusting the order to ensure that later rules with equal specificity are applied.