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

![image](https://github.com/user-attachments/assets/a3b0fef8-f862-47c8-9a38-68b354ce354d)
![image](https://github.com/user-attachments/assets/7d0238ea-220f-49c4-af8b-ed5d62291d34)



**Procedure**

Write the detailed procedure here

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by:T Isaac Raja

Register Number: 24900178
*/

![image](https://github.com/user-attachments/assets/ab7227e5-7300-4fdd-b6a1-08279863cd91)
![image](https://github.com/user-attachments/assets/968afeea-5ce3-4961-9980-da6da952690b)



**RTL Schematic**

![image](https://github.com/user-attachments/assets/58bdb3c0-14f4-41ae-8dc0-38164662ba5a)
![image](https://github.com/user-attachments/assets/1e836b2a-ff6d-4191-a008-9faa9a12dd29)



**Output Timing Waveform**

![image](https://github.com/user-attachments/assets/8a6caa1f-fefa-41f2-91d0-5524e42e1b4c)
![image](https://github.com/user-attachments/assets/3bdd1505-4ca2-4f73-85e9-f77bfccc6d18)



**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



