# Copilot Instructions for Arithmetic Project

## Project Overview
This is a simple Python project for performing basic arithmetic operations (addition, subtraction, multiplication, division) via a command-line interface. The project consists of two main files:

- `arithmetic_operations.py`: Contains the core logic for arithmetic operations.
- `main.py`: Handles user input and displays results using the logic from `arithmetic_operations.py`.

## Architecture & Data Flow
- User input is collected in `main.py`.
- The function `perform_operation` (in `arithmetic_operations.py`) is called with two numbers and an operation string.
- Supported operations: `add`, `subtract`, `multiply`, `divide`.
- Division by zero is handled with an error message.

## Developer Workflows
- **Run the program:**
  ```powershell
  python main.py
  ```
- **No external dependencies**: Only standard Python is required.
- **No tests or build scripts**: There are currently no automated tests or build steps.

## Project-Specific Patterns
- All arithmetic logic is centralized in `perform_operation`.
- Error handling for invalid operations and division by zero is done via string error messages.
- Inputs are always cast to `float` for calculations.
- Operation names are expected in lowercase (`add`, `subtract`, `multiply`, `divide`).

## Extending the Project
- To add new operations, update `perform_operation` in `arithmetic_operations.py`.
- For more robust error handling, consider raising exceptions instead of returning error strings.
- To add tests, create a new file (e.g., `test_arithmetic_operations.py`) and use `unittest` or `pytest`.

## Example Usage
```
Enter the first number: 5
Enter the second number: 2
Enter the operation (add, subtract, multiply, divide): divide
Result: 2.5
```

## Key Files
- `arithmetic_operations.py`: Arithmetic logic
- `main.py`: CLI interface

---
For questions or improvements, update this file to guide future AI agents.
