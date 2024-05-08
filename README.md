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

Developed by:DHARSHINI S
RegisterNumber:212223110010*/

module boolean(e, f, a, b, c, d);
output e, f;
input a, b, c, d;
assign e = a || (b && c) || ((!b) && d);
assign f = ((!b) && c)|| (b && (!c) && (!d));
endmodule


**RTL realization**
![315195518-6a824445-3dfe-4570-b62f-c69840760e88](https://github.com/Akshayaamt/BOOLEAN_FUNCTION_MINIMIZATION/assets/144870472/26a16282-89fb-489c-a4b9-d8695153d132)


**RTL**
![315195977-612a4714-79dc-4603-9389-5fe91ab60aaa](https://github.com/Akshayaamt/BOOLEAN_FUNCTION_MINIMIZATION/assets/144870472/aa4e54f8-2a5a-4219-859c-bf8e7c434d35)



**Timing Diagram**
![315195707-75ec0f62-e6e6-46bd-9281-d8bc850e20a7](https://github.com/Akshayaamt/BOOLEAN_FUNCTION_MINIMIZATION/assets/144870472/f54947f8-efca-4d76-b90d-d17b90a98cc3)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.


