# Energy Efficiency License, Version 1.0 (EEL-1.0)

**Copyright (C) 2026 [Your Name or Organization]**

A license that requires software to meet minimum energy efficiency standards
and disclose energy consumption metrics.

## Preamble

The EEL addresses the environmental impact of software.  It requires that
software run efficiently, that energy consumption be measurable, and that
users be informed about the software's energy footprint.  It is designed
for environmentally conscious projects that want to ensure their software
does not waste energy.

## TERMS AND CONDITIONS

### 0. Definitions.

"This License" refers to version 1.0 of the Energy Efficiency License
(EEL-1.0).

"The Software" means the program licensed under this License.

"Energy Consumption" means the electrical energy consumed by running the
Software under standard operating conditions.

"Efficiency Standard" means the energy efficiency requirements specified
in the License notice.  If none are specified, the Software must not
perform unnecessary computation when idle and must support power-saving
modes where feasible.

### 1. Permissions.

You may use, copy, modify, and distribute the Software for any lawful
purpose, subject to the energy efficiency conditions below.

### 2. Efficiency Requirement.

If you modify and distribute the Software, you must not significantly
increase its Energy Consumption compared to the original version, unless
the increase is justified by proportional functional improvements and
documented.

### 3. Energy Disclosure.

You must provide users with information about the Software's Energy
Consumption, including:
- **a)** Typical energy use under common workloads;
- **b)** Power-saving features and how to enable them;
- **c)** Idle power consumption;
- **d)** Recommended hardware for optimal efficiency.

### 4. Idle Efficiency.

The Software must not consume more than 5% of typical active Energy
Consumption when idle, unless the Software's primary function requires
continuous active processing.

### 5. Resource Awareness.

The Software should:
- Release unused memory promptly;
- Cease background processing when not needed;
- Adapt to the device's power state (battery vs. mains);
- Not pollute CPU caches or storage with unnecessary data.

### 6. Termination.

Significant undocumented efficiency regressions terminate rights.
A 90-day cure period applies.

### 7. Disclaimer of Warranty.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ENERGY EFFICIENCY.

### 8. Limitation of Liability.

IN NO EVENT SHALL THE COPYRIGHT HOLDER BE LIABLE FOR ENERGY COSTS.

**END OF TERMS AND CONDITIONS**


## How to Apply These Terms

Include the following notice:

```
<Software name>
Copyright (C) <year> <author>
Licensed under the Energy Efficiency License, version 1.0 (EEL-1.0).
Energy consumption disclosure required.
Full terms: <URL>.
```
