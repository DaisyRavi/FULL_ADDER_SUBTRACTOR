

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

**Full Adder**
![full-adder2](https://github.com/DaisyRavi/FULL_ADDER_SUBTRACTOR/assets/151394386/cff687c3-db54-4c5d-b578-077a812cb18e)




**Full subtractor**

![Screenshot 2024-04-04 134801](https://github.com/DaisyRavi/FULL_ADDER_SUBTRACTOR/assets/151394386/0cb89035-02a3-41a9-811c-0470dcf7ec04)

**Procedure**

Write the detailed procedure here
*Create a new Quartus project:* Launch Quartus Prime software and create a new project. Provide a name for your project and specify the location where you want to save it.

*Design Entry:* In the Quartus software, go to File > New > Project Wizard. Follow the wizard to specify the target device family, device, and any other relevant settings.

*Create a schematic:* In Quartus, you can create a schematic using the built-in schematic editor. You'll need to design a circuit that includes full adders and logic gates to handle subtraction. Alternatively, you can write Verilog or VHDL code for your full adder/subtractor.

*Write Verilog or VHDL code:* Open a new file in Quartus and write the Verilog or VHDL code for your full adder/subtractor.

*Compile the design:* After designing your circuit or writing the Verilog/VHDL code, compile your design by clicking on Processing > Start Compilation.

*Simulate your design:* You can simulate your design using ModelSim, which is included with Quartus. This helps you verify that your design functions correctly.

*Program your FPGA:* Once your design is successfully compiled and simulated, you can program your FPGA using the Programmer tool in Quartus.

*Test your design:* After programming the FPGA, you can test your full adder/subtractor to ensure it behaves as expected.

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. 

Developed by: Daisy R

RegisterNumber: 212223220018
*/

**Full Adder**

![Screenshot 2024-04-04 195614](https://github.com/DaisyRavi/FULL_ADDER_SUBTRACTOR/assets/151394386/86b3a702-c2da-4031-8d09-d3daab0f3b1d)

**Full subtractor**

![Screenshot 2024-04-04 194743](https://github.com/DaisyRavi/FULL_ADDER_SUBTRACTOR/assets/151394386/400826bd-2579-4931-8c64-511e39c1b3bc)


**RTL Schematic**

**Full Adder**

![Screenshot 2024-04-04 195631](https://github.com/DaisyRavi/FULL_ADDER_SUBTRACTOR/assets/151394386/a5e7fdf1-6bdd-443d-b43c-f7914db5399e)


**Full subtractor**

![Screenshot 2024-04-04 132642](https://github.com/DaisyRavi/FULL_ADDER_SUBTRACTOR/assets/151394386/7cdfa1d5-1130-4130-8576-bd9daf323547)

**Output Timing Waveform**

**Full Adder**
![Screenshot 2024-04-04 195847](https://github.com/DaisyRavi/FULL_ADDER_SUBTRACTOR/assets/151394386/f94a7966-c3c3-4ea2-929d-3ff41d3c3a24)



**Full subtractor**

![Screenshot 2024-04-04 132551](https://github.com/DaisyRavi/FULL_ADDER_SUBTRACTOR/assets/151394386/6354cd55-8ddd-47e0-b79c-7b98611228db)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



