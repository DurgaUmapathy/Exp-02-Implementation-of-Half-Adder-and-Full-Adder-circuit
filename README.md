# Exp-03-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
## AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

## Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

## Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

## Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
 
## Program:
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: DURGA U
RegisterNumber:  23003210

## CODE:

### HALF ADDER:

![Exp3 ha code](https://github.com/DurgaUmapathy/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152186191/eb7a2724-8e95-467e-84e0-d9c1488455bd)


### FULL ADDER:

![Exp3 fa code](https://github.com/DurgaUmapathy/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152186191/0bcc6450-60ef-4395-8871-d7c91511f199)



## Output:
## RTL:
### HALF ADDER:

![Exp3 ha RTL diagram](https://github.com/DurgaUmapathy/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152186191/aafb863b-0efb-4a20-a551-5e7675bfa4b1)


### FULL ADDER:

![Exp3 fa RTL diagram](https://github.com/DurgaUmapathy/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152186191/8fa39fda-13c3-4a6c-9379-21a85008065e)



## TIMING DIAGRAM:
### HALF ADDER:

![exp3 ha wave](https://github.com/DurgaUmapathy/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152186191/2b2f5771-fc4f-4456-ba01-f67345ad5c38)


### FULL ADDER:

![exp 3 fa wave](https://github.com/DurgaUmapathy/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152186191/22c6fdff-3666-4728-9a59-a9c970640cac)




### TRUTH TABLE:

### HALF ADDER:

![Exp3 truthtable (ha)](https://github.com/DurgaUmapathy/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152186191/7cd33cc9-b447-4866-84b5-19c0e8d04a79)


### FULL ADDER:

![Exp3 truthtable (fa)](https://github.com/DurgaUmapathy/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152186191/3264b142-97b5-4167-a551-c8ce28beec67)




### Result:
Thus, a half adder and full adder circuit is designed to verify its truth table in Quartus using Verilog
programming
