# C++ Code Repository

This repository contains C++ code designed to be compiled and debugged on Windows using Visual Studio Code. The setup includes tasks for compiling and running the code, as well as debugging configurations.

## Prerequisites

- **Windows OS**
- **g++ (GCC)**: Ensure `g++` is installed and added to your PATH.
- **GDB**: Ensure `gdb` is installed and added to your PATH.
- **Visual Studio Code**: Install VS Code with the C++ extension.

## Folder Structure

```
C++ code/
├── basics.cpp       # Example C++ file
├── input.txt        # Input file for testing
├── output.txt       # Output file for results
├── .vscode/
│   ├── tasks.json   # Build and run tasks
│   ├── launch.json  # Debug configurations
```

## How to Run

1. Open the repository folder in Visual Studio Code.
2. Press `Ctrl+Shift+B` to compile and run the code.
   - The program will read input from `input.txt` and write output to `output.txt`.

## How to Debug

1. Open the C++ file you want to debug (e.g., `basics.cpp`).
2. Set breakpoints by clicking on the left margin next to the line numbers.
3. Press `F5` to start debugging.
   - The debugger will launch the program and allow you to step through the code.

## How to Format Code

1. Open the C++ file you want to format (e.g., `basics.cpp`).
2. Press `Shift+Alt+F` to format the code using `clang-format`.
   - Ensure the `.clang-format` file is present in the workspace for custom formatting rules.
3. Alternatively, enable `Format on Save` in VS Code settings to automatically format the code when saving.

## Notes

- This setup is specifically designed for **Windows**.
- Ensure all dependencies are properly installed and configured before running or debugging.
- Modify `input.txt` to provide custom input for your program.
- Check `output.txt` for the program's output after running.