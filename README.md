# 16-bit-Processor-
16-bit Processor using 2-address format for Immediate addressing mode Logisim file

Design and simulation of a processor, which can perform Load/Store, Arithmetic & Logical operations on a set of data. Design for a Harward Architecture, separate code memory & separate data memory to store program instructions and operands respectively. Including all the control & status registers like PC (to hold address of instruction), MAR (to hold the memory address), MBR (to hold the data from memory), PSW (to hold status of condition codes)  and IR (to decode the instruction). Also including a Register file of 16 Registers (R0—R15). Include a data memory and code memory of suitable size. 

Functionalities:

•	Fetch the instruction using the contents of PC and update PC

•	Decode the instruction from IR

•	Fetch the operands (wherever applicable)

•	Execute the operation

•	Write the result back in the destination (wherever applicable)

Instruction Set
| Inst.No |	Opcode	| Operation |
| ------- | ------- | --------- |
|    1    |	 0000   |	  Load   |
|2|	0001|	Store|
|3	|0010	|Add|
|4	|0011	|Subtract|
|5	|0100	|Multiply|
|6	|0101	|Divide|
|7	|0110	|Increment|
|8	|0111	|Decrement|
|9	|1000	|And|
|10	|1001	|Or|
|11	|1010	|Not|
|12	|1011	|Exchange|
|13	|1100	|Shift Right|
|14	|1101	|Shift Left|
|15	|1110	|Rotate right|
|16	|1111	|Rotate left|

