# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Function 1:

    module ha(a,b,sum,carry);
    input a,b;
    output sum,carry;
    assign sum= (a ^ b);
    assign carry= ( a & b);
    endmodule

Function 2:

    module hs(a,b,difference,borrow);
    input a,b;
    output difference,borrow;
    assign difference= (a ^ b);
    assign borrow= ( ~a & b);
    endmodule



Developed by: HARSHIDA K S

RegisterNumber:24900060


**RTL**

![logic diagram](https://github.com/user-attachments/assets/e7097d03-359a-4ed3-9eda-4c89a4c855c8)
![LOGIC DIA FUN2](https://github.com/user-attachments/assets/6965bb59-ec79-4489-90a9-2c8b6c8ddfd6)



**Output:**
![op functions](https://github.com/user-attachments/assets/ef3ed1a1-c964-4f3a-8136-2e6b257de497)
![OP fun2](https://github.com/user-attachments/assets/5e01ef49-cf29-4ede-ab63-f3fb16883d24)



**Timing Diagram**
![op functions](https://github.com/user-attachments/assets/f9c82611-d02c-41c5-a184-42a8d868a71d)
![OP fun2](https://github.com/user-attachments/assets/a295cbbe-33f4-4a86-9ff9-c24c7e1e6a56)



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

