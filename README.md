# Calculator App

## Summary

This is a simple calculator web application built using HTML, CSS, and JavaScript. It allows users to perform basic arithmetic operations like addition, subtraction, multiplication, and division.

## Setup Instructions

To run this application, you need a web browser. Simply clone the repository or download the files and open `index.html` in your browser.  No server is required since it's a purely frontend application.

1.  Clone the repository:
    ```bash
    git clone <repository_url>
    ```
2.  Navigate to the project directory:
    ```bash
    cd <project_directory>
    ```
3.  Open `index.html` in your web browser.

## Usage Guide

1.  **Input:** Use the buttons on the calculator to enter numbers and operators.
2.  **Operators:** The calculator supports the following operators: `+`, `-`, `*`, `/`.
3.  **Decimal Point:** Use the `.` button to enter decimal numbers.
4.  **Clear:** Press the `C` button to clear the display.
5.  **Backspace:** Press the `←` button to remove the last entered character.
6.  **Calculate:** Press the `=` button to calculate the result.
7.  **Error Handling:** If an invalid expression is entered, the display will show "Error".

## Code Explanation

*   **`index.html`:** This file contains the HTML structure of the calculator, including the display input field and the buttons.
*   **`style.css`:** This file contains the CSS styles for the calculator, providing the visual appearance.
*   **`script.js`:** This file contains the JavaScript logic for handling user input, performing calculations, and updating the display.

    *   `appendToDisplay(value)`: Appends the given value to the display string and updates the display.
    *   `clearDisplay()`: Clears the display by resetting the display string.
    *   `backspace()`: Removes the last character from the display string.
    *   `calculate()`: Evaluates the expression in the display string using the `eval()` function and displays the result. It also includes error handling to catch invalid expressions.

The `eval()` function is used for calculation. While convenient, be aware of the security implications of using `eval()` with untrusted input. For more complex or production-critical applications, consider using a safer expression parsing library.