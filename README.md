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
module exp2(a,b,c,d,f1); 
input a,b,c,d; 
output f1; 
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c)); 
endmodule
```
```
module exp2(w,x,y,z,f2); 
input w,x,y,z; 
output f2; 
assign f2=((~y & z)|( w & y )|(x & y)); 
endmodule 
```

Developed by: RegisterNumber:25016862


**RTL realization**
<img width="1920" height="1080" alt="exp2 logic diagram" src="https://github.com/user-attachments/assets/a5387f36-f088-4f81-b01a-7ac2bac616c9" />
<img width="1920" height="1021" alt="exp2 logicgate" src="https://github.com/user-attachments/assets/9cd1e276-7397-4c6f-938f-7150d445946e" />



**RTL**
<img width="1920" height="1080" alt="exp2 waveform" src="https://github.com/user-attachments/assets/1644d1a2-62de-46fe-b5ec-54114ac490be" />
<img width="1920" height="1021" alt="exp2 wave" src="https://github.com/user-attachments/assets/c2a7ab12-59cc-43d5-b267-9d54966ee849" />



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

