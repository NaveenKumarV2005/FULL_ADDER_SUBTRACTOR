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
![image](https://github.com/23004426/FULL_ADDER_SUBTRACTOR/assets/144979327/fcdbd408-57a3-4771-89b6-b94543ac1efb)
![image](https://github.com/23004426/FULL_ADDER_SUBTRACTOR/assets/144979327/964b3ae3-ad26-4512-841e-4196875a4e8d)

**Procedure**

Write the detailed procedure here

**Program:**



![Screenshot 2024-04-03 212451](https://github.com/NaveenKumarV2005/FULL_ADDER_SUBTRACTOR/assets/151476286/bda33b29-7fae-4f56-9fd6-693eb87955a0)



**RTL Schematic**
![image](https://github.com/23004426/FULL_ADDER_SUBTRACTOR/assets/144979327/1910862b-efcf-40be-9e0d-3b4b70da275e)

**Output Timing Waveform**
![image](https://github.com/23004426/FULL_ADDER_SUBTRACTOR/assets/144979327/6720023f-9bb3-4425-8c54-8d85c0fdc6df)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



