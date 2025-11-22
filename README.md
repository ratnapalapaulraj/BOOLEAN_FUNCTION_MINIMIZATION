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

```
module funct1(a,b,c,d,f1); 
input a,b,c,d; 
output f1; 
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c)); 
endmodule
```

Developed by: RegisterNumber:25016862


**RTL realization**
<img width="1920" height="1080" alt="exp2 logic diagram" src="https://github.com/user-attachments/assets/a5387f36-f088-4f81-b01a-7ac2bac616c9" />



**RTL**
<img width="1920" height="1080" alt="exp2 waveform" src="https://github.com/user-attachments/assets/1644d1a2-62de-46fe-b5ec-54114ac490be" />



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

