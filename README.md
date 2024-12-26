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


![Screenshot 2024-12-26 194844](https://github.com/user-attachments/assets/495d5e36-7d84-4f96-9842-c3d242dfd53b)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

Developed by:B.Gunasundari

RegisterNumber:24002680

![Screenshot 2024-12-26 194648](https://github.com/user-attachments/assets/32e372be-b126-4b30-80d9-82fd77a8aa3f)


![Screenshot 2024-12-26 194658](https://github.com/user-attachments/assets/46187589-a172-4d0b-a814-6bdf5507fc30)


**RTL Schematic**
![Screenshot 2024-12-26 194706](https://github.com/user-attachments/assets/1a1cda07-d5ac-4d24-94af-2df61964b64a)

![Screenshot 2024-12-26 194714](https://github.com/user-attachments/assets/df2f84c7-10b9-4e4f-a07a-cbc1a4b13aa6)



**Output/TIMING Waveform**
![Screenshot 2024-12-26 194723](https://github.com/user-attachments/assets/9832d604-dd9e-4364-b424-74eafec07dce)


![Screenshot 2024-12-26 194731](https://github.com/user-attachments/assets/7c8b1403-f085-43a8-9151-366f59ff9557)


**Result:**

Thus the half wave subtractor in quartus using verilog programming are studied, verified and executed successfully.
