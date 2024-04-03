# HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by:KANAGAVEL.R

RegisterNumber:212223040085

**CODE**

**HALF ADDER**

![Screenshot 2024-04-03 101248](https://github.com/kanagavel7/HALF_ADDER_SUBTRACTOR/assets/162578954/7af24390-eefa-4c78-ab0c-cbd6cf5de238)

**HALF SUBTRACTER**

![Screenshot 2024-04-03 101336](https://github.com/kanagavel7/HALF_ADDER_SUBTRACTOR/assets/162578954/0f404b2d-f2d4-460e-8a6a-deb23bff7dcd)

**RTL SCHEMATIC**

**HALF ADDER**

![Screenshot 2024-04-03 101510](https://github.com/kanagavel7/HALF_ADDER_SUBTRACTOR/assets/162578954/17fbbfff-29ce-4fb7-b286-5dde85a4866f)

**HALF SUBTRACTER**

![Screenshot 2024-04-03 101545](https://github.com/kanagavel7/HALF_ADDER_SUBTRACTOR/assets/162578954/1b1538e3-053f-4f13-b075-1d7b8cbeec15)

**OUTPUT/TIMING WAVEFORM**

**HALF ADDER**

![Screenshot 2024-04-03 101707](https://github.com/kanagavel7/HALF_ADDER_SUBTRACTOR/assets/162578954/27666525-9743-4909-be91-ed5f45bf97de)

**HALF SUBTRACTER**

![Screenshot 2024-04-03 101749](https://github.com/kanagavel7/HALF_ADDER_SUBTRACTOR/assets/162578954/62c1f0b9-243c-4f6b-9bf7-78fed91d5aaa)

**Result:**

Thus, a half adder and half subtractor circuit is designed to verify its truth table in Quartus using Verilog programming.
