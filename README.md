# CPS213-Labs
**LOGISIM REQUIRED TO OPEN .CIRC FILES**
CPS 213 Computer Organization Labs
Labs 1 through 5

Lab 5 Explanation
Takes 2 4-bit binary input and results in either LED segment displaying in hexadecimal or 4-bit binary output and other LEDs.

Set Mode bit(M) to 0 for Arithmetic Unit output and Set Mode bit to 1 for Logic unit. Set the Enable bit to 1 for Arithmetic Unit MUX and Set Enable bit to 0 for enabling logic unit MUX. This results in the LED segment only displaying if you want arithmetic unit output and when you select logic unit the LED is off. 

Arithmetic Unit C0 is for output for 4 bit Full Adder(overflow occurs if 1). C1 is the 4-bit subtractor output. Arithmetic Unit selector bits will be 00 for 4 bit addition, 01 for subtractor, 10 for 2's complement of B input and 11 for Incrementing A by 1.

Logic Unit selctor bits are 00 for AND of both inputs, 01 for OR of inputs, 10 for XOR of both inputs and 11 for 1s complement of input A.

The comparator will only have one of the three pins on and that would be for either A is B, B is greater than A or A is greater than B.
