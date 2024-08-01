# Basic Calculator in C - Code Analysis

## Overview

This project implements a basic calculator in C that can perform addition, subtraction, multiplication, and division. The calculator runs in a loop, allowing the user to select an operation and perform calculations until they choose to exit.

## Code Structure

### `calculator.c`

#### Main Function (`main`)

- **Purpose**: Entry point of the program, runs the main loop to prompt user for operation.
- **Functionality**:
  - Runs an infinite loop to prompt the user for an operation choice.
  - Based on the user's choice, calls the corresponding function (`add`, `subtract`, `multiply`, `divide`).
  - Exits if the user chooses `5`.

#### Addition Function (`add`)

- **Purpose**: Computes the sum of two numbers.
- **Functionality**:
  - Prompts the user to enter two numbers.
  - Computes their sum and prints the result.

#### Subtraction Function (`subtract`)

- **Purpose**: Computes the difference between two numbers.
- **Functionality**:
  - Prompts the user to enter two numbers.
  - Computes their difference and prints the result.

#### Multiplication Function (`multiply`)

- **Purpose**: Computes the product of two numbers.
- **Functionality**:
  - Prompts the user to enter two numbers.
  - Computes their product and prints the result.

#### Division Function (`divide`)

- **Purpose**: Computes the quotient of two numbers.
- **Functionality**:
  - Prompts the user to enter two numbers.
  - Checks if the second number is not zero.
  - If not zero, computes their quotient and prints the result.
  - If zero, prints an error message indicating division by zero is not allowed.
