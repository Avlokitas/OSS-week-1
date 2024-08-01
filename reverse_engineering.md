# Simple Calculator in C

## Project Structure

The project is organized into the following files:

- **`calculator.c`**: Contains the main implementation of the calculator. This file includes:
  - The `main()` function, which is the entry point of the program. It manages user input and calls appropriate functions based on user choices.
  - Definitions for arithmetic functions such as `add()`, `subtract()`, `multiply()`, and `divide()`.

- **`calculator.h`**: Contains declarations of functions used in the project. This header file includes:
  - Function prototypes for the arithmetic operations: `add()`, `subtract()`, `multiply()`, and `divide()`.

## File Descriptions

### `calculator.c`
- **`main()` Function:**
  - Initializes the program, handles user input, and calls arithmetic functions.
  
- **Arithmetic Functions:**
  - `int add(int a, int b)`: Returns the sum of `a` and `b`.
  - `int subtract(int a, int b)`: Returns the difference between `a` and `b`.
  - `int multiply(int a, int b)`: Returns the product of `a` and `b`.
  - `float divide(int a, int b)`: Returns the quotient of `a` divided by `b`. Includes error handling for division by zero.

### `calculator.h`
- **Function Declarations:**
  - `int add(int a, int b);`
  - `int subtract(int a, int b);`
  - `int multiply(int a, int b);`
  - `float divide(int a, int b);` (Note: `float` is used for division to handle fractional results.)

## Code Flow

1. **Initialization:**
   - The `main()` function starts and prompts the user for input.
   
2. **User Interaction:**
   - The program reads the user's choice and corresponding operands.
   - Based on the user’s choice, it calls the appropriate arithmetic function.
   
3. **Function Execution:**
   - Each arithmetic function performs its operation and returns the result.
   - The result is then displayed to 
