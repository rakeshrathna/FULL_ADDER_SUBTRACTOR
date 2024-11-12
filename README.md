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
![Screenshot 2024-11-05 151544](https://github.com/user-attachments/assets/12b4eb0e-6255-40ec-bc6d-14b6d32be2ef)
![Screenshot 2024-11-05 151611](https://github.com/user-attachments/assets/6104a3e6-7825-4e0c-ac10-a3b57e82155a)


**Procedure**
```

Type the program in Quartus software.

Compile and run the program.

Generate the RTL schematic and save the logic diagram.

Create nodes for inputs and outputs to generate the timing diagram.

For different input combinations generate the timing diagram
```



**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by:RAKESH RATHNA

RegisterNumber:24900592
*/

**RTL Schematic**
![exp4](https://github.com/user-attachments/assets/ba0cefb8-eac3-484f-899a-6f0523a643fb)
![exp5](https://github.com/user-attachments/assets/5b8e0f26-1337-4d34-92f6-c5b8ba2b7bca)



**Output Timing Waveform**

![Screenshot 2024-11-12 131617](https://github.com/user-attachments/assets/d6e7d2fd-68d2-465a-bada-722bb586d3cf)

![Screenshot 2024-11-12 131825](https://github.com/user-attachments/assets/ff6bb836-1be7-44c7-929f-4e17025c591e)



**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



