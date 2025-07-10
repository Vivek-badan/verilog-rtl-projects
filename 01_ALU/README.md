# 4-Bit ALU using Verilog

## Overview
This project implements a 4-bit Arithmetic and Logic Unit (ALU) in Verilog.  
It performs operations like ADD, SUB, AND, OR, XOR, and NOT based on a 3-bit opcode.

##  ALU Operations

| Opcode | Operation | Description      |
|--------|-----------|------------------|
| 000    | ADD       | A + B            |
| 001    | SUB       | A - B            |
| 010    | AND       | A & B            |
| 011    | OR        | A | B            |
| 100    | XOR       | A ^ B            |
| 101    | NOT       | ~A               |

## Inputs and Outputs

- **Inputs:**
  - `A[3:0]`: First 4-bit input
  - `B[3:0]`: Second 4-bit input
  - `opcode[2:0]`: Selects the operation

- **Output:**
  - `result[3:0]`: Output of the selected operation

## Testbench
A testbench is written to verify all operations. It prints input and output values and can be run using ModelSim or [EDA Playground](https://edaplayground.com/).

