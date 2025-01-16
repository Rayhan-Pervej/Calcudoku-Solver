# Calcudoku Solver

## What is Calcudoku?

Calcudoku, also known as KenKen, is a logic-based numerical puzzle that combines elements of Sudoku and arithmetic. The goal is to fill an \(n \times n\) grid with numbers ranging from 1 to \(n\) while satisfying specific mathematical and positional constraints.

## Rules of Calcudoku

### Row and Column Constraints:
- Each number from 1 to \(n\) must appear exactly once in every row and every column.

### Cage Constraints:
- The grid is divided into outlined regions, called **cages**. Each cage has a target number and a mathematical operation (e.g., addition, subtraction, multiplication, or division). The numbers in the cells of the cage must:
  1. Satisfy the given operation to reach the target.
  2. Be unique within the cage.

### Operations:
- **Addition (+)**: The numbers in the cage must sum up to the target number.
- **Subtraction (-)**: For a two-cell cage, the difference between the larger and smaller number must equal the target.
- **Multiplication (×)**: The numbers in the cage must be multiplied by the target number.
- **Division (÷)**: For a two-cell cage, the quotient of the larger number divided by the smaller must equal the target.

## Example Problem and Solution:

![Calcudoku Example](img.png)
*Figure: Example Calcudoku problem (size: 650 x 360).*
