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
Developed by: KANISHKA R S
RegisterNumber:  212223050026
*/
![image](https://github.com/kanishkaramesh007/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147321636/55c9df84-c4b6-4fbb-929d-2c39c3c7dd39)

   
Logic symbol & Truthtable
RTL realization

### Output:
### RTL
![image](https://github.com/kanishkaramesh007/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147321636/4d038307-9541-4324-9559-3766c12f6af1)


### TIMING DIAGRAM
![image](https://github.com/kanishkaramesh007/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147321636/c00c208e-10de-44a7-af6c-22cbc758c7f0)



### TRUTH TABLE 
![image](https://github.com/kanishkaramesh007/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147321636/5915f2b7-1394-458d-91bb-5c9ea9412895)




### Result:
Thus the implementation of Half Adder and Full Adder verified successfully.
