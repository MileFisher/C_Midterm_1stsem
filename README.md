# Programming Methodology Midterm Project (Semester 1/2023-2024)

## Overview
This project is a command-line calculator implemented in C for the Programming Methodology midterm exam (Semester 1/2023-2024). It reads mathematical expressions from an `input.txt` file, performs the specified operations, and writes the results to an `output.txt` file. The program supports a variety of operations, including basic arithmetic, statistical calculations, and sequence transformations.

## Features
- **Basic Arithmetic**: Addition (+), subtraction (-), multiplication (*), division (/), power (^), and remainder (%).
- **Statistical Operations**: Average (avg), minimum (min), maximum (max).
- **Summation**: Sum of odd or even numbers up to a given n (sum odd, sum even).
- **Prime Counting**: Count prime numbers in a list (count).
- **Binary Conversion**: Convert decimal to binary (dec2bin).
- **Sequence Mapping**: Double values (map double), square values (map square), absolute values (map absolute).
- Handles invalid inputs with "error" output.

## Requirements
- **Language**: Written in C (not C++).
- **Compiler**: Must compile with `gcc` in a Unix-like environment.
- **Input/Output**: Reads from `input.txt` and writes to `output.txt` in the same directory as the source code.
- **Constraints**:
  - Parameters must be within [-100, 100].
  - Maximum 10 parameters for operations accepting multiple inputs.
  - No extra spaces or invalid tokens allowed in input.

## Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/milefisher/C_Midterm_1stsem
   cd C_Midterm_1stsem
