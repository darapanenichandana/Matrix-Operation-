# Matrix Operations Tool

This is a Python-based command-line tool for performing basic matrix operations, including addition, subtraction, multiplication, transposition, and determinant calculation using NumPy.

## Features

- **Addition**: Adds two matrices of the same dimensions.
- **Subtraction**: Subtracts one matrix from another (same dimensions required).
- **Multiplication**: Multiplies two matrices (column count of the first must match row count of the second).
- **Transpose**: Finds the transpose of a given matrix.
- **Determinant**: Calculates the determinant of a square matrix.

## Prerequisites

- Python 3.x
- NumPy library

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/matrix-operations-tool.git
   cd matrix-operations-tool
   ```

2. Install dependencies:
   ```bash
   pip install numpy
   ```

## Usage

Run the script:
```bash
python matrix_operations.py
```

Follow the on-screen instructions to enter matrices and select operations.

## Example Usage

```
Matrix Operations Tool
1. Addition
2. Subtraction
3. Multiplication
4. Transpose
5. Determinant
6. Exit

Choose an operation (1-6): 1
Enter the first matrix:
Enter the number of rows: 2
Enter the number of columns: 2
Enter the elements row-wise (space-separated):
1 2
3 4

Enter the second matrix:
Enter the number of rows: 2
Enter the number of columns: 2
Enter the elements row-wise (space-separated):
5 6
7 8

Result of Addition:
[[ 6.  8.]
 [10. 12.]]
```

## License

This project is licensed under the MIT License.

