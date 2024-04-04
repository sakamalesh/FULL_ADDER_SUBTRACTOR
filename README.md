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
## FULL ADDER:
https://images.app.goo.gl/KLKnHsuwatB5a5m7A
## FULL SUBRACTOR:
https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.prepbytes.com%2Fblog%2Fdigital-electronics%2Ffull-subtractor%2F&psig=AOvVaw3T7ddToL8z3HpeAZJ5Vb3C&ust=1712327189624000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCIiwidzhqIUDFQAAAAAdAAAAABAE
**Procedure**

Write the detailed procedure here

**Program:**
Developed by: KAMALESH S
RegisterNumber: 212223040083
## FULL ADDER:
![Screenshot 2024-04-04 195614](https://github.com/sakamalesh/FULL_ADDER_SUBTRACTOR/assets/149148235/bb3196af-a7ae-44bb-89b5-125c6ae7821a)

## FULL SUBRACTOR:
![Screenshot 2024-04-04 194743](https://github.com/sakamalesh/FULL_ADDER_SUBTRACTOR/assets/149148235/51738613-55d4-498e-aa4f-2332d93d8393)


**RTL Schematic**
## FULL ADDER:
![Screenshot 2024-04-04 195631](https://github.com/sakamalesh/FULL_ADDER_SUBTRACTOR/assets/149148235/53e1ec5d-35b3-4eb6-b8b1-0ca860c229e0)

## FULL SUBRACTOR:
![Screenshot 2024-04-04 194802](https://github.com/sakamalesh/FULL_ADDER_SUBTRACTOR/assets/149148235/581167c7-356d-4395-a431-477deaf9f916)


**Output Timing Waveform**
## FULL ADDER:
![Screenshot 2024-04-04 195847](https://github.com/sakamalesh/FULL_ADDER_SUBTRACTOR/assets/149148235/2e5182c4-6e29-4063-b497-51348364609b)

## FULL SUBRACTOR:

![Screenshot 2024-04-04 194840](https://github.com/sakamalesh/FULL_ADDER_SUBTRACTOR/assets/149148235/f4da01bb-bf34-4cf6-8931-1e12ba621a5b)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



