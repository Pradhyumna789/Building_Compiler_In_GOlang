## Getting Started

To get started with the Building_Compiler_In_GOlang project, follow these steps:

### Clone the repository:
- git clone https://github.com/Pradhyumna789/Building_Compiler_In_GOlang.git

### Navigate to the project directory:
- cd Building_Compiler_In_GOlang

### Build and run the interpreter:
- go build
./Building_Compiler_In_GOlang


## Note - Still in development 

## Features:

### The project is divided into two main components:

1. **Interpreter**: The interpreter is being developed following the principles outlined in Thorsten Ball's book "Writing An Interpreter In Go". It covers the implementation of a simple programming language from parsing to evaluation.

2. **Compiler**: The compiler component focuses on translating the source code into machine-readable instructions. This part is influenced by the same book and extends the understanding of building a language by compiling it to bytecode.

### Interpreter

- **Lexical Analysis**: Tokenization of source code to break it into meaningful units.
- **Syntax Parsing**: Creation of an abstract syntax tree (AST) from the tokenized source code.
- **Evaluation**: Interpretation of the AST to execute the program.

### Compiler

- **Lexical Analysis**: Tokenization of source code for further processing.
- **Parsing**: Conversion of tokenized code into an intermediate representation.
- **Code Generation**: Transformation of the intermediate representation into bytecode.
- **Execution**: Interpretation or execution of the generated bytecode.

