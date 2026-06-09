# Hardware Affero General Public License, Version 1.0 (HAGPL-1.0)

**Copyright (C) 2026 [Your Name or Organization]**

This license extends copyleft protection to hardware designs, HDL source code,
schematics, and associated firmware, requiring that any hardware product
incorporating the design disclose all design files.

## Preamble

The HAGPL applies copyleft principles to the hardware domain.  Just as the
AGPL ensures software freedom, the HAGPL ensures that hardware designs—
including HDL code, schematics, PCB layouts, and mechanical CAD files—remain
free for study, modification, and redistribution.  Any physical product built
from a covered design must be accompanied by the complete design files.

## TERMS AND CONDITIONS

### 0. Definitions.

"This License" refers to version 1.0 of the Hardware Affero General Public
License (HAGPL-1.0).

"The Design" means any hardware design licensed under this License, including
HDL source code (Verilog, VHDL, Chisel, etc.), schematics, PCB layouts,
Gerber files, bill of materials, mechanical CAD files, and associated
firmware or software that is embedded in the hardware.

"Physical Product" means any tangible device, board, chip, or system that is
manufactured based in whole or in part on the Design.

"Design Files" means the preferred form for making modifications to the
Design, including all source files, libraries, simulation testbenches,
constraint files, and build scripts.

"Firmware" means any software embedded in or distributed with the Physical
Product that is necessary for the Design to function as intended.

"Corresponding Materials" means:
- Complete Design Files in their native format;
- Complete Firmware source code;
- All build and synthesis scripts;
- All simulation and verification files;
- Documentation sufficient for a third party to manufacture and modify the
  hardware;
- A list of all required toolchains and their exact versions.

### 1. Basic Permissions.

All rights are conditional on continued compliance.  You may study, modify,
and use the Design for any lawful purpose.

### 2. Conveying Design Files.

You may convey verbatim or modified copies of the Design Files, provided:
- You keep all copyright notices intact;
- You include a copy of this License;
- Modified versions are licensed under this License in their entirety;
- You include the Corresponding Materials.

### 3. Physical Product Requirement.

If you manufacture, distribute, or sell a Physical Product based on the
Design (modified or unmodified), you must:

- **a)** Provide the complete Corresponding Materials with each Physical
  Product, either on durable medium included with the product or through a
  publicly accessible URL printed on the product;
- **b)** Ensure the Corresponding Materials remain available for at least
  five years after the last Physical Product is sold;
- **c)** Include instructions for accessing, modifying, and rebuilding the
  Design;
- **d)** If the Physical Product contains programmable logic (FPGA, CPLD,
  etc.), provide the complete programming files and the tools required to
  reprogram the device.

### 4. Network Interaction (Embedded Devices).

If the Physical Product is a network-connected device, you must:
- Provide a mechanism for the owner to access and modify the Design remotely;
- Include a conspicuous notice in the device's interface or documentation
  stating that the device contains hardware design files licensed under this
  License and where to obtain them;
- Not implement any mechanism that prevents the owner from replacing, 
  modifying, or reprogramming the Design.

### 5. Combined Designs.

A combined design that includes both HAGPL-covered and non-covered components
is a covered work if the HAGPL component is modified or if the non-covered
components are substantially dependent on the HAGPL component to function.

Mere aggregation on a PCB or in a system does not create a covered combined
design.

### 6. Termination.

Violation terminates your rights.  A 60-day cure period is available for a
first documented violation.  Subsequent violations are permanently terminated
without remedy.

### 7. Patents.

Each contributor grants a non-exclusive, worldwide, royalty-free patent
license under their essential patent claims that read on the Design.
Patent litigation terminates all rights under this License.

### 8. Warranty and Liability.

THERE IS NO WARRANTY FOR THE DESIGN.  IN NO EVENT SHALL ANY COPYRIGHT HOLDER
BE LIABLE FOR DAMAGES ARISING FROM THE USE OF THE DESIGN OR A PHYSICAL
PRODUCT BASED THEREON.

**END OF TERMS AND CONDITIONS**


## How to Apply These Terms

Include the following notice in every design file, and include the full
license text as `LICENSE`:

```
<Design name>
Copyright (C) <year> <author>

This hardware design is free: you can redistribute it and/or modify it
under the terms of the Hardware Affero General Public License, version 1.0.
There is NO WARRANTY.  Full terms: <URL to license text>.
```

Mark the design as HAGPL-1.0 licensed in the project README and in a
prominent location on the schematic or PCB silkscreen where feasible.
