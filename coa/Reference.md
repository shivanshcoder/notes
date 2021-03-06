## Common Opcode abbreviation examples

Abbreviation | Function
--|--
#ADD | Add
#SUB | Subtract
#MUL | Multiply
#DIV | Divide
#LOAD | Load data from memory
#STOR | Store data to memory

## Common Symbols for instructions memory locations
Abbreviation | Function
--|--
#LOC|Some arbitrary memory location
#R1|Register 1
#R2|Register 2
#R3|Register 3
#R4|Register 4
#R5|Register 5
#R6|Register 6
#R7|Register 7


## Register Transfer Notation (#RTN)
#Register_Transfer_Notation

Examples:
 > #R2 <- [#LOC] : Contents of memory Location LOC are transferred into R2 register
 
 > #R4 <- [#R2] + [#R3] : Add the contents of #R2 and #R3 