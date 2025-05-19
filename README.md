# Assembly-Language-Project
An assembly program that converts two-digit octal input to decimal and displays it only if it's a multiple of 3 or 5.

## Description:
In this project I wrote an assembly language program that converts a two digit octal number into its decimal equivalent. The program will then display the results only if the decimal number is a multiple of 3 or 5. Otherwise, it outputs 0. This was completed as part of my Computer Organization project. 

## Author:
Cristiana Eagen

## Built with:
- Custom Assembly Language
- Assembler.jar simulator

## Details:
  - ASCII-to-decimal conversion
  - Octal-to-decimal logic
  - Division using subtraction loops
  - Conditional branching using: `SZA` - Skip if AC is zero, `SNA` – Skip if AC is negative, `SPA` – Skip if AC is positive
  - Used `BSA` to call these two subroutines: CHECKFIVE and CHECKTHREE

## How to run the code:
- Download and open Assembler.jar
- Clone the repository
- Navigate into the src folder → `cd src`
- Load `Assembly_language_program.txt` in the Source Program panel.
- Compile the code: Tools → Compile.
- Enter an octal number in the Input Stream.
- Run the program via Tools → Execute → Run and take a look at the output.

## Example:
- Input: 43 (octal)
- Decimal: 35 → Output: 35
- Input: 10 (octal)
- Decimal: 8 → Not a multiple → Output: 0
