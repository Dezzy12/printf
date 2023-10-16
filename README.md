Hello there welcome to our 

# Custom printf Implementation in C

This is a school project that involves writing a custom `printf` function in C. The project consists of multiple tasks, each aimed at implementing specific features and conversion specifiers.

## Project Overview

The goal of this project is to implement a custom `printf` function that mimics the behavior of the standard `printf` from the C standard library but with some added functionality.

## Tasks

### Task 0

- Write a function that produces output according to a given format.

### Task 1

- Handle the conversion specifiers `%d` and `%i`.

### Task 3

- Handle the conversion specifiers `%u`, `%o`, `%x`, and `%X`.

### Task 4

- Use a local buffer of 1024 characters to minimize calls to the `write` function.

### Task 5

- Handle a custom conversion specifier `%S` to print strings.
- Non-printable characters (ASCII values between 0 < ASCII < 32 or >= 127) are printed as `\x` followed by the ASCII code value in hexadecimal (always in upper case and two characters).

### Task 6

- Handle the conversion specifier `%p`.

### Task 7

- Handle flag characters for non-custom conversion specifiers:
  - `+`
  - `space`
  - `#`

### Task 8

- Handle length modifiers for non-custom conversion specifiers:
  - `l`
  - `h`

### Task 9

- Handle field width for non-custom conversion specifiers.

### Task 10

- Handle precision for non-custom conversion specifiers.

### Task 11

- Handle the `0` flag character for non-custom conversion specifiers.

### Task 12

- Handle the `-` flag character for non-custom conversion specifiers.

### Task 13

- Handle a custom conversion specifier `%r` to print reversed strings.

### Task 14

- Handle a custom conversion specifier `%R` to print rot13'ed strings.

### Task 15

- Ensure that all the above options work well together.

## Conclusion

This project aims to develop a feature-rich and versatile `printf` implementation that meets the requirements specified in the tasks. It's an excellent opportunity to explore and practice various aspects of C programming and string manipulation.
