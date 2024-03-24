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
![313918409-ebae1abf-7460-40f7-9578-0d5066659c5a](https://github.com/keziahhhf/BOOLEAN_FUNCTION_MINIMIZATION/assets/155235704/61701e30-229d-4cf5-98cc-cbaa4fd60636)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
// Verilog model:Circuit with boolean expressions
module ex02 (E,F,A,B,C,D);
input A, B, C, D;
output E,F;
assign E = A || (B && C) || ((!B) && D);
assign F=((!B) && C) || ( B && (!C) && (!D));
endmodule

Developed by: RegisterNumber:*/
F.keziah 212223040094


**RTL realization**

![screenshot(5)](https://github.com/keziahhhf/BOOLEAN_FUNCTION_MINIMIZATION/assets/155235704/dc491add-895f-41e4-ac1d-ac9b119066cf)

**Output:**

**RTL**

**Timing Diagram**
![screenshot(6)](https://github.com/keziahhhf/BOOLEAN_FUNCTION_MINIMIZATION/assets/155235704/a1b649d2-cdef-42f0-8e4d-3e2788f32ed6)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

