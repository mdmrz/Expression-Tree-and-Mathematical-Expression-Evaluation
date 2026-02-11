# Expression-Tree-and-Mathematical-Expression-Evaluation
Converts infix expressions to postfix, constructs an Expression Tree, and recursively calculates the result using custom Stack and Tree implementations in Python.

📖 Description

A Python console application that builds an **Expression Tree** from an infix mathematical expression and evaluates it.  
The project converts infix expressions to postfix, constructs a tree from the postfix expression, and recursively calculates the result.  
Custom Stack and Tree implementations are used without relying on built-in Python data structures like `list`, `dict`, or `set`.

 🛠 Features
 
● Convert **infix expressions** to **postfix** notation

● Build an **Expression Tree** from the postfix expression

● Recursively **evaluate** the expression using the tree

● Supports operators: `+`, `-`, `*`, `/`

● Handles parentheses in expressions

● Console-based application

 🏗 Data Structures Used
 
● **Expression Tree Node**:
  - `value` (operator or number)
  - `left` child
  - `right` child
● **Custom Stack** for infix-to-postfix conversion
● Recursive tree traversal for evaluation

▶ How to Run

1. Clone the repository or download the files  
2. Navigate to the project folder in terminal  
3. Run the main Python file:
python main.py

💬 Example

Input:

(3 + 5) * (2 - 1)

Output:

Postfix Expression: 3 5 + 2 1 - *
Result: 8

👨‍💻 Author

Mohammadreza Shafaghati Yekta

Computer Engineering Student
University of Guilan
