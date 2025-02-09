# CSS Specificity Issue with !important and Nested Selectors

This repository demonstrates an uncommon CSS specificity issue involving the `!important` declaration and nested selectors.  The bug showcases how the order of declarations and the cascading nature of CSS can lead to unexpected behavior, even when using `!important`.

## Bug Description

The core problem lies in the interaction between specificity, the `!important` flag, and the order of CSS rules.  While `!important` generally has higher precedence, its effectiveness can be overridden by a more specific selector declared later, creating counter-intuitive results.

## How to Reproduce

1. Clone this repository.
2. Open `bug.css` and observe the CSS rules. 
3. Create a corresponding HTML file to test with the CSS styles and examine the resulting styles applied to the element.