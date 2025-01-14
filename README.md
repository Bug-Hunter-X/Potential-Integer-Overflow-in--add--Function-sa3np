# Potential Integer Overflow in Solidity `add` Function

This repository demonstrates a potential integer overflow vulnerability in a Solidity function and provides a solution.

## Bug Description
The `add` function in `bug.sol` directly adds two unsigned integers.  If the sum exceeds the maximum value representable by the data type, an integer overflow occurs, leading to unexpected results.

## Solution
The `bugSolution.sol` file provides an improved `add` function that checks for potential overflows before performing the addition. This prevents unexpected behavior and maintains data integrity.

## Usage
1. Clone the repository.
2. Compile and deploy the `bug.sol` and `bugSolution.sol` contracts using a Solidity compiler.
3. Observe the different outcomes with large inputs.
