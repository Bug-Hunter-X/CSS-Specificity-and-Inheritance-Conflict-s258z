# CSS Specificity and Inheritance Conflict

This repository demonstrates a subtle bug related to CSS specificity and inheritance.  The issue arises when a more specific selector attempts to override a style inherited from a parent element.

## The Problem

In the provided CSS, we expect a paragraph element inside a div with a specific ID to be styled with a specific color. However, due to the inheritance of styles and the way CSS specificity works, this does not happen as expected.

## The Solution

The solution involves understanding the order of precedence of CSS selectors and how inheritance interacts with it.  The solution CSS file offers a fix to achieve the desired styling.

## How to Run

1. Clone the repository.
2. Open `bug.html` in a web browser.
3. Compare the output to the solution by opening `solution.html`
