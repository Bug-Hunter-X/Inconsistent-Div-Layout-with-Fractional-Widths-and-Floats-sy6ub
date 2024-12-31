# Inconsistent Div Layout with Fractional Widths and Floats

This repository demonstrates a common CSS layout issue involving floating div elements and fractional widths.  The bug arises from the imprecise rendering of floats when dealing with percentages that don't evenly divide the container's width.  This can result in unexpected layout variations across different browsers.

The `bug.css` file contains the problematic code.  The `bugSolution.css` file offers a solution using flexbox or grid, which provide more reliable and predictable layout control.

## How to Reproduce

1. Clone the repository.
2. Open `index.html` in your browser.
3. Observe the inconsistent layout of the divs across different browser and window sizes.

## Solution

The provided solution uses flexbox for improved layout control, ensuring consistent behavior across browsers and responsive adjustments.