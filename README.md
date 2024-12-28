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
 module hello (w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y&z)|(w&y)|(x&y));
endmodule
```

Developed by:Khamalraaj S 


RegisterNumber:24901015

**Truth table**

![Screenshot 2024-12-28 232952](https://github.com/user-attachments/assets/1319edf4-4305-4446-bf07-d2030f76e0f0)

**Boolean minimization**
![WhatsApp Image 2024-12-21 at 08 56 18_c590625c](https://github.com/user-attachments/assets/2d90b5cc-7a8d-4ba8-8a27-f296a7424ee5)
![WhatsApp Image 2024-12-21 at 08 56 31_aa7c955f](https://github.com/user-attachments/assets/01c430fc-d406-449e-b8eb-aa123d0da42e)



**RTL realization Output:**
![Screenshot 2024-11-05 132637](https://github.com/user-attachments/assets/0371c461-b1a3-4a5d-8c7f-efbce294d925)

**RTL Timing Diagram**
![Screenshot 2024-11-05 133135](https://github.com/user-attachments/assets/b5b1bae2-ebf6-4fbc-a51b-4cc903a1b5f4)



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

