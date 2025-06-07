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
FUNCTION 1

i)
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule


FUNCTION 2


ii)
module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule
```

FUNCTION 1

![394201203-d5357ef7-67bb-41e1-bfbf-23ae66e6dffc](https://github.com/user-attachments/assets/ac1b84d2-6c2e-4af1-87fe-fd1dc014cabd)

FUNCTION 2

![394201405-a53eabae-02ca-4be4-bca1-1e3a29b0187c](https://github.com/user-attachments/assets/09c6a190-697e-4f95-bce3-d3f035f59052)

FUNCTION 1

![394201719-b4e996bf-d92d-4180-8221-eeef67884cd0](https://github.com/user-attachments/assets/9002235c-f939-41d6-8295-be24da4b2748)

FUNCTION 2

![394201840-8e4bfdec-b657-47f5-bf3f-989f5ee42813](https://github.com/user-attachments/assets/1594f92d-55fe-4484-b8ec-e3234831201d)

Timing Diagram

FUNCTION 1

![394202009-bbde9f23-db1f-4530-86e6-ea08c2454349](https://github.com/user-attachments/assets/93466c94-a85d-47b3-a4e6-78dbaa4d036f)

FUNCTION 2

![394202275-a9804bf4-5da4-4fba-8332-59aca9d6e562](https://github.com/user-attachments/assets/59f9776c-ee4e-4fab-bffe-824cf11c13d5)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

