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

 Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
i)
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

ii)
module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule


**RTL realization**
<img width="433" height="395" alt="Screenshot 2025-11-19 102145" src="https://github.com/user-attachments/assets/87fb6b24-f7a4-4e83-9a7e-4e2c9a1ff370" />
<img width="467" height="271" alt="Screenshot 2025-11-19 105710" src="https://github.com/user-attachments/assets/97021e67-1327-4ee7-a36a-a0576b23e1e9" />


**Output:**
<img width="1920" height="1080" alt="Screenshot (35)" src="https://github.com/user-attachments/assets/65e25bf5-0191-4ef1-97cd-830d059d7037" />
<img width="1645" height="920" alt="Screenshot (38)" src="https://github.com/user-attachments/assets/576b9f26-2fde-4909-bcfa-9d8699908df7" />


**RTL**

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.


