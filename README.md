AIM:

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D

F2=xy’z+x’y’z+w’xy+wx’y+wxy

Equipment Required:

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

Theory

Logic Diagram

Procedure

1.Type the program in Quartus software.

2.Compile and run the program.

3.Generate the RTL schematic and save the logic diagram.

4.Create nodes for inputs and outputs to generate the timing diagram.

5.For different input combinations generate the timing diagram.

Program:
module expfour(a,b,c,d,f)
input a,b,c,d
output f;


Developed by:KALYANE SREE M     RegisterNumber:212222050028

RTL realization
![circuit 2](https://github.com/Kalyanesree/implementation-of-combinational-logic/assets/163311552/ddd53e4d-956d-4e9c-9d46-7893c5d86f7f)

Output:

RTL
![table 2](https://github.com/Kalyanesree/implementation-of-combinational-logic/assets/163311552/b456f9f6-2bd8-4ecf-b3f8-6b66a358ab48)


Timing Diagram
![timing 2](https://github.com/Kalyanesree/implementation-of-combinational-logic/assets/163311552/4b8b5937-95b6-409d-bc49-c22f2eb23985)



Result:
Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

