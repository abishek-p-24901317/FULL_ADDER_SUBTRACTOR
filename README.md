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
![397930715-5236ac27-a335-4135-b78a-8db84a4506c7](https://github.com/user-attachments/assets/e7a18841-9549-45be-8356-7eff458fdfc0)
![397930722-bddcce6e-b2b6-4fea-b3f9-2476635ce48c](https://github.com/user-attachments/assets/36f1d1ff-080c-4a70-9a6a-e568a8ffbf3e)

**Procedure**
1.Type the program in Quartus software.
2.Compile and run the program.
3.Generate the RTL schematic and save the logic diagram.
4.Create nodes for inputs and outputs to generate the timing diagram.
5.For different input combinations generate the timing diagram.

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: Abishek P, 24901317
*/
![image](https://github.com/user-attachments/assets/4fee9747-ecbd-47f4-bd69-ae20cedc8862)


**RTL Schematic**
![393247467-6fd71894-673a-4ccc-bf6f-b2b65ee16e18](https://github.com/user-attachments/assets/e57320ad-9a16-45b1-8965-947320c0e21f)
![393247469-371eb82f-6369-48ee-9fa9-b6d2c9a94d7f](https://github.com/user-attachments/assets/3ac85b84-1c83-4ff0-a898-f977eb0828e8)

**Output Timing Waveform**
![393247468-39cbdaa9-7e4f-4c93-b207-3c42cb800bdc](https://github.com/user-attachments/assets/6110cc3d-3062-4bfe-b703-48c9a57053c8)
![393247470-f213dcc6-ddc8-4d99-8da3-d0ea3751b715](https://github.com/user-attachments/assets/ebcee85e-d5aa-4302-947c-5ee2f68a40ee)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



