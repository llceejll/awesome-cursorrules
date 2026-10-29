# C++ Programming Guidelines for Cursor AI

This `.cursorrules` file provides comprehensive guidelines and best practices for C++ development when using Cursor AI. It helps maintain consistent, high-quality code across C++ projects by standardizing naming conventions, coding patterns, and other important aspects of C++ programming.

## File Pattern Matches

This `.cursorrules` file is designed to work with the following file patterns:

- `*.cpp` - C++ source files
- `*.h` - C/C++ header files
- `*.hpp` - C++ header files (alternative extension)
- `*.cxx` - C++ source files (alternative extension)
- `*.cc` - C++ source files (alternative extension)
- `*.c` - C source files (if the project mixes C and C++)
- `CMakeLists.txt` - CMake build configuration files
- `*.cmake` - CMake script files
- `Makefile` - Make build files

## Key Features

- Comprehensive naming conventions for variables, functions, classes, and files
- Best practices for function design and implementation
- Guidelines for class structure and organization
- Memory management recommendations using modern C++ features
- Project structure organization
- Standard library usage guidelines
- Concurrency and multithreading best practices

## Usage

Copy this file into `.cursor/rules` as an `.mdc` rule in your C++ project. If it has no frontmatter, set the rule type to Always Apply, which [Cursor's rules help](https://cursor.com/help/customization/rules) describes as the match for the legacy root `.cursorrules` file. 