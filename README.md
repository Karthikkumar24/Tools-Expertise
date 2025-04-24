# Tools-Expertise
## 1.	Primetime Description:
- ●	Prime Time Flow
- ●	Writing Constraints and Validating them
- ●	Generating Timing Reports and analyzing them
- ●	Constraining multiple clocks
- ●	Additional Constraints

## 2.	Fusion Compiler
- ●	Creating a design library and importing NDM, Technology files, Parasitic Models and RTL.
- ●	Writing MCMM Timing Constraints and reading into the tool.
- ●	Loading the UPF file into the tool.
- ●	Synthesize and optimize the Design and Writing Netlist, SDC, and DEF files.
- ●	Resynthesize the design using a DEF file for Better QoR.
- ●	Design Mismatch Manager (DMM): Creating the Black Box for missed blocks in the design.
- ●	Creating the Floorplan (Square, Rectangular, Rectilinear, L – Shape, U –Shape, T -	shape), Shaping the blocks and placing Pins, I/Os, and Macros.
- ●	Creating Power plan – Power Rings, Straps, Rails, and PBNS
- ●	Performing CCD Optimization and Inserting ICGs.
- ●	Performing Clock Tree Synthesis


### Setting up the CTS
- ●	Identifying Implicit Sink Pins & Ignore Pins
- ●	Declaring Explicit Sink Pins and Ignore Pins
- ●	Setting the clock as propagated and
- ●	Preserving the pre-existing cells on the clock network
- ●	Writing the Clock Routing Rule for various NDRs
- ●	(Spacing, Shielding, and Metal Width Increasing)
- ●	Specifying the logical DRCs
- ●	(max_tran , max_cap and max_fanout)

### Running CTS
- ●	Running Classic CTS and CCD CTS for Skew optimization
- ●	Check the Timing Reports (setup, hold, WNS, TNS)
- ●	Enable application options related to Hold optimization and minimize Hold violations
- ●	Performing Global & Detail Routing and Checking DRCs.
-- a.	Responsible for fixing opens, shorts, and floating sets during the routing stage.
- ●	Performing Signoff checks
- ●	Extract RC using Star-RC.
- ●	Export netlist, GDS II, SDC, SPEF, and DEF file.
- ●	Timing analysis of the Design using the Prime Time tool
- ●	Obtaining the Timing reports
- ●	Fix the Timing violations by Sizing the cells, Inserting/Deletion of the Buffer, Cell Swapping, Improving the nets.
- ●	Generating ECO reports


## 3.	Calibre
- Physical Verification: Run design rule checking (DRC) and layout versus schematic
- (LVS) checks to ensure the layout meets manufacturing and electrical integrity standards.
