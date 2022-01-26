# MacroTable_TR_to_PrintCh
A working HLASM model showing how to convert from hex into character for display purposes.
1. Uses HEXTBL macro to define a 256-byte table. 
2. MVZ and MVN instructions allow each input byte to be separated into hi order and low order bits.
3. The TR instruction uses the table defined in HEXTBL to obtain a char representation.

Source:  Carmine Cannatello - "Advanced Assembler Language and MVS Interfaces"
