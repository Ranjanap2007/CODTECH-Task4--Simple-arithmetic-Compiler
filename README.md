Name: Ranjana P
Company: CODTECH IT SOLUTION
ID: CT08FPL
Domain: C++ Programming
Duration: 20 December 2024 to 20 January 2025
Mentor: Santhosh N

Overview of the Program

The provided program is a basic arithmetic expression evaluator written in C++. It allows users to input mathematical expressions involving integers, basic operators (+, -, *, /), and parentheses. The program parses and evaluates the input while respecting operator precedence and handling errors.


---

Key Features

1. Expression Parsing:

The program breaks down an expression into smaller components:

Factors: Numbers or sub-expressions in parentheses.

Terms: Handles multiplication and division (*, /).

Expressions: Handles addition and subtraction (+, -).


Operator precedence is maintained using separate parsing methods.



2. Error Handling:

Detects and reports issues such as:

Invalid characters.

Missing or mismatched parentheses.

Unexpected input after the expression.




3. Recursive Evaluation:

Parses expressions recursively to process parentheses and nested operations.



4. Whitespace Handling:

Ignores extra spaces or tabs within the input.



5. Interactive Input:

The program prompts the user to enter an expression, evaluates it, and prints the result.





---

Program Flow

1. Input Expression:

The user enters a mathematical expression, e.g., 3 + 5 * (2 - 8).



2. Expression Parsing:

The input string is parsed character by character:

Numbers are identified and converted to integers.

Operators are processed according to precedence.

Parentheses are handled to override precedence rules.




3. Expression Evaluation:

The program evaluates the parsed expression using recursive parsing.



4. Output Result:

The final result is displayed to the user.



5. Error Handling:

If the input is invalid (e.g., missing parentheses or unexpected characters), the program reports the error.





---

Example Workflow

Input:

3 + 5 * (2 - 8) / 2

1. The program splits the input into components:

3 (number)

+ (operator)

5 * (2 - 8) / 2 (sub-expression).



2. Sub-expression evaluation:

2 - 8 = -6

5 * -6 = -30

-30 / 2 = -15.



3. Final evaluation:

3 + (-15) = -12.




Output:

Result: -12


---

Use Cases

Learning: A great starting point for understanding compiler design principles like parsing and evaluation.

Calculator Development: Serves as a foundation for creating a command-line calculator.

Problem Solving: Can be extended to handle floating-point numbers, advanced operators (e.g., ^ for exponents), and functions like sin, cos, etc.



---

Limitations

Only supports integers; does not handle floating-point numbers.

Limited to basic operators (+, -, *, /).

Does not handle advanced math functions (e.g., trigonometry, logarithms).

Error messages are basic and could be improved.


This program is an excellent way to demonstrate the principles of parsing and evaluating arithmetic expressions in a simple, structured manner.

![image](https://github.com/user-attachments/assets/bf66803d-ec87-4939-aaa2-c888e27fa29c)

![image](https://github.com/user-attachments/assets/ac4752fa-bb4c-4748-949f-4a7627304c11)

![image](https://github.com/user-attachments/assets/d5adb4d7-79f3-4a79-87c9-5ef6df9945f1)


