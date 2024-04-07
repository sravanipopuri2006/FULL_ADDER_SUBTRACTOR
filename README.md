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
## FULL ADDER
![Screenshot 2024-04-07 223348](https://github.com/sravanipopuri2006/FULL_ADDER_SUBTRACTOR/assets/139778301/85274ae8-1e67-4900-9880-d3eae0604306)
## Full subtractor
![Screenshot 2024-04-07 223401](https://github.com/sravanipopuri2006/FULL_ADDER_SUBTRACTOR/assets/139778301/01019278-9b95-4e8d-a672-06a31fe23a19)




**Procedure**

1.Create a New Project :
Open Quartus and create a new project by selecting "File" > "New Project Wizard." Follow the wizard's instructions to set up your project, including specifying the project name, location, and target device (FPGA).

2.Create a New Design File :
Once the project is created, right-click on the project name in the Project Navigator and select "Add New File." Choose "Verilog HDL File" or "VHDL File," depending on your chosen hardware description language.

3.Write the Combinational Logic Code :
Open the newly created Verilog or VHDL file and write the code for your combinational logic.

4.Compile the Project :
To compile the project, click on "Processing" > "Start Compilation" in the menu. Quartus will analyze your code, synthesize it into a netlist, and perform optimizations based on your target FPGA device.

5.Analyze and Fix Errors :
If there are any errors or warnings during the compilation process, Quartus will display them in the Messages window. Review and fix any issues in your code if necessary. View the RTL diagram.

6.Verification :
Click on "File" > "New" > "Verification/Debugging Files" > "University Program VWF". Once Waveform is created Right Click on the Input/Output Panel > " Insert Node or Bus" > Click on Node Finder > Click On "List" > Select All. Give the Input Combinations according to the Truth Table amd then simulate the Output waveform

## Program:
/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by:POPURI SRAVANI
RegisterNumber:212223240117
*/

## Full Adder
![Screenshot 2024-04-07 222708](https://github.com/sravanipopuri2006/FULL_ADDER_SUBTRACTOR/assets/139778301/a0bf7dc1-e199-4be4-97b7-18818dbb5812)
## Full subtractor
![Screenshot 2024-04-07 222719](https://github.com/sravanipopuri2006/FULL_ADDER_SUBTRACTOR/assets/139778301/72ac33ec-0284-42d6-89e1-4446e97f98bb)
## RTL SCHEMATIC:
## Full Adder
![Screenshot 2024-04-07 222850](https://github.com/sravanipopuri2006/FULL_ADDER_SUBTRACTOR/assets/139778301/42128dd1-057b-41d4-bdab-0e3971c57c46)
## Full subtractor
![Screenshot 2024-04-07 222904](https://github.com/sravanipopuri2006/FULL_ADDER_SUBTRACTOR/assets/139778301/7ed1e7d7-2da6-4b57-a71f-47d3c6ecde7e)
## TIMING WAVEFORM:
## FULL ADDER
![Screenshot 2024-04-07 222915](https://github.com/sravanipopuri2006/FULL_ADDER_SUBTRACTOR/assets/139778301/3b35d0fb-2a1c-4af2-b5fa-c0328d1bff6c)
## FULL SUBTRACTOR
![Screenshot 2024-04-07 222923](https://github.com/sravanipopuri2006/FULL_ADDER_SUBTRACTOR/assets/139778301/11006ba1-5c58-4d93-b2ae-a408178ddd20)













**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



