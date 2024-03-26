# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

## AIM:

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

## Full Adder and Full Subtractor

## Full Adder

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

## Figure -1 FULL ADDER

## Full Subtractor

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

## Truthtable

## Procedure

Write the detailed procedure here

## Program:
## Developed by: HARISHKUMAR R
## RegisterNumber:212223230073

Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.

## Full Adder:
![image](https://github.com/harissunique/FULL_ADDER_SUBTRACTOR/assets/147139338/d663f44a-0493-4a9b-9d62-ba789741efe2)




## Full Subtractor

![image](https://github.com/harissunique/FULL_ADDER_SUBTRACTOR/assets/147139338/6d2297ef-9d0b-4034-bb0e-2c5fb250d7c2)



## RTL Schematic

## Full Adder:
![image](https://github.com/harissunique/FULL_ADDER_SUBTRACTOR/assets/147139338/bcef06b3-b130-49b5-b1c9-90b37df0ad8c)

## Full Subtractor

![image](https://github.com/harissunique/FULL_ADDER_SUBTRACTOR/assets/147139338/7471e798-ecc5-4a7a-b06b-42f820ea791e)


## Output Timing Waveform

## Full Adder:
![image](https://github.com/harissunique/FULL_ADDER_SUBTRACTOR/assets/147139338/a2deefdf-1b46-4d83-ac52-94873a893727)


## Full Subtractor

![image](https://github.com/harissunique/FULL_ADDER_SUBTRACTOR/assets/147139338/5caeaddc-be04-4e66-b1a8-c02d43d65be5)


## Result:

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



