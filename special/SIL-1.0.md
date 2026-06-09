# Simulation License, Version 1.0 (SIL-1.0)

**Copyright (C) 2026 [Your Name or Organization]**

A license for simulation environments, digital twins, and synthetic
testbeds, requiring output labeling and prohibiting representation of
simulations as real-world data.

## Preamble

The SIL addresses the unique nature of simulation software: it models
real-world systems but produces synthetic outputs.  Users must clearly
label simulation results as such, document the simulation parameters and
limitations, and not represent simulated data as real-world observations.
It is designed for digital twin platforms, physics simulators, and
synthetic test environments.

## TERMS AND CONDITIONS

### 0. Definitions.

"This License" refers to version 1.0 of the Simulation License (SIL-1.0).

"The Software" means the simulation environment, digital twin platform, or
simulation engine licensed under this License.

"Simulation Output" means any data, visualization, prediction, or result
produced by running the Software.

"Digital Twin" means a virtual representation of a real-world system that
is updated with real-world data.

"Simulation Parameters" means the configuration, initial conditions,
boundary conditions, and model settings used to produce Simulation Output.

### 1. Permissions.

You may use, copy, modify, and distribute the Software for any lawful
purpose, subject to the simulation integrity conditions below.

### 2. Output Labeling.

All Simulation Output must be clearly labeled as simulated data.  The
label must be conspicuous and include:
- **a)** A statement that the data is simulated, not real;
- **b)** The Software version and Simulation Parameters used;
- **c)** Known limitations or deviations from real-world behavior.

### 3. No Misrepresentation.

You may not represent Simulation Output as:
- Real-world measurements or observations;
- Actual system behavior unless validated against real-world data;
- Scientific evidence without appropriate qualifications.

### 4. Validation Disclosure.

If you claim that the Software accurately represents a specific real-world
system, you must disclose:
- The validation methodology used;
- The accuracy metrics and confidence intervals;
- The conditions under which the simulation is valid.

### 5. Digital Twin Requirements.

If the Software is used as a Digital Twin, you must:
- Maintain a clear separation between simulated and real data;
- Document the synchronization frequency and methodology;
- Disclose any discrepancies between the Digital Twin and the real system.

### 6. Termination.

Misrepresentation of simulation as real data terminates all rights with no
cure.

### 7. Disclaimer of Warranty.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF SIMULATION ACCURACY.

### 8. Limitation of Liability.

IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR DECISIONS BASED ON SIMULATION
OUTPUT.

**END OF TERMS AND CONDITIONS**


## How to Apply These Terms

Include the following notice:

```
<Simulation name> v<version>
Copyright (C) <year> <author>
Licensed under the Simulation License, version 1.0 (SIL-1.0).
Simulation output must be labeled as simulated.
Full terms: <URL>.
```
