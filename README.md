# Design-of-an-HDL-based-32-bit-processor

# Objective :

Design an HDL-based 32-bit processor (Instruction decode (Instruction decoder + controller) + Instruction execute (ALU)+register write (Register
Bank)) which executes the following 10 instructions:
ADD, SUB, SLL, SLT, SLTU, XOR, SRL, SRA, OR, AND
Perform post-synthesis simulations for a basic 32-bit processor which executes the aforementioned instructions. The processor will basically have the
following modules:
a. A 32-bit register bank which will have 32 registers and each register can
store 32-bit data.
b. An instruction decoder module which will slice the 32-bit instructions into
the corresponding fieldsopcode, func and rs1, rs2 and rd values
c. A controller module which will generate a corresponding signal for the
respective operations depending func and opcode.
d. 32-bit ALU for processing the data present in rs1 and rs2 registers.
e. Register write to store the result back into rd register in the register bank.

# NOTE:

1. Initialize the 32 registers present in the register bank, before executing
the instructions.
2. Perform ALU operations on the data present in ‘rs1’ and ‘rs2’ registers.
The result is stored in ‘rd’ register.
