# CSS `calc()` Unexpected Behavior
This repository demonstrates a common issue with the CSS `calc()` function when combining percentages and fixed units (like pixels or ems).  The `calc()` function, while powerful, can sometimes produce inconsistent results across browsers or in dynamic layouts.

The `bug.css` file shows the problem, and `bugSolution.css` offers a potential solution or workaround.

**Problem:** The expected behavior is a div with a width of 50% of its parent, minus 10 pixels.  However, depending on the browser or context, the calculation may be inaccurate, leading to layout issues.

**Solution:**  The solution demonstrates possible workarounds, including using alternative layout techniques or avoiding the direct mixing of percentage and fixed units within `calc()`.