# Logigram: ANSI Logic Circuit Designer & Generator

A modern, web-based logic circuit designer that supports ANSI/IEEE standard symbols and automatic circuit generation from Boolean expressions.

## Features
- **ANSI/IEEE Standard Symbols**: Realistic gate shapes (AND, OR, NOT, etc.).
- **Logic Expression Parser**: Enter expressions like `F = xz' + y'z` to instantly generate the circuit and truth table.
- **Interactive UI**: Drag nodes, toggle inputs, and view live signal propagation.
- **Auto-Layout**: Intelligently arranges nodes based on the expression structure.
- **Truth Table Generation**: Automatically calculates and displays the truth table for any circuit.

## How to Run
This project is built using React and Babel Standalone, so it doesn't require any complex installation. You just need a simple web server.

1. Clone this repository.
2. Open a terminal in the project directory.
3. Run a simple web server (e.g., using Python):
   ```bash
   python3 -m http.server 8000
   ```
4. Open [http://localhost:8000](http://localhost:8000) in your browser.

## Expression Syntax
- **Input Variables**: Single letters (e.g., `x`, `y`, `z`).
- **Negation**: Suffix `'` (e.g., `z'`).
- **AND**: Juxtaposition or concatenation (e.g., `xz`).
- **OR**: Plus symbol `+`.
- **Assignment**: Use `F = ...` to name the output.

## License
MIT
