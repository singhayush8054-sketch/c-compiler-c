# c-compiler-c

A simple and educational C compiler written from scratch in C.

## Architecture
- **Lexical Analyzer:** Tokenizes the source code into manageable chunks.
- **Syntax Parser:** Generates an Abstract Syntax Tree (AST) for code analysis.
- **Code Generator:** Translates the AST into executable machine code.

## Key Features
- Supports basic C syntax and control structures
- Educational reference for compiler design
- Minimal dependencies

## Benchmarks
- Compiles simple C programs in < 100ms.

## Usage
```bash
make
./c-compiler input.c
```

## Roadmap
- [ ] Support pointer arithmetic
- [ ] Add optimization passes for generated assembly
