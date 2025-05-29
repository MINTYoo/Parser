# CS351 Final Project - Lexer and Parser

A Python-based lexical analyzer and parser with a graphical user interface that visualizes parse trees.


## Prerequisites
- Python 3.x
- Graphviz (for parse tree visualization)

## Installation

1. Install Python dependencies:
```bash
pip install graphviz
```

2. Install Graphviz:
   - Download from: https://graphviz.org/download/
   - Choose the Windows 10 (and later) Package
   - Run the installer
   - Make sure to check "Add Graphviz to the system PATH for all users" during installation

## Running the Program

1. Navigate to the project directory:
```bash
cd CS351Final
```

2. Run the program:
```bash
python FinalProject.py
```

## Usage

The program provides a graphical interface where you can:

1. Enter code statements in the text area
2. Click "Advance" to process each statement
3. View the parse tree visualization
4. Use "Reset" to clear the input and start over

## Supported Syntax

The parser supports the following types of statements:

1. Variable Declarations:
```
int x = 5;
float y = 3.14;
```

2. If Statements:
```
if (x > 5)
if (y < 10)
```

3. Print Statements:
```
print("Hello World");
print("Testing");
```

4. Math Expressions:
```
x = 5 + 3;
y = x * 2;
```

## Error Handling

The parser will display error messages for:
- Invalid syntax
- Missing semicolons
- Incorrect statement structure
- Unexpected end of input
- Invalid operators or operands

## Parse Tree Visualization

The program generates a visual representation of the parse tree for each valid statement, showing:
- Expression structure
- Operator precedence
- Statement hierarchy

## Example Usage

1. Start the program
2. Enter a statement (e.g., `int x = 5;`)
3. Click "Advance"
4. View the parse tree visualization
5. Enter another statement or click "Reset" to start over

## Troubleshooting

If you encounter the error "You must install Graphviz and add it to your PATH":
1. Ensure Graphviz is installed
2. Verify Graphviz is in your system PATH
3. Restart your terminal/IDE
4. Run the program again
