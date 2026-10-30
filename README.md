
# 4-Bit Binary Squarer Using Verilog HDL

## Project Description
The 4-Bit Binary Squarer is a digital circuit designed using Verilog HDL that calculates the square of a 4-bit binary input. It takes a 4-bit input (A) and produces an 8-bit output (Y) representing the square of the input value.

## Features
- 4-bit binary input.
- 8-bit binary output.
- Supports input values from 0 to 15.
- Performs squaring operation using Verilog HDL.
- Verified through simulation using a testbench.

## Input and Output
| Signal | Width | Description |
|---|---|---|
| A | 4-bit | Binary input |
| Y | 8-bit | Square of the input |

## Working Principle
The circuit takes a 4-bit binary number as input and multiplies the number by itself to generate its square.

**Example:**

| Input (A) | Decimal Input | Output (Y) | Decimal Output |
|---|---:|---|---:|
| 0000 | 0 | 00000000 | 0 |
| 0001 | 1 | 00000001 | 1 |
| 0010 | 2 | 00000100 | 4 |
| 0011 | 3 | 00001001 | 9 |
| 0100 | 4 | 00010000 | 16 |
| 1111 | 15 | 11100001 | 225 |

## Tools Used
- Verilog HDL
- Xilinx Vivado
- Simulation Testbench

## Project Files
- `squarer.v` – Design module.
- `squarer_tb.v` – Testbench for verification.

## Simulation
The design is verified by applying all possible 16 input combinations (0 to 15) through the testbench and checking the corresponding squared outputs.

## Applications
- Digital arithmetic circuits.
- Arithmetic logic unit (ALU) design.
- Digital signal processing.
- FPGA-based mathematical computations.

## Conclusion
The 4-Bit Binary Squarer successfully computes the square of all possible 4-bit unsigned binary inputs and produces the corresponding 8-bit output. The functionality is verified through Verilog simulation.
