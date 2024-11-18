# EXP-5: 32Bit-ALU_Synthesis

## Aim:

Synthesize 32 Bit ALU design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being
used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

#### Synthesis RTL Schematic :


![Screenshot 2024-11-18 121917](https://github.com/user-attachments/assets/1f64e9e0-9d3b-40eb-807d-12984da103fe)


#### Area report:

![Screenshot 2024-11-18 120942](https://github.com/user-attachments/assets/9c87b5d8-3a1a-4b36-bae1-00f1133e1f18)


#### Power Report:

![Screenshot 2024-11-18 121019](https://github.com/user-attachments/assets/f27e3682-93b9-4b06-83a4-276e5d8592af)


#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
