# Bit-Pattern-Maniputation
Programs that manipulate 16 bit words of the LC-3 machine language.

The LC-3 is an educational assembly language.

LC-3 ISA: Address space of 2^16, 8 general purpose registers, [15 instructions](http://users.ece.utexas.edu/~patt/19f.306/Handouts/LC3_Instruction_Set.pdf), 2's complement integer data type, 5 addressing modes.



Instructions to download the LC3 simulator can be found on [Professor Yale Patt's website](http://users.ece.utexas.edu/~patt/19f.306/software.html).

With LC3tools, convert all files to .obj to run

left_shift.bin obtains a bit pattern from x3100 in memory and shifts all bits to the left by a specified amount found in x3101 in memory. It then stores the result in x3102 in memory.

left_rotate.bin obtains a bit pattern from x3100 in memory and rotates all bits to the left by a specified amount found in x3101 in memory. It then stores the result in x3102 in memory.

