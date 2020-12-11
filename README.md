# single-Pass-Assembler
***

INPUT.DAT -> Input file

## STEPS :-

1) Store The Assembly Program In INPUT.DAT and place the input file and onepassassembler.c in same location
2) Run THE PROGRAM onepassassembler.c

***
## Algorithm:
***
STEP 1: Start the program execution.
STEP 2: Assembler simply generate object code as it scans the source code.
STEP 3: If the instruction operand is a symbol text, has not yet been defined, the
operands address is omitted.
STEP 4: When nearly half the program translation is over, some of the forward reference
problem are existed.
STEP 5: Combine the process to the end of the program to fill forward reference
property.
STEP 6: At the end of the program, the symbol table entries with ‘x’ are undefined.
STEP 7: Stop the program execution.
