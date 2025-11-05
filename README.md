# Virtual-Circuit-Board
Building a CPU

#CPU OP Code
- XXXX XXXX
- OP Code, address
- LDRA: 0001 (Load Value in address into reg A)
- LDRB: 0010 (Load Value at address into reg B)
- STRC: 0011 (Store value in C at address)

# Ram Op code
- XX    XXXX      XXXXXXXX
- r/w, Address, value to be stored (Null of reading)/n
- read:  10
- write: 01
