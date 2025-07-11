# Sudoku Solver

A C++ console application to solve Sudoku puzzles using a backtracking algorithm. This project allows you to input puzzles manually or load them from a file, and provides detailed feedback and statistics on the solving process.

## Features
- **Interactive Console Menu**: User-friendly interface to guide you through puzzle input and solving steps.
- **Flexible Input**: Enter Sudoku puzzles manually or load from a file.
- **Robust Validation**: Ensures all inputs are within valid ranges and provides helpful error messages.
- **Backtracking Solver**: Efficiently solves puzzles using recursion and backtracking.
- **Statistics**: Displays the number of recursive calls made during solving.

## How to Use
1. **Compile the Project**
   - Use any C++ compiler (e.g., g++, MSVC, etc.).
   - Example (using g++):
     ```sh
     g++ -o sudoku_solver "Sudoku Solver.cpp"
     ```
2. **Run the Program**
   - Execute the compiled binary:
     ```sh
     ./sudoku_solver
     ```
3. **Input the Puzzle**
   - Choose to enter the puzzle manually or by reading from a file.
   - **Manual Input**: Enter each cell value as prompted. Use `0` for empty cells.
   - **File Input**: Provide a file containing 81 numbers (separated by spaces), with `0` for empty cells. The file must be in the same directory as the executable, and the filename should not exceed 20 characters.

## Example Puzzle File
```
5 3 0 0 7 0 0 0 0
6 0 0 1 9 5 0 0 0
0 9 8 0 0 0 0 6 0
8 0 0 0 6 0 0 0 3
4 0 0 8 0 3 0 0 1
7 0 0 0 2 0 0 0 6
0 6 0 0 0 0 2 8 0
0 0 0 4 1 9 0 0 5
0 0 0 0 8 0 0 7 9
```

## Project Structure
- `Sudoku Solver.cpp`: Main source file containing all logic and classes (`SudokuGrid` and `SudokuSolver`).
- `README.md`: Documentation and usage guide (this file).

## Credits
- Developed by Ahmad Mujtaba.
- Special thanks to all contributors and users providing feedback.

---
*Last updated: July 11, 2025*
