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


**Program:
module EXP_3_1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
endmodule
module EXP_3_2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y&z)|(x&y)|(w&y));
endmodule

Developed by:Avanthika M RegisterNumber:212224110009*/


**RTL realization**
![Screenshot 2025-05-01 180632](https://github.com/user-attachments/assets/a92f96d9-bc53-4d0c-b597-429142859a4f)
![Screenshot 2025-05-01 181809](https://github.com/user-attachments/assets/6c42101e-46d2-4bbd-8b2e-073e3bb84f10)

**Output:**

**RTL**
![Screenshot 2025-05-01 180935](https://github.com/user-attachments/assets/3fcfb8bd-8f29-4993-b57a-d775ab284153)
![Screenshot 2025-05-01 182016](https://github.com/user-attachments/assets/d71546c3-75c1-4add-8554-5c0c47943985)

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

