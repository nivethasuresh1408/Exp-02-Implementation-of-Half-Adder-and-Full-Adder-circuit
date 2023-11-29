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

Developed by: NIVETHA S

RegisterNumber: 23002894 

 Code:

 Half Adder:

 ![Exp3 ha code](https://github.com/nivethasuresh1408/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152055927/9f81cd2a-4427-4ee5-8aa7-b01901c7d731)

Full Adder:

![Exp3 fa code](https://github.com/nivethasuresh1408/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152055927/c8e6ea30-e22f-411f-b60d-0b02a4534855)

Truth table:

Half adder:

![Exp3 truthtable (ha)](https://github.com/nivethasuresh1408/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152055927/f628c321-b6b7-423d-b0f7-f8984e228c65)

Full adder:

![Exp3 truthtable (fa)](https://github.com/nivethasuresh1408/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152055927/bc649806-4f7d-4858-b8f6-fb9cf0d0835c)

RTL Diagram:

Half adder:

![Exp3 ha RTL diagram](https://github.com/nivethasuresh1408/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152055927/0a030138-bc95-4d9a-a751-12691ed01d5f)

Full adder:

![Exp3 fa RTL diagram](https://github.com/nivethasuresh1408/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152055927/6c21242c-6084-450f-867d-9a20ffd7322c)

### Output:

Half adder:

![halfadder-wave](https://github.com/nivethasuresh1408/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152055927/00462eb2-bee0-4af1-bd32-795ca6656e77)

Full Adder:

![Exp3 fa wave](https://github.com/nivethasuresh1408/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152055927/a8b4a085-6964-46ca-a784-7742f3442fca)


### Result:
Thus the half adder and full adder circuit are designed and the truth table for half adder and full
adder are verified.
