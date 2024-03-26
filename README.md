# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**

**Procedure**

Write the detailed procedure here

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by:SALINI .A RegisterNumber:212223220091
*/

**CODE**

**FULL ADDER:**

![Screenshot 2024-03-26 090151](https://github.com/salinianbzhgan/FULL_ADDER_SUBTRACTOR/assets/145742862/6b1dfe27-2bdc-4cc4-864c-a54bf249b82b)

**FULL SUBTRACTOR:**

![Screenshot 2024-03-26 090200](https://github.com/salinianbzhgan/FULL_ADDER_SUBTRACTOR/assets/145742862/a09ac518-5a57-409b-9257-d4ecfe44f478)

**RTL Schematic**
**FULL ADDER:**

![Screenshot 2024-03-26 090209](https://github.com/salinianbzhgan/FULL_ADDER_SUBTRACTOR/assets/145742862/d55f56c1-dd06-421f-99d5-626f07c5957f)

**FULL SUBTRACTOR:**

![Screenshot 2024-03-26 090218](https://github.com/salinianbzhgan/FULL_ADDER_SUBTRACTOR/assets/145742862/2ae6344e-fb67-436e-8639-01283729bfb2)

**Output Timing Waveform**
**FULL ADDER:**

![Screenshot 2024-03-26 090233](https://github.com/salinianbzhgan/FULL_ADDER_SUBTRACTOR/assets/145742862/3f205a31-f07c-4d25-af3a-e14671af38d5)

**FULL SUBTRACTOR:**

![Screenshot 2024-03-26 090243](https://github.com/salinianbzhgan/FULL_ADDER_SUBTRACTOR/assets/145742862/c349faca-e5b7-4b6c-becf-215bd54e055c)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



