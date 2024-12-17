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

![Screenshot 2024-12-17 144359](https://github.com/user-attachments/assets/2672a108-ed42-4ae2-9fda-c896a6ca91ee)

 Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. 
 
 Developed by: ROSHINI A / RegisterNumber: 24002364


**RTL Schematic**

![Screenshot 2024-12-17 144414](https://github.com/user-attachments/assets/e35e0726-ba6b-46a8-8e6f-7baf3585c8f5)
![Screenshot 2024-12-17 144424](https://github.com/user-attachments/assets/f085c131-3df1-4a7d-87df-dc18d111a05c)

**Output Timing Waveform**

![Screenshot 2024-12-17 144440](https://github.com/user-attachments/assets/dd572113-d1b1-4d54-8037-d1a982197810)
![Screenshot 2024-12-17 144500](https://github.com/user-attachments/assets/1821abab-c474-4d8c-9063-204191f83487)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



