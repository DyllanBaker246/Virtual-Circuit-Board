# Virtual-Circuit-Board
The most up to date version of this project is CPU V.1. Functionality includes:
- adding two values from memory
- storing a value to memory

## CPU OP Code
Current Version: Instruction Decoder V.1
- XXXX XXXX
- OP Code, address
  - LDRA: 0000 (Load Value in address into reg A)
  - LDRB: 0001 (Load Value at address into reg B)
  - STRC: 0010 (Store value in C at address)
  - ADD: 0011 (Adds the values of A and B, stores in C)

## Ram Op code
16 bytes of storage
- XX    XXXX      XXXXXXXX
- r/w, Address, value to be stored (Null of reading)/n
  - read:  10
  - write: 01
