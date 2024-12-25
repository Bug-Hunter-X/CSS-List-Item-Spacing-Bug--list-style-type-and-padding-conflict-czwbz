# CSS List Item Spacing Bug

This repository demonstrates an uncommon CSS bug related to list item spacing. The bug arises from an unexpected interaction between the `list-style-type` and `padding` properties when styling lists.  Specifically, certain `list-style-type` values, combined with `padding` values, can lead to incorrect spacing between list items, causing them to overlap or appear clustered.

The `bug.css` file shows the problematic CSS, while `bugSolution.css` presents a solution demonstrating how to correctly space list items in these scenarios.

## How to Reproduce

1. Clone this repository.
2. Open `bug.html` (or create your own HTML with a `<ul>` or `<ol>` element). 
3. Apply the styles from `bug.css`. Observe the unexpected spacing or overlap of list items. 
4. Replace `bug.css` with `bugSolution.css` to see the fixed implementation.

## Discussion

The root cause is a subtle interaction between how the browser renders list markers and how it applies padding.  The solution illustrates several ways to achieve the desired spacing using different techniques, avoiding the unforeseen behavior.

This example highlights the importance of thorough testing and understanding the nuances of CSS property interactions.  Even seemingly straightforward styles can lead to unusual results if not carefully considered.