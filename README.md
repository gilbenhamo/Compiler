# C-Like Language Compiler for Linux

The C-Like Language Compiler is a compiler implementation for a C-like programming language, specifically designed for the Linux environment.
It is built using YACC, LEX, and C, providing a powerful toolset for translating high-level code written in the C-like language into almost executable machine code on Linux systems.

## Features

- Lexical Analysis: Utilizes LEX to tokenize the source code, identifying keywords, identifiers, operators, and other language elements.
- Syntax Parsing: Utilizes YACC to parse the tokenized code according to the language's grammar rules, ensuring syntactic correctness.
- Semantic Analysis: Performs semantic checks to enforce language-specific rules, type checking, and symbol table management.
- Intermediate Code Generation: Translates the parsed code into an intermediate representation (3-AC) and preparing for optimization and code generation.

## Usage

    1. Ensure YACC, LEX, and a C compiler are installed on your Linux machine.
    2. Clone this repository to your local machine.
    3. Navigate to the compiler's directory.
    4. Run the build command to compile the source code and generate the compiler executable.

## Author

- [Gil Ben Hamo](https://github.com/gilbenhamo)

