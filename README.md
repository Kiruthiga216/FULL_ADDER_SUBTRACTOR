EXPERIMENT 4: FULL ADDER AND  FULL SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit


NAME:KIRUTHIGA.B


ROLL NUMBER:24900863

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


![fa tt](https://github.com/user-attachments/assets/781a1cef-12ae-499c-a87c-29fe3f68e33c)


full subtractor truth table:


![f s tt](https://github.com/user-attachments/assets/fdc483e8-fd9c-441e-8474-f0e632f21b0e)



**Procedure**

 1. Type the program in Quartus software.
 2. Compile and run the program.
 3. Generate the RTL schematic and save the logic diagram.
 4. Create nodes for inputs and outputs to generate the timing diagram.
 5. For different input combinations generate the timing diagram.


**Program:**

 Program to design a full adder and full subtractor circuit and verify its truth table in quartus using Verilog programming. 
 
 
 program for full adder:
 
 
 ![de ex4 sc3](https://github.com/user-attachments/assets/c262ae2a-5e68-4b6d-ac8b-a856c4ed7e72)

 
 program for full subtractor:

 
 ![de ex8 sc3](https://github.com/user-attachments/assets/6004f5a6-2e9e-4771-9fec-7c0119a7eee6)



**RTL Schematic**


full adder:


![de ex4 sc2](https://github.com/user-attachments/assets/36b72cd9-5737-47e5-bae5-5e1c3230e0bf)


full subtractor:


![de ex8sc2](https://github.com/user-attachments/assets/c71fe8e7-533e-45a4-b68c-be065361fd22)




**Output Timing Waveform**


full adder:

![de ex4 sc1](https://github.com/user-attachments/assets/fa6ca926-4eef-47fc-96c7-fc182be81b5a)


full subtractor:


![de ex8 sc1](https://github.com/user-attachments/assets/ac18b2bb-bbcf-480f-88eb-379e8dea397e)



**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



