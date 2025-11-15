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
<img width="1920" height="1080" alt="Screenshot (54)" src="https://github.com/user-attachments/assets/42c1f375-5150-4595-acc9-fab9cdaeda53" />

**Output:**
<img width="1920" height="1080" alt="Screenshot (55)" src="https://github.com/user-attachments/assets/6cc8e7f7-67db-4e51-9416-663471c76c82" />

**RTL**

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

<img width="584" height="375" alt="Screenshot 2025-10-09 172821" src="https://github.com/user-attachments/assets/d56a6833-ab09-44da-b348-29d4564908ce" />

<img width="1903" height="886" alt="Screenshot 2025-10-09 173104" src="https://github.com/user-attachments/assets/6dedb6fc-8779-4ee9-a46d-ba00b1c9ad07" />
