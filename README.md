# Traffic_light_controller_Synthesis

## Aim:

Synthesize Traffic Light Controller design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Creating an SDC File

•	In your terminal type “gedit input_constraints.sdc” to create an SDC File if you do not have one.

### Step 3 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

Synthesis RTL Schematic :![6th OP](https://github.com/user-attachments/assets/0aca1482-98d2-4001-b1e5-e4255c12d3cb)


### Area report:![6th area](https://github.com/user-attachments/assets/f032c2ca-6a16-47d0-b129-f91aab947f94)

### Time Report:![6th time](https://github.com/user-attachments/assets/739a4b33-52ee-4b4e-8d93-baeddbb551e6)

### Power Report:![6th power](https://github.com/user-attachments/assets/daa6f3b1-5903-4fed-a762-cd7a29b15318)


### Result:

The generic netlist of Traffic Light Controller has been created, and area, power reports have been tabulated and generated using Genus.
