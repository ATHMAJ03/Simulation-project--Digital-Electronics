# TITTLE
IMPLEMENT OR GATE USING NAND GATE

# THEORY
An OR gate can be replaced by NAND gates as shown in the figure (The OR gate is replaced by a NAND gate with all its inputs complemented by NAND gate inverters). Thus, the NAND gate is a universal gate since it can implement the AND, OR and NOT functions.

# LOGIC DIAGRAM
![image](https://github.com/ATHMAJ03/Simulation-project--Digital-Electronics/assets/118753139/fd73f794-56c5-4d87-bdbf-6f091790dade)


# NETLIST DIAGRAM
![project diagram](https://github.com/ATHMAJ03/Simulation-project--Digital-Electronics/assets/118753139/6f956449-3371-4506-a637-d7726e765226)

# TIMING DIAGRAM
![project timing](https://github.com/ATHMAJ03/Simulation-project--Digital-Electronics/assets/118753139/1fafe8e3-f7be-40fa-b476-579754988200)

# PROGRAM
```
Developed By : ATHMAJ VENUGOPAL
Register No : 212222240014
```
module aaa(a,b,f);
input a,b;
output f;
wire c,d;
nand (c,a);
nand (d,b);
nand (f,c,d);
endmodule
```
# REFERENCE
