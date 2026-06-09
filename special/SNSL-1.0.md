# Sensor Network License, Version 1.0 (SNSL-1.0)

**Copyright (C) 2026 [Your Name or Organization]**

A license for sensor network software requiring data minimization, mesh interoperability, and energy-aware operation.

## Preamble

The SNSL governs software for distributed sensor networks. It mandates data minimization (collect only what is needed), mesh interoperability (sensors must work with other vendors), and energy-aware operation (optimize for battery life). It prevents vendor lock-in and privacy-invasive data collection in sensor deployments.

## TERMS AND CONDITIONS

### 0. Definitions.

"This License" refers to version 1.0 of the Sensor Network License (SNSL-1.0).

"The Software" means the sensor network firmware or platform licensed under this License.

"Mesh Network" means a network topology where each sensor node can relay data for others.

"Sensor Data" means measurements or observations collected by sensor nodes.

### 1. Permissions.

You may use, copy, modify, and distribute the Software, subject to the sensor network conditions below.

### 2. Data Minimization.

The Software must:
- **a)** Collect only data necessary for the stated purpose;
- **b)** Support configurable collection intervals;
- **c)** Delete raw data after processing where feasible.

### 3. Mesh Interoperability.

If the Software participates in a Mesh Network:
- **a)** It must use open or documented protocols;
- **b)** It must not block relay of data from other vendors;
- **c)** It must support standard routing protocols.

### 4. Energy Awareness.

The Software should optimize for energy efficiency:
- **a)** Support sleep/wake cycles;
- **b)** Minimize radio transmissions;
- **c)** Provide power consumption documentation.

### 5. Security.

Sensor data must be encrypted in transit, and nodes must authenticate before joining the network.

### 6. Termination.

Violating data minimization or blocking mesh interoperability terminates rights. A 60-day cure period applies.

### 7. Disclaimer of Warranty. Limitation of Liability.

THE SOFTWARE IS PROVIDED "AS IS". IN NO EVENT SHALL THE AUTHORS BE LIABLE.

**END OF TERMS AND CONDITIONS**
