# Basic-mathematics-Calculator

A basic calculator is a device designed to perform fundamental arithmetic operations: addition, subtraction, multiplication, and division. These calculators are typically simple in design and easy to use, making them suitable for everyday calculations like balancing a checkbook or figuring out tips according to Moglix
A basic mathematics calculator built using HTML, CSS, and JavaScript functions as an interactive web application that performs fundamental arithmetic operations.
HTML (Structure):
The HTML file (index.html) defines the calculator's layout. This includes:
A display area, typically an input field, to show numbers and results.
Buttons for digits (0-9).
Buttons for basic arithmetic operators (+, -, *, /).
Buttons for special functions like "equals" (=) and "clear" (C or AC).
The overall arrangement of these elements is often achieved using div containers and potentially table elements for a structured grid layout.
CSS (Styling):
The CSS file (style.css) dictates the visual appearance of the calculator. This involves:
Styling the display area (e.g., background color, font size, text alignment).
Styling the buttons (e.g., size, color, hover effects, borders, text alignment).
Arranging the layout of the calculator using properties like display: grid or flexbox for responsive design.
Ensuring the calculator is visually appealing and user-friendly.
JavaScript (Functionality):
The JavaScript file (script.js) provides the calculator's interactive logic:
Event Listeners: Attaches event listeners to the buttons to detect clicks.
Input Handling: Captures button clicks (numbers and operators) and appends them to the display area.
Calculation Logic: Parses the mathematical expression entered by the user.
Evaluation: Performs the arithmetic calculation based on the operators and numbers.
Display Update: Updates the display area with the result of the calculation or the current input.
Clear Functionality: Implements a function to clear the display and reset the calculator.
