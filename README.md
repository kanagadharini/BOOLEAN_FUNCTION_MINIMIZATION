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



**RTL realization**

**Output:**
<img width="1920" height="1080" alt="Screenshot (33)" src="https://github.com/user-attachments/assets/7eed7372-a8e8-4673-aa88-2dbd11546465" />

**RTL*<img width="1920" height="1080" alt="Screenshot (32)" src="https://github.com/user-attachments/assets/6dfadd02-4251-4506-b1da-7db5517d5c98" />
*EXPERIMENT 2:
MINIMIZATION OF BOOLEAN FUNCTION
i)
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

**Timing Diagram**
![WhatsApp Image 2025-11-12 at 10 46 56_a9d74ece](https://github.com/user-attachments/assets/885c4f4f-56b8-4ca8-b2c9-8bd9e67ed003)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

