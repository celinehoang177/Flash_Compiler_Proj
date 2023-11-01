# Flash Compiler (C++)

The Flash Compiler is a lightweight and high-performance programming language compiler implemented in C++. This project aims to deliver a streamlined and efficient compiler while serving as a reference for compiler construction.

## Key Features

- **Simplicity:** Flash has been intentionally kept minimal to provide a solid foundation for comprehending the fundamental concepts of compiler construction.

- **Fast Compilation:** It generates x86-64 assembly code, making it efficient for small to medium-sized programs.

- **User-Friendly Syntax:** Flash adopts a straightforward and intuitive syntax that is accessible to both beginners and experienced programmers.

## Language Features

The Flash Compiler supports a range of essential language features, including:

- Arithmetic expressions
- Variable declarations (utilizing the `let` keyword)
- Conditional statements (leveraging the `if` keyword)
- An `exit` statement for orderly program termination

## Building the Compiler

To compile the Flash Compiler, ensure that you have `nasm` and `ld` installed on a Linux-based operating system. Follow these steps to build the compiler:

```bash
git clone https://github.com/celinehoang177/flash-compiler
cd flash-compiler
mkdir build
cmake -S . -B build
cmake --build build
```

Explore the world of compiler construction with Flash Compiler! Happy coding! 🚀
