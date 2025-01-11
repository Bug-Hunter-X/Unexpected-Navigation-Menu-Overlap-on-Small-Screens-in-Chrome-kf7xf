# Unexpected Navigation Menu Overlap on Small Screens in Chrome

This repository demonstrates an uncommon CSS bug where the navigation menu overlaps with other elements on small screens (less than 768px) in the Chrome browser.  The bug is caused by unexpected behavior in how the CSS handles media queries and element positioning in this specific browser and screen size.

## Bug Report

The provided `bug.css` file contains the problematic CSS code.  The navigation menu (`nav`) does not collapse appropriately and overlaps content when the screen width is smaller than 768px in Chrome. This works fine in other browsers. 

## Solution

The solution provided in `bugSolution.css` addresses the issue by adding specific styles to target the problematic behavior of Chrome.  The solution is a more robust way of handling the menu's behavior across different screen sizes and browsers, making it less susceptible to unexpected behavior.

## How to Reproduce

1. Clone this repository.
2. Open `index.html` (you will have to create this simple html with a nav element) in Chrome.
3. Resize the browser window to a width smaller than 768px.
4. Observe the overlap of the navigation menu.
5. Compare this behavior with other browsers for the same scenario.