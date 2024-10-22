Calculator Application

Description

This project is a simple Calculator application built using Java Swing for the graphical user interface (GUI). The calculator can handle basic arithmetic operations such as addition, subtraction, multiplication, and division. It also supports functionalities like decimal point entry, negation, deletion of the last digit, and clearing the entire input.

Features

Basic Arithmetic: Perform addition, subtraction, multiplication, and division.
Decimal Support: Allows entering and calculating decimal numbers.
Negative Number Handling: Switch between positive and negative values.
Delete Function: Remove the last entered digit.
Clear Function: Clear all the input to start a new calculation.
Responsive GUI: The application layout adjusts based on the calculator buttons and fields.
Prerequisites

Java Development Kit (JDK) version 8 or above.
Any Integrated Development Environment (IDE) that supports Java (e.g., IntelliJ IDEA, Eclipse, or NetBeans).
Installation

Clone the repository or download the project files.
Open the project in your preferred IDE.
Compile and run the Calculator.java file.
bash
Copy code
javac Calculator.java
java Calculator
How to Use

Number Input: Click the number buttons (0-9) to input digits.
Operations: Click the buttons for operations like +, -, x, and /.
Decimal: Use the . button to input decimal values.
Negative Numbers: Toggle between positive and negative values by clicking (-).
Delete: Click Delete to remove the last entered digit.
Clear: Click Clear to reset the input field.
Equal: Click = to evaluate the expression entered.
The result will be displayed in the text field at the top of the calculator.

Code Structure

JFrame: The main window for the calculator.
JTextField: Used to display numbers and results.
JButtons: Includes buttons for numbers, operations, and functions like clear, delete, etc.
JPanel: Contains the buttons in a grid layout for easy access.
ActionListener: Handles button clicks and processes the corresponding operations.
Key Components:
Buttons:
+, -, x, / for basic arithmetic.
. for decimal input.
(-) for toggling between positive and negative.
= for calculating the result.
Delete for removing the last digit.
Clear for clearing the text field.
Text Field:
Displays the entered numbers and the result of calculations.
Action Listener:
Handles all button clicks and performs the required calculations based on the operator selected.
Example

Input: 5 + 3
Output: 8
Sample Workflow
Enter 5.
Click +.
Enter 3.
Click =.
The result 8 will appear in the text field.
Future Enhancements

Advanced Operations: Support for additional functions like square root, power, etc.
Memory Functions: Implement memory recall and storage features.
Enhanced UI: Add themes or styles for a more polished look.
License

This project is open-source. Feel free to use and modify it as needed.