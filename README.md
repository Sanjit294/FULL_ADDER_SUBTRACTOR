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

![WhatsApp Image 2024-11-28 at 11 15 03_ebf5ca59](https://github.com/user-attachments/assets/da8631c0-f2eb-4138-beff-c923adaf5fbf)


**Procedure**

Type the program in Quartus software.

1.Compile and run the program.

2.Generate the RTL schematic and save the logic diagram.

3.Create nodes for inputs and outputs to generate the timing diagram.

4.For different input combinations generate the timing diagram.

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. 
Developed by: Sanjit A RegisterNumber: 24005054

![Screenshot 2024-11-28 105809](https://github.com/user-attachments/assets/47c65ec7-22e2-4bb9-8fb3-b5b47170c7a2)

*/

**RTL Schematic**

![Screenshot 2024-11-28 105854](https://github.com/user-attachments/assets/3d617b8d-c0e9-48fd-b20d-ddc45fc47b1b)


**Output Timing Waveform**

![Screenshot 2024-11-28 105752](https://github.com/user-attachments/assets/3345c9cf-25c2-43ee-9325-7ab9a0d92ba3)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



