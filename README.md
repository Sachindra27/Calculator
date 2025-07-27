# Simple Calculator

This is a basic JavaScript calculator script that allows you to perform simple mathematical operations directly in the browser.

## Features
- Append numbers and operators to the display
- Clear the display
- Evaluate the mathematical expression
- Handle errors gracefully

## Files Used
- **HTML**: Contains the calculator structure (input field and buttons)
- **JavaScript**: Provides functionality for appending values, clearing the display, and calculating the result.

## How to Use
1. Add an HTML input field with the ID `display` in your HTML file.
2. Create calculator buttons that call the following functions:
   - `appendValue(value)` → Adds numbers/operators to the input field.
   - `clearDisplay()` → Clears the input field.
   - `calculate()` → Evaluates the expression in the display.

### Example HTML
```html
<input type="text" id="display" readonly>
<button onclick="appendValue('1')">1</button>
<button onclick="appendValue('+')">+</button>
<button onclick="calculate()">=</button>
<button onclick="clearDisplay()">C</button>
