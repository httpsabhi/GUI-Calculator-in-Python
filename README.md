# GUI-Calculator-in-Python
This Python code generates a straightforward calculator using the tkinter module. The calculator features buttons for each digit and buttons for parentheses, a clear button, and arithmetic operations (+, -, *, and /). The outcome is shown in a Text widget.

Three functions are specified in the code:
add_to_calc: adds the pressed button's symbol to the calculator's input.
evaluate_calc: evaluates the calculator's input and displays the result in the Text widget.
clear_field: clears the calculator's input and the Text widget.

Also, the code generates a tkinter window and specifies its size and title. It generates numerous Button widgets for each digit, mathematical operations, parentheses, clear, and equals, as well as a Text widget to display the outcome.

When a button is pressed, it uses lambda functions to call the associated function, passing the button's symbol as an argument. The button may remember its value when it is pressed because the lambda function records the symbol's value at the time the button is generated.

The tkinter main loop is then executed by the code to show the window and process user input.

Overall, this code serves as a decent illustration of how to utilize the Python tkinter package to build a straightforward calculator with a graphical user interface.
