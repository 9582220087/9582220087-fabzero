
## How to Design and Fabrication of a programmable electronic circuit: 

First of all we start with designing the electronic circuit and 
developing its PCB diagram by using Kicad software and then send it for milling. Then, component soldering and programming followed by testing.

### Draw a schematic diagram:
Design a schematic diagram using Kicad software. Steps are as follows:

- Open KiCAd software  --> open new project --> save with meaningful name in proper location -->

- Load symbol library by click on symbol or (Tool --> Edit symbol Library)

- Place the symbol by double click and choose the component from dropdown list.

- Connect all the component by using the green wire placed right hand side of the tool.

- Attach a PWR_FLAG to VCC and GND 

- Unused pin of the ATinny44 must be assign "no connect".

- Annotation or Naming by clicking on  "Annotate schematic symbols" tool (choose default values).

- To Edit the value of component by press E while the cursor will be above the component.

- To Write the local name use the "Place Net label" icon.

- Use "Generate Netlist" icon while generating the generate the netlist.

- Use "Assign PCB footprints to schematic symbols" icon for assigning footprint.



-

