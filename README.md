# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
 HALF ADDER
 
![image](https://github.com/Nandhika05/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/154419402/97031178-651c-45fc-89aa-d687c06bb862)

FULL ADDER

![image](https://github.com/Nandhika05/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/154419402/94a9d9af-99b5-47c5-9035-82aad1434f7f)

Developed by: NANDHIKA P

RegisterNumber:  212223040125

*/
## Truthtable

HALF ADDER

![image](https://github.com/Nandhika05/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/154419402/fcf86791-042f-4c47-8b48-ae61865dd4ed)

FULL ADDER

![image](https://github.com/Nandhika05/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/154419402/372b535b-5a84-4b55-8c54-814a03e3219d)

## RTL realization

HALF ADDER CIRCUIT 

![image](https://github.com/Nandhika05/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/154419402/0cce6be8-a130-4b84-afe5-8dc3d88698bb)

FULL ADDER CIRCUIT

![image](https://github.com/Nandhika05/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/154419402/8d56fc90-7e50-4a27-895a-ec368452472a)

### TIMING DIAGRAM

HALF ADDER 

![image](https://github.com/Nandhika05/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/154419402/89b38295-9920-432e-a30a-1a2b2e59dd4f)

FULL ADDER

![image](https://github.com/Nandhika05/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/154419402/caee2618-10e3-4e8b-abc9-5f6a0cb6f184)

### Result:

To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming
