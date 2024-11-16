### About the Calculator Project

This project is a simple, responsive calculator built with HTML, CSS, and JavaScript, designed to perform basic arithmetic operations. Its clean design, implemented using Bootstrap 4, ensures usability and modern aesthetics, while JavaScript powers the interactive functionality.

![](move.gif)

---

## Features

1. **Arithmetic Operations**:
   - Supports addition, subtraction, multiplication, division, and decimal operations.
   - Allows sequential calculations without needing intermediate resets.

2. **Clear Functionality**:
   - Includes a "C" button to reset the calculator's display, clearing all input.

3. **Dynamic Display**:
   - The input and calculated results are displayed in real-time on the calculator's screen.

4. **Responsive Design**:
   - The layout adapts to various screen sizes, making it accessible for both desktop and mobile users.

5. **Error-Free Evaluation**:
   - The `eval` function computes mathematical expressions entered into the display. Inputs are validated based on button interactions.

---

## Technical Details

### Technologies Used:
- **HTML5**: Provides the structure for the calculator interface.
- **CSS3**: Custom styles for buttons, display, and overall layout, enhanced with Bootstrap for responsiveness.
- **Bootstrap 4**: Ensures a modern, mobile-first design with consistent styling.
- **JavaScript**: Handles user interactions, performs arithmetic operations, and updates the display dynamically.

### Key JavaScript Features:
1. **Dynamic Input Handling**:
   - Buttons are linked to a `calcular()` function that identifies the input type (`valor` or `acao`) and processes it accordingly.

2. **Calculation Logic**:
   - When users press `=`, the `eval()` function evaluates the entered mathematical expression and displays the result.
   - The code handles operator input (`+`, `-`, `*`, `/`, `.`) by appending them to the display value.

3. **Error Prevention**:
   - The `C` button clears the display to avoid invalid calculations or input errors.
   - The `disabled` attribute prevents manual edits to the display field.

---

## Use Cases

1. **Educational Tool**:
   - Ideal for students learning arithmetic operations or practicing basic math.
   - Demonstrates the principles of responsive web design and JavaScript interactivity.

2. **Standalone Widget**:
   - Can be embedded into other projects, such as financial calculators or dashboards.

3. **Code Study**:
   - Provides an excellent introduction to DOM manipulation, JavaScript event handling, and Bootstrap-based design.

---

## How to Run

1. Open the HTML file directly in a web browser.
2. Interact with the calculator by clicking on the buttons for inputs and operations.
3. Perform calculations and use the clear button (`C`) to reset as needed.

---

## Limitations and Improvements

### Current Limitations:
- The `eval()` function, while simple, poses potential security risks if input is not strictly controlled.
- Does not handle complex calculations or provide error messages for invalid inputs.

### Potential Enhancements:
1. **Validation**:
   - Replace `eval()` with a custom parser for improved security and input validation.
2. **Advanced Features**:
   - Add functionalities like percentage calculations, square roots, or trigonometric operations.
3. **Improved UI/UX**:
   - Include animations or visual feedback when buttons are pressed.
   - Display a history of calculations for user reference.
4. **Accessibility**:
   - Add keyboard support to allow input without mouse interaction.

---

## Conclusion

This project demonstrates the effective use of front-end technologies to build a functional, user-friendly calculator. It serves as a foundation for more advanced projects, combining responsive design principles with JavaScript-driven interactivity.