# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

![Screenshot 2024-12-22 161428](https://github.com/user-attachments/assets/e9d08b86-12ff-4e10-a410-a438e388a49f)


**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

module exp2(a,b,c,d,w,x,y,z,f1,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule

Developed by: RegisterNumber:*/ OBELESH R (24901123)


**RTL realization**

**Output:**

**RTL**

![Screenshot 2024-12-22 161621](https://github.com/user-attachments/assets/e010cba0-efb9-40f1-a803-867985d7eb8a)


**Timing Diagram**

![Screenshot 2024-12-22 161649](https://github.com/user-attachments/assets/464ffa19-94f9-44a4-af90-87a22d1f87bb)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

