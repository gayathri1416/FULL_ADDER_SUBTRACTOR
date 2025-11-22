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

**Truthtable for Full Adder**

![Full adder](https://github.com/user-attachments/assets/f3a2572b-ba2e-4a8a-abce-98b5a067f089)

**Truth table for Full subtracter**

![Full subtracter](https://github.com/user-attachments/assets/0291360b-cc7e-4a77-9aaa-2869fbb14587)

**Program:**

```
 Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
 Developed by    : GAYATHRI C
 Register Number : 25009125
```

**RTL OUTPUT**

<img width="707" height="642" alt="gate" src="https://github.com/user-attachments/assets/78a07fdb-8c95-4688-bc14-b0f3ea581b76" />


**Output Timing Waveform**

<img width="1336" height="497" alt="Screenshot 2025-11-21 155726" src="https://github.com/user-attachments/assets/a01fa16d-8bd9-4f42-bc0f-2bbfb896c2f0" />

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



