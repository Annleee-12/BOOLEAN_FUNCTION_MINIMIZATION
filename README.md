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


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber: 25016022
i) module funct1(a,b,c,d,f1);
 input a,b,c,d;
 output f1;
 assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
 endmodule
 ii) module funct2(w,x,y,z,f2);
 input w,x,y,z;
 output f2;
 assign f2=((~y & z)|( w & y )|(x & y));
 endmodule


**RTL realization**


<img width="622" height="684" alt="image" src="https://github.com/user-attachments/assets/eaaf6755-57d5-49f2-884d-317bbd9b5880" />


**Output:**

**RTL**

**Timing Diagram**

<img width="635" height="601" alt="image" src="https://github.com/user-attachments/assets/b7c6f7d9-9702-4a8e-982f-338196be4999" />


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

