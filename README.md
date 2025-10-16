# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.

```
**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
F(A,B,C,D)=AB+CD+AD

module boolean_function_4var (
    input  wire A,
    input  wire B,
    input  wire C,
    input  wire D,
    output wire F
);

assign F = (~A & B) | (C & D) | (A & ~D);

endmodule
```
```
Developed by:PRAKASH V 
RegisterNumber:*25018527
```

**RTL realization**

<img width="1021" height="833" alt="Screenshot 2025-10-13 155454" src="https://github.com/user-attachments/assets/2f80b0a6-eb93-4b46-9b62-a16e73270c3d" />

**Output:**

<img width="631" height="798" alt="Screenshot 2025-10-13 155808" src="https://github.com/user-attachments/assets/7b97994a-ecbd-4e09-8b08-9b241efda2c0" />

**RTL**

<img width="1047" height="266" alt="Screenshot 2025-10-13 155907" src="https://github.com/user-attachments/assets/29a5f84b-61af-46e3-9931-ddd507fbb5f2" />

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

