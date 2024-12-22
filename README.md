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

/*i)module funct1(a,b,c,d,f1);

input a,b,c,d;

output f1;

assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));

endmodule

ii) module funct2(w,x,y,z,f2);

input w,x,y,z;

output f2;

assign f2=((~y & z)|( w & y )|(x & y));

endmodule 

Developed by:R. mounish vamsi kumar
RegisterNumber: 24003774*/


**RTL realization**

**Output:**

**RTL**
![Screenshot 2024-12-22 092148](https://github.com/user-attachments/assets/232bb3fe-6e1d-4a46-920d-f5c3f5b08622)

![Screenshot 2024-12-22 092237](https://github.com/user-attachments/assets/1b58f8f1-1a6b-484d-949a-802d87f4bab5)


**Timing Diagram**

![Screenshot 2024-12-22 092302](https://github.com/user-attachments/assets/ceb35df6-1659-47bf-9539-48bb9741c12e)

![Screenshot 2024-12-22 092333](https://github.com/user-attachments/assets/18bf7624-e5fc-4150-ba88-13bae3131e72)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

