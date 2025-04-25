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


FULL ADDER
![Screenshot 2025-04-25 113454](https://github.com/user-attachments/assets/b0e8a830-4c2b-46c1-b59e-68fb04d4fcc0)
FULL SUBTRACTER
![Screenshot 2025-04-25 113639](https://github.com/user-attachments/assets/161d3903-126f-48b3-9a87-71038fb0fdd3)

**Procedure**

 Full Adder: 1.Open Quartus II and create a new project. 2.Use schematic design entry to
 draw the full adder circuit. 3.The circuit consists of XOR, AND, and OR gates. 4.Compile
 the design, verify its functionality through simulation. 5.Implement the design on the
 target device and program it.
 Full Subtractor: 1.Follow the same steps as for the full adder. 2.Draw the full subtractor
 circuit using schematic design. 3.The circuit includes XOR, AND, OR gates to perform
 subtraction. 4.Compile, simulate, implement, and program the design similarly to the
 full adder

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
*/
FULL ADDER
![Screenshot 2025-04-25 113050](https://github.com/user-attachments/assets/8e8c3876-419b-4aff-a518-cf0ece9b954b)
FULL SUBTRACTOR
![Screenshot 2025-04-25 113312](https://github.com/user-attachments/assets/1176ed81-505b-482d-a46f-83c6ddf9e689)


**RTL Schematic**
![Screenshot 2025-04-25 113755](https://github.com/user-attachments/assets/a2aa24a3-078b-4b09-8d36-c18b3866a05c)



**Output Timing Waveform**
![Screenshot 2025-04-25 113849](https://github.com/user-attachments/assets/a3985fe5-4bda-4532-9a0d-336cb55e9007)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



