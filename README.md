# Single-Pass-Assembler


INPUT.DAT -> Input file

## STEPS :-

1) Store The Assembly Program In INPUT.DAT and place the input file and onepassassembler.c in same location
2) Run THE PROGRAM onepassassembler.c

***
## Algorithm :-

STEP 1: Start the program execution.<br>
STEP 2: Assembler simply generate object code as it scans the source code.<br>
STEP 3: If the instruction operand is a symbol text, has not yet been defined, the
operands address is omitted.<br>
STEP 4: When nearly half the program translation is over, some of the forward reference
problem are existed.<br>
STEP 5: Combine the process to the end of the program to fill forward reference
property.<br>
STEP 6: At the end of the program, the symbol table entries with ‘x’ are undefined.<br>
STEP 7: Stop the program execution.<br>
