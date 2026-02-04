# Abstract-Syntax-Tree-AST-Visualization-Analysis-Tool
A Python-based static analysis utility that performs lexical and syntax analysis to visualize code hierarchy and quantify logical complexity using Graphviz.

## Overview
This tool performs **Lexical and Syntax Analysis** to transform source code into a hierarchical tree structure. It is designed to assist in structural auditing and code complexity mapping.

##  Key Features
- **Visual Rendering:** Utilizes `Graphviz` to generate professional-grade logic diagrams of code hierarchy.
- **Complexity Scoring:** Features a recursive algorithm to quantify logic operations (`BinOp`), variable density, and function definitions.
- **Compiler Stage Simulation:** Demonstrates the first two phases of a compiler: Lexical Analysis and Parsing.

##  Sample Output
![AST Tree Output](<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a5978ee1-899b-415c-a9e1-74464e4d27d4" />
))

##  Tech Stack
- **Language:** Python 3.x
- **Libraries:** `ast` (Standard Library), `graphviz`
- **Platform:** Google Colab / VS Code
