# Custom Compiler Design

This repository showcases the Custom Compiler Design project developed as part of the "Compiler Design" course. The project is focused on creating a custom compiler capable of performing lexing, parsing, and translating a proprietary language into intermediate C code. The implementation relies on PLY (Python Lex-Yacc) and Python programming language.

## Project Overview

- **Goal:** Design and implement a custom compiler for lexing, parsing, and translating a proprietary language into intermediate C code.
- **Implementation:** The project is developed using PLY (Python Lex-Yacc) and Python programming language.
- **Course:** Compiler Design
- **Professor:** Dr. Momtazi

## Features

The custom compiler includes the following key features:

- **Lexical Analysis (Lexing):** Tokenizes the input source code into meaningful tokens.
- **Parsing:** Builds a syntax tree to analyze the structure of the source code.
- **Translation:** Translates constructs of the proprietary language into intermediate C code.
- **Backpatching:** Utilizes backpatching to efficiently resolve unresolved branches in the code.

## Workflow

1. Input source code written in the proprietary language is passed through the lexer.
2. The parser constructs a syntax tree based on the lexed tokens.
3. The compiler translates proprietary language constructs into intermediate C code.
4. Backpatching is applied to efficiently resolve unresolved branches in the code.

## Usage

To explore this project:

1. Clone the repository: `git clone https://github.com/leilibrk/Compiler-Design.git`
2. Review the code for the lexer, parser, and translation process.
3. Experiment with running the provided examples of the proprietary language to observe the translation process.


## Acknowledgments

We express our gratitude to Dr. Momtazi for guiding us through the Compiler Design course and motivating us to build a custom compiler capable of translating a proprietary language into intermediate C code.

## Contributing

Contributions to this repository are welcome! If you have ideas for enhancing the compiler, improving the translation process, optimizing the parser, or any other improvements, feel free to fork the repository and submit pull requests.
